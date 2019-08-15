# symlinks
Scans directories for symbolic links, and identifies dangling, relative, absolute, messy, and other_fs links.
Can optionally change absolute links to relative within a given filesystem.
Recommended for use by anyone developing and/or maintaining Linux FTP site or distribution or CD-ROM.

All credit goes to Mark Lord.

the original tarball is included as  *symlinks-1.4.tar.gz*

To compile on OSX:

**gcc-9 -I /Library/Developer/CommandLineTools/SDKs/MacOSX.sdk/usr/include/malloc  -Wall -Wstrict-prototypes -O2 -o symlinks symlinks.c**

The Mach-O 64-bit executable x86_64 binary *symlinks* was compiled via homebrew on Mojave.

![Image ](/linkmess.jpg)
