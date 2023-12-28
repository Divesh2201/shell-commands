# shell-commands-cheatsheet

Bourne-again shell (Bash) is a command line language interpreter for the GNU OS.

Linux is GUI with optional command line while Unix is only command line

1. `strings`: see the text inside a binary/data file

   `-n <length>`: specify the length of strings we want, default 4
    
2. `open`: open an image in preview
3. `exiftool`: working with metadata on command line
4. `binwalk`: searches a binary image for embedded files and executable code
5. `chmod`: change mod is used to change permissions for a file
   eg: chmod +x is adding execute permissions (- is remove, = is assign, etc)
6. `ls -ld`: lists permissions (10 digit)
   first digit represents 'd' for directory and '-' for file
   next 9 are split into three 3's, owner, group and world
   eg: drwxr-xr-x, so here we have read write and execute permissions as owner
7. `curl`: client URL allows you to exchange data between server and cli
8. `man`: manual for a command, eg: man binwalk
9. `grep`: global regular expression print, to search matching patterns in a file
10. `2>/dev/null`: redirect the stderr (>) to <file> and don't print on terminal (/dev/null supressing the output, null)
11. `2?&1`: redirect stderr to stdout, & tells shell that 1 is not a filename but file descriptor (file descriptor 1 is stdout, 2 is stderr)
    
