This is version 6.32 of the Inform compiler,
copyright (c) Graham Nelson 1993 - 2010
Full release notes and instructions are available at
http://www.inform-fiction.org/
and
http://www.ifarchive.org/indexes/if-archiveXinfocomXcompilersXinform6.html


This is a minor update to Inform 6.31. The only changes between 6.32 and
6.31 are the application of the following patches:

C63007: Strict mode not available in V3/4 games
http://www.inform-fiction.org/patches/C63007.html

C63102: Support $ALLOC_CHUNK_SIZE memory setting
http://www.inform-fiction.org/patches/C63102.html

C63104: Support @push and @pull macros in Glulx
http://www.inform-fiction.org/patches/C63104.html

C63107: Glulx support for custom opcodes
http://www.inform-fiction.org/patches/C63107.html

C63108: Glulx support for compilation control
http://www.inform-fiction.org/patches/C63108.html

C63110: Crash when grammar table exceeds readable memory
http://www.inform-fiction.org/patches/C63110.html

C63112: Exactly 64Kb of readable memory gives corrupt game
http://www.inform-fiction.org/patches/C63112.html

Glulx 3.0 Unicode support
http://www.eblong.com/zarf/glulx/inform63u.patch

Glulx 3.1 memory heap support
http://www.eblong.com/zarf/glulx/inform63mall.patch

Add #g$GLOBAL syntax for the address of a global variable
http://www.eblong.com/zarf/glulx/inform63globref.patch

Glulx 3.1.1 acceleration support
http://www.eblong.com/zarf/glulx/inform63accel.patch

Glulx memory map extension
http://www.eblong.com/zarf/glulx/inform631n-memmap.patch

Support for printing Unicode characters with "print (char)"
http://eblong.com/zarf/glulx/inform631n-unichar.patch

Support for compiling the game dictionary with Unicode characters
http://eblong.com/zarf/glulx/inform631n-unidict.patch
http://eblong.com/zarf/glulx/inform631n-unidict2.patch

Glulx 3.1.2 floating-point support
http://eblong.com/zarf/glulx/inform631n-float.patch

Support for floating-point literals of the form "$+1.0e+1"
http://eblong.com/zarf/glulx/inform631n-floatconst.patch

Show veneer routines in assembly output
http://mailman-new.greennet.org.uk/pipermail/inform-maintenance/2009-January/001704.html

Allow more than 255 verbs in Glulx. Note that this is only a compiler
change, and requires the library to use both bytes of the verb number
for it to work.
http://mailman-new.greennet.org.uk/pipermail/inform-maintenance/2009-April/001705.html

Remove one argument form of Glulx print_to_array() veneer method
http://mailman-new.greennet.org.uk/pipermail/inform-maintenance/2009-November/001709.html

Increased PATHLEN and set the HUGE memory model as the default for
OSX, Linux, Unix and Unix64.


