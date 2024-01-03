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
7. `curl`/`wget`: client URL / www get - allows you to exchange data between server and cli
8. `man`: manual for a command, eg: man binwalk
9. `grep`: global regular expression print, to search matching patterns in a file
10. `2>/dev/null`: redirect the stderr (>) to <file> and don't print on terminal (/dev/null supressing the output, null)
11. `2?&1`: redirect stderr to stdout, & tells shell that 1 is not a filename but file descriptor (file descriptor 1 is stdout, 2 is stderr)
12. `--`: is used to denote end of flags. eg: you want to mkdir -q (-q is the name of the directory), then `mkdir -- -q`
13. `s` is for scrolling down (macOS) (`j` for parrotOS) and `k` for scrolling up inside `man`, use `/<search>` for searching your flag
14. `cat <file_name(s)>` reads and prints contents of a file
15. `nc`: 'NetCat' is like a cat command over a network. It is a networking communication tool used to read and write data to network connections (ports) using TCP/UDP
16. Pager program: helps the user get the output, on the terminal, one page at a time. Popular pagers in Unix are `more` and `less`
17. `objdump`: program for displaying information about object files in Unix, eg: used as a disassembler to view executable in assembly form
18. `file` command gives information about the file you pass
19. `ltrace` intercepts and records dynamic library calls, similar `strace` traces system calls called by a process
    
