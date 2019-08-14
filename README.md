# symlinks
Scans directories for symbolic links, and identifies dangling, relative, absolute, messy, and other_fs links.
Can optionally change absolute links to relative within a given filesystem.
Recommended for use by anyone developing and/or maintaining Linux FTP site or distribution or CD-ROM.

All credit goes to Mark Lord.

I just modified the Makefile for using gcc-9 on OS-X. 
The Mach-O 64-bit executable x86_64 binary *symlinks* was compiled via homebrew on Mojave.

