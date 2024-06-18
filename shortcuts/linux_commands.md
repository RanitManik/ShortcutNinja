# Linux Shortcuts

| Command    | Description                                                 | Example                                                                                     |
|------------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| adduser    | Add a new user                                              | `adduser newusername`                                                                       |
| arch       | Print machine architecture                                  | `arch`                                                                                      |
| awk        | Find and replace text within file(s)                        | `awk '/pattern/ {print $2}' filename`                                                       |
| bc         | An arbitrary precision calculator language                  | `echo "5+5" \| bc`                                                                          |
| cal        | Display a calendar                                          | `cal`                                                                                       |
| cat        | Concatenate files and print on the standard output          | `cat file1.txt file2.txt`                                                                   |
| cd         | Change working directory                                    | `cd /path/to/directory`                                                                     |
| chgrp      | Change the group ownership of files                         | `chgrp groupname filename`                                                                  |
| chkconfig  | Tool for maintaining the /etc/rc[0-6].d directory hierarchy | `chkconfig --list`                                                                          |
| chmod      | Change the access permissions of files and directories      | `chmod 755 filename`                                                                        |
| chown      | Change the user and group ownership of files                | `chown username:groupname filename`                                                         |
| chroot     | Change root directory                                       | `chroot /new/root/directory`                                                                |
| cksum      | Print CRC checksum and byte counts                          | `cksum filename`                                                                            |
| clear      | Clear terminal screen                                       | `clear`                                                                                     |
| cmp        | Compare two files                                           | `cmp file1.txt file2.txt`                                                                   |
| comm       | Compare two sorted files line by line                       | `comm file1.txt file2.txt`                                                                  |
| cp         | Copy one or more files to another location                  | `cp sourcefile destination`                                                                 |
| cron       | Daemon to execute scheduled commands                        | `crontab -e` (to edit crontab)                                                              |
| crontab    | Schedule a command to run at a later time                   | `crontab -l` (to list crontab entries)                                                      |
| csplit     | Split a file into context-determined pieces                 | `csplit filename /pattern/`                                                                 |
| cut        | Divide a file into several parts                            | `cut -f 1,3 filename`                                                                       |
| date       | Display or change the date & time                           | `date`                                                                                      |
| dc         | Desk calculator                                             | `echo "5 3 + p" \| dc`                                                                      |
| dd         | Data dump - convert and copy a file                         | `dd if=inputfile of=outputfile bs=blocksize`                                                |
| df         | Display free disk space                                     | `df -h` (human-readable format)                                                             |
| diff       | Display the differences between two files                   | `diff file1.txt file2.txt`                                                                  |
| diff3      | Show differences among three files                          | `diff3 file1.txt file2.txt file3.txt`                                                       |
| dir        | Briefly list directory contents                             | `dir`                                                                                       |
| dircolors  | Color setup for `ls`                                        | `dircolors` (to set up colors for ls command)                                               |
| dirname    | Convert a full pathname to just a path                      | `dirname /path/to/file`                                                                     |
| du         | Estimate file space usage                                   | `du -sh directory` (show disk usage summary in human-readable format)                       |
| echo       | Display message on screen                                   | `echo "Hello, World!"`                                                                      |
| ed         | A line-oriented text editor (edlin)                         | `ed filename` (to edit a file)                                                              |
| egrep      | Search file(s) for lines that match an extended expression  | `egrep 'pattern' filename`                                                                  |
| eject      | Eject CD-ROM                                                | `eject`                                                                                     |
| env        | Display, set, or remove environment variables               | `env`                                                                                       |
| expand     | Convert tabs to spaces                                      | `expand filename` (convert tabs to spaces)                                                  |
| expr       | Evaluate expressions                                        | `expr 5 + 3` (perform arithmetic operations)                                                |
| factor     | Print prime factors                                         | `factor 12` (factorization of a number)                                                     |
| false      | Do nothing, unsuccessfully                                  | `false`                                                                                     |
| fdformat   | Low-level format a floppy disk                              | `fdformat /dev/fd0` (format floppy disk)                                                    |
| fdisk      | Partition table manipulator for Linux                       | `fdisk /dev/sdX` (replace X with drive identifier)                                          |
| fgrep      | Search file(s) for lines that match a fixed string          | `fgrep 'pattern' filename`                                                                  |
| find       | Search for files that meet a desired criteria               | `find /path/to/search -name "filename"`                                                     |
| fmt        | Reformat paragraph text                                     | `fmt -w 80 filename` (reformat text to 80 columns)                                          |
| fold       | Wrap text to fit a specified width                          | `fold -w 80 filename` (wrap text to 80 columns)                                             |
| free       | Display memory usage                                        | `free -h` (human-readable format)                                                           |
| fsck       | Filesystem consistency check and repair                     | `fsck /dev/sdX` (replace X with drive identifier)                                           |
| gawk       | Find and replace text within file(s)                        | `gawk '/pattern/ {print $2}' filename`                                                      |
| grep       | Search file(s) for lines that match a given pattern         | `grep 'pattern' filename`                                                                   |
| groups     | Print group names a user is in                              | `groups username`                                                                           |
| gzip       | Compress or decompress named file(s)                        | `gzip filename` (compress file)                                                             |
| head       | Output the first part of file(s)                            | `head -n 10 filename` (display first 10 lines)                                              |
| hostname   | Print or set system name                                    | `hostname`                                                                                  |
| id         | Print user and group id's                                   | `id`                                                                                        |
| info       | Help info                                                   | `info command` (get information about a command)                                            |
| install    | Copy files and set attributes                               | `install -m 644 sourcefile destination` (copy with permissions)                             |
| join       | Join lines on a common field                                | `join file1.txt file2.txt`                                                                  |
| kill       | Stop a process from running                                 | `kill -9 process_id` (forcefully terminate a process)                                       |
| less       | Display output one screen at a time                         | `less filename` (view file content)                                                         |
| ln         | Make links between files                                    | `ln -s sourcefile linkname` (create a symbolic link)                                        |
| locate     | Find files                                                  | `locate filename` (find the path of a file)                                                 |
| logname    | Print current login name                                    | `logname` (display the current user's login name)                                           |
| lpc        | Line printer control program                                | `lpc status` (check printer status)                                                         |
| lpr        | Off line print                                              | `lpr filename` (print a file)                                                               |
| lprm       | Remove jobs from the print queue                            | `lprm jobnumber` (remove a print job)                                                       |
| ls         | List information about file(s)                              | `ls -l` (long format listing)                                                               |
| man        | Help manual                                                 | `man command` (display manual for a command)                                                |
| mkdir      | Create new folder(s)                                        | `mkdir newfolder`                                                                           |
| mkfifo     | Make FIFOs (named pipes)                                    | `mkfifo mypipe` (create a named pipe)                                                       |
| mknod      | Make block or character special files                       | `mknod /dev/mydevice c 10 1` (create a character device)                                    |
| more       | Display output one screen at a time                         | `more filename` (display file content)                                                      |
| mount      | Mount a file system                                         | `mount /dev/sdX1 /mnt` (replace X with drive identifier)                                    |
| mv         | Move or rename files or directories                         | `mv oldfile newfile` (rename file)                                                          |
| nice       | Set the priority of a command or job                        | `nice -n 10 command` (set priority)                                                         |
| nl         | Number lines and write files                                | `nl filename` (number lines in a file)                                                      |
| nohup      | Run a command immune to hangups                             | `nohup command &` (run command in the background)                                           |
| passwd     | Modify a user password                                      | `passwd username` (change user password)                                                    |
| paste      | Merge lines of files                                        | `paste file1.txt file2.txt`                                                                 |
| pathchk    | Check file name portability                                 | `pathchk filename` (check portability)                                                      |
| pr         | Convert text files for printing                             | `pr -t -e5 filename` (print with 5 lines per page)                                          |
| printcap   | Printer capability database                                 | `printcap` (display printer capabilities)                                                   |
| printenv   | Print environment variables                                 | `printenv` (display environment variables)                                                  |
| printf     | Format and print data                                       | `printf "Hello, World"`                                                                     |
| ps         | Process status                                              | `ps aux` (display all processes)                                                            |
| pwd        | Print working directory                                     | `pwd` (display current directory)                                                           |
| quota      | Display disk usage and limits                               | `quota` (check disk usage)                                                                  |
| quotacheck | Scan a file system for disk usage                           | `quotacheck -avug` (scan file system for all users and groups)                              |
| quotactl   | Set disk quotas                                             | `quotactl -u username -b -e /dev/sdX1` (set quotas for a user)                              |
| ram        | Ram disk device                                             | `mount -t tmpfs -o size=512m tmpfs /mnt` (create a RAM disk)                                |
| rcp        | Copy files between machines                                 | `rcp filename remote:/path/to/destination`                                                  |
| read       | Read a line from standard input                             | `read variable` (read input into a variable)                                                |
| readonly   | Mark variables/functions as readonly                        | `readonly MY_VAR=value` (set read-only variable)                                            |
| renice     | Alter priority of running processes                         | `renice 10 -p process_id` (change process priority)                                         |
| remsync    | Synchronize remote files                                    | `remsync` (synchronize files between remote systems)                                        |
| rm         | Remove files or directories                                 | `rm filename` (remove file)                                                                 |
| rmdir      | Remove empty folders                                        | `rmdir foldername`                                                                          |
| rsync      | Remote file and directory synchronization                   | `rsync -avz /path/to/source /path/to/destination` (sync files between directories)          |
| screen     | Terminal multiplexor                                        | `screen` (start a new screen session)                                                       |
| scp        | Secure copy (remote file copy)                              | `scp filename user@remote:/path/to/destination` (copy file to remote system)                |
| sdiff      | Merge two files interactively                               | `sdiff file1.txt file2.txt` (interactively merge files)                                     |
| sed        | Stream editor                                               | `sed 's/pattern/replacement/g' filename` (replace pattern in file)                          |
| select     | Accept keyboard input                                       | `select var in list; do command; done` (display a list for selection)                       |
| seq        | Print numeric sequences                                     | `seq 1 10` (print numbers 1 to 10)                                                          |
| set        | Set shell options                                           | `set -o option` (enable shell option)                                                       |
| sftp       | Secure File Transfer Protocol                               | `sftp user@remote` (start sftp session with remote system)                                  |
| shift      | Shift positional parameters                                 | `shift` (move positional parameters to the left)                                            |
| shopt      | Shell options                                               | `shopt -s option` (enable shell option)                                                     |
| shutdown   | Shutdown or restart Linux                                   | `shutdown -h now` (shutdown system immediately)                                             |
| sleep      | Delay for a specified time                                  | `sleep 5` (delay for 5 seconds)                                                             |
| sort       | Sort text files                                             | `sort filename` (sort file content)                                                         |
| source     | Run commands from a file `.`                                | `source filename` (execute commands from file)                                              |
| split      | Split a file into fixed-size pieces                         | `split -b 10M filename` (split file into 10MB pieces)                                       |
| ssh        | Secure Shell client (remote login program)                  | `ssh user@remote` (login to remote system)                                                  |
| strace     | Trace system calls and signals                              | `strace command` (trace system calls made by a command)                                     |
| su         | Substitute user identity                                    | `su - username` (switch to another user)                                                    |
| sudo       | Execute a command as another user                           | `sudo command` (execute command with superuser privileges)                                  |
| sum        | Print a checksum for a file                                 | `sum filename` (calculate checksum of file)                                                 |
| suspend    | Suspend execution of this shell                             | `suspend` (pause current shell session)                                                     |
| sync       | Synchronize data on disk with memory                        | `sync` (flush file system buffers)                                                          |
| tail       | Output the last part of file                                | `tail -n 10 filename` (display last 10 lines of file)                                       |
| tar        | Store, list or extract files in an archive                  | `tar -cvf archive.tar directory` (create tar archive)                                       |
| tee        | Redirect output to multiple files                           | `command \| tee filename` (write output to file and display)                                |
| test       | Evaluate a conditional expression                           | `test -e filename` (check if file exists)                                                   |
| time       | Measure program running time                                | `time command` (measure execution time of command)                                          |
| times      | Print shell and user times                                  | `times` (display user and system times)                                                     |
| touch      | Change file timestamps                                      | `touch filename` (create an empty file)                                                     |
| top        | Display Linux tasks                                         | `top` (display active processes)                                                            |
| traceroute | Trace route to a network host                               | `traceroute hostname` (trace route to remote host)                                          |
| true       | Do nothing, successfully                                    | `true`                                                                                      |
| tsort      | Topological sort                                            | `tsort filename` (perform topological sort)                                                 |
| tty        | Print terminal linked to standard input                     | `tty` (display terminal device)                                                             |
| type       | Describe a command                                          | `type command` (display information about command)                                          |
| ulimit     | Limit user resources                                        | `ulimit -n 1024` (set maximum number of open files)                                         |
| umask      | Users file creation mask                                    | `umask 022` (set default file permissions)                                                  |
| umount     | Unmount a device                                            | `umount /dev/sdX1` (replace X with drive identifier)                                        |
| unalias    | Remove an alias                                             | `unalias aliasname`                                                                         |
| uname      | Print system information                                    | `uname -a` (display all system information)                                                 |
| unexpand   | Convert spaces to tabs                                      | `unexpand filename` (replace spaces with tabs)                                              |
| uniq       | Uniquify files                                              | `uniq filename` (remove duplicate lines)                                                    |
| units      | Convert units from one scale to another                     | `units '10 kg' 'lb'` (convert 10 kilograms to pounds)                                       |
| unset      | Remove variable or function names                           | `unset variable` (delete a variable)                                                        |
| unshar     | Unpack shell archive scripts                                | `unshar filename` (unpack a shell archive)                                                  |
| until      | Execute commands (until error)                              | `until condition; do command; done` (repeat commands until condition is true)               |
| uptime     | Show uptime                                                 | `uptime` (display system uptime)                                                            |
| useradd    | Create new user                                             | `useradd newusername` (create a new user)                                                   |
| usermod    | Modify user                                                 | `usermod -aG groupname username` (add user to group)                                        |
| users      | List users currently logged in                              | `users` (display logged in users)                                                           |
| uuencode   | Encode a binary file                                        | `uuencode filename > encodedfile` (encode file)                                             |
| uudecode   | Decode a file                                               | `uudecode encodedfile` (decode file)                                                        |
| v          | Verbosely list directory contents `ls -l -b`                | `v` (display directory contents verbosely)                                                  |
| vdir       | Verbosely list directory contents                           | `vdir` (list directory contents)                                                            |
| vi         | Text editor                                                 | `vi filename` (edit file using vi editor)                                                   |
| vmstat     | Report virtual memory statistics                            | `vmstat` (display memory statistics)                                                        |
| wait       | Wait for a process to complete                              | `wait process_id` (wait for process to complete)                                            |
| watch      | Execute/display a program periodically                      | `watch command` (repeat command every 2 seconds)                                            |
| wc         | Print byte, word, and line counts                           | `wc filename` (count lines, words, and bytes)                                               |
| whereis    | Search for binaries, sources, and manuals                   | `whereis command` (locate command binaries)                                                 |
| which      | Locate a program file in the user's path                    | `which command` (find location of command)                                                  |
| while      | Execute commands                                            | `while condition; do command; done` (repeat commands while condition is true)               |
| who        | Print all usernames currently logged in                     | `who` (list logged in users)                                                                |
| whoami     | Print the current user id and name                          | `whoami` (display current username)                                                         |
| xargs      | Execute utility, passing constructed argument list(s)       | `xargs command` (build and execute command lines from input)                                |
| yes        | Print a string until interrupted                            | `yes` (output repeated string)                                                              |
