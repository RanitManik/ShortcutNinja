# Linux Shortcuts

| Command    | Description                                                | Example                                                   |
|------------|------------------------------------------------------------|-----------------------------------------------------------|
| adduser    | Add a new user                                              | `adduser newusername`                                     |
| arch       | Print machine architecture                                 | `arch`                                                    |
| awk        | Find and Replace text within file(s)                       | `awk '/pattern/ {print $2}' filename`                     |
| bc         | An arbitrary precision calculator language                 | `echo "5+5" | bc`                                         |
| cal        | Display a calendar                                         | `cal`                                                     |
| cat        | Concatenate files and print on the standard output         | `cat file1.txt file2.txt`                                |
| chdir      | Change working directory                                   | `cd /path/to/directory`                                  |
| chgrp      | Change the group ownership of files                         | `chgrp groupname filename`                              |
| chkconfig  | Tool for maintaining the /etc/rc[0-6].d directory hierarchy| `chkconfig --list`                                       |
| chmod      | Change the access permissions of files and directories     | `chmod 755 filename`                                     |
| chown      | Change the user and group ownership of files               | `chown username:groupname filename`                     |
| chroot     | Change root directory                                      | `chroot /new/root/directory`                            |
| cksum      | Print CRC checksum and byte counts                         | `cksum filename`                                        |
| clear      | Clear terminal screen                                      | `clear`                                                  |
| cmp        | Compare two files                                          | `cmp file1.txt file2.txt`                               |
| comm       | Compare two sorted files line by line                       | `comm file1.txt file2.txt`                              |
| cp         | Copy one or more files to another location                 | `cp sourcefile destination`                             |
| cron       | Daemon to execute scheduled commands                       | `crontab -e` (to edit crontab)                          |
| crontab    | Schedule a command to run at a later time                   | `crontab -l` (to list crontab entries)                   |
| csplit     | Split a file into context-determined pieces                 | `csplit filename /pattern/`                             |
| cut        | Divide a file into several parts                            | `cut -f 1,3 filename`                                   |
| date       | Display or change the date & time                           | `date`                                                  |
| dc         | Desk Calculator                                            | `echo "5 3 + p" | dc`                                   |
| dd         | Data Dump - Convert and copy a file                         | `dd if=inputfile of=outputfile bs=blocksize`           |
| df         | Display free disk space                                    | `df -h` (human-readable format)                         |
| diff       | Display the differences between two files                   | `diff file1.txt file2.txt`                             |
| diff3      | Show differences among three files                         | `diff3 file1.txt file2.txt file3.txt`                  |
| dir        | Briefly list directory contents                             | `dir`                                                   |
| dircolors  | Colour setup for `ls'                                      | `dircolors` (to set up colors for ls command)          |
| dirname    | Convert a full pathname to just a path                      | `dirname /path/to/file`                                 |
| du         | Estimate file space usage                                  | `du -sh directory` (show disk usage summary in human-readable format)|
| echo       | Display message on screen                                   | `echo "Hello, World!"`                                  |
| ed         | A line-oriented text editor (edlin)                         | `ed filename` (to edit a file)                         |
| egrep      | Search file(s) for lines that match an extended expression  | `egrep 'pattern' filename`                              |
| eject      | Eject CD-ROM                                               | `eject`                                                 |
| env        | Display, set, or remove environment variables               | `env`                                                   |
| expand     | Convert tabs to spaces                                      | `expand filename` (convert tabs to spaces)            |
| expr       | Evaluate expressions                                       | `expr 5 + 3` (perform arithmetic operations)           |
| factor     | Print prime factors                                        | `factor 12` (factorization of a number)                |
| false      | Do nothing, unsuccessfully                                 | `false`                                                 |
| fdformat   | Low-level format a floppy disk                              | `fdformat /dev/fd0` (format floppy disk)               |
| fdisk      | Partition table manipulator for Linux                       | `fdisk /dev/sdX` (replace X with drive identifier)     |
| fgrep      | Search file(s) for lines that match a fixed string          | `fgrep 'pattern' filename`                              |
| find       | Search for files that meet a desired criteria               | `find /path/to/search -name "filename"`                |
| fmt        | Reformat paragraph text                                    | `fmt -w 80 filename` (reformat text to 80 columns)    |
| fold       | Wrap text to fit a specified width                          | `fold -w 80 filename` (wrap text to 80 columns)       |
| format     | Format disks or tapes                                      | `format` (to start disk formatting tool)               |
| free       | Display memory usage                                       | `free -h` (human-readable format)                      |
| fsck       | Filesystem consistency check and repair                     | `fsck /dev/sdX` (replace X with drive identifier)     |
| gawk       | Find and Replace text within file(s)                        | `gawk '/pattern/ {print $2}' filename`                 |
| grep       | Search file(s) for lines that match a given pattern         | `grep 'pattern' filename`                              |
| groups     | Print group names a user is in                              | `groups username`                                      |
| gzip       | Compress or decompress named file(s)                        | `gzip filename` (compress file)                        |
| head       | Output the first part of file(s)                            | `head -n 10 filename` (display first 10 lines)         |
| hostname   | Print or set system name                                    | `hostname`                                              |
| id         | Print user and group id's                                   | `id`                                                    |
| info       | Help info                                                  | `info command` (get information about a command)      |
| install    | Copy files and set attributes                               | `install -m 644 sourcefile destination` (copy with permissions)|
| join       | Join lines on a common field                                | `join file1.txt file2.txt`                             |
| kill       | Stop a process from running                                 | `kill -9 process_id` (forcefully terminate a process) |
| less       | Display output one screen at a time                         | `less filename` (view file content)                   |
| ln         | Make links between files                                    | `ln -s sourcefile linkname` (create a symbolic link)  |
| locate     | Find files                                                 | `locate filename` (find the path of a file)           |
| logname    | Print current login name

                                    | `logname` (display the current user's login name)      |
| lpc        | Line printer control program                               | `lpc status` (check printer status)                   |
| lpr        | Off line print                                             | `lpr filename` (print a file)                         |
| lprm       | Remove jobs from the print queue                            | `lprm jobnumber` (remove a print job)                  |
| ls         | List information about file(s)                              | `ls -l` (long format listing)                           |
| man        | Help manual                                                | `man command` (display manual for a command)          |
| mkdir      | Create new folder(s)                                        | `mkdir newfolder`                                      |
| mkfifo     | Make FIFOs (named pipes)                                    | `mkfifo mypipe` (create a named pipe)                  |
| mknod      | Make block or character special files                       | `mknod /dev/mydevice c 10 1` (create a character device)|
| more       | Display output one screen at a time                         | `more filename` (display file content)                |
| mount      | Mount a file system                                         | `mount /dev/sdX1 /mnt` (replace X with drive identifier)|
| mv         | Move or rename files or directories                         | `mv oldfile newfile` (rename file)                    |
| nice       | Set the priority of a command or job                         | `nice -n 10 command` (set priority)                    |
| nl         | Number lines and write files                                | `nl filename` (number lines in a file)                |
| nohup      | Run a command immune to hangups                              | `nohup command &` (run command in the background)     |
| passwd     | Modify a user password                                      | `passwd username` (change user password)              |
| paste      | Merge lines of files                                        | `paste file1.txt file2.txt`                           |
| pathchk    | Check file name portability                                 | `pathchk filename` (check portability)                 |
| pr         | Convert text files for printing                             | `pr -t -e5 filename` (print with 5 lines per page)    |
| printcap   | Printer capability database                                 | `printcap` (display printer capabilities)             |
| printenv   | Print environment variables                                 | `printenv` (display environment variables)            |
| printf     | Format and print data                                       | `printf "Hello, %s!\n" username` (formatted print)   |
| ps         | Process status                                             | `ps aux` (display all running processes)              |
| pwd        | Print Working Directory                                    | `pwd` (display current working directory)             |
| quota      | Display disk usage and limits                               | `quota -u username` (display disk usage for a user)   |
| quotacheck | Scan a file system for disk usage                            | `quotacheck -v /path/to/filesystem` (scan and report disk usage)|
| quotactl   | Set disk quotas                                             | `quotactl -u username /path/to/filesystem` (set disk quotas)|
| ram        | Ram disk device                                            | `ram` (create a ram disk)                             |
| rcp        | Copy files between two machines                             | `rcp file.txt user@remote:/path/to/destination`      |
| rm         | Remove files                                               | `rm filename` (remove file)                           |
| rmdir      | Remove folder(s)                                           | `rmdir emptyfolder` (remove empty folder)             |
| rpm        | Remote Package Manager                                      | `rpm -ivh packagename.rpm` (install a package)        |
| rsync      | Remote file copy (Synchronize file trees)                   | `rsync -av source/ destination/` (synchronize directories)|
| screen     | Terminal window manager                                     | `screen` (start a new terminal session)               |
| sdiff      | Merge two files interactively                               | `sdiff file1.txt file2.txt`                           |
| sed        | Stream Editor                                              | `sed 's/pattern/replacement/' filename` (find and replace)|
| select     | Accept keyboard input                                      | `select var in option1 option2 option3; do echo "You selected $var"; done` (menu selection)|
| seq        | Print numeric sequences                                     | `seq 1 10` (print sequence from 1 to 10)             |
| shutdown   | Shutdown or restart Linux                                   | `shutdown now` (shutdown immediately)                 |
| sleep      | Delay for a specified time                                  | `sleep 5` (sleep for 5 seconds)                       |
| sort       | Sort text files                                            | `sort filename` (sort lines in a file)                |
| split      | Split a file into fixed-size pieces                         | `split -l 100 filename` (split file into 100-line parts)|
| su         | Substitute user identity                                    | `su username` (switch user)                           |
| sum        | Print a checksum for a file                                 | `sum filename` (calculate checksum)                   |
| symlink    | Make a new name for a file                                   | `ln -s sourcefile linkname` (create a symbolic link)  |
| sync       | Synchronize data on disk with memory                         | `sync` (synchronize data to disk)                    |
| tac        | Concatenate and write files in reverse                      | `tac filename` (concatenate and display in reverse order)|
| tail       | Output the last part of files                                | `tail -n 10 filename` (display last 10 lines)         |
| tar        | Tape Archiver                                              | `tar -cvf archive.tar file1 file2` (create a tar archive)|
| tee        | Redirect output to multiple files                           | `command | tee output.txt` (store output in a file and display on the console)|
| test       | Evaluate a conditional expression                           | `[ -e filename ] && echo "File exists"` (check if a file exists)|
| time       | Measure Program Resource Use                                | `time command` (measure the execution time of a command)|
| touch      | Change file timestamps                                      | `touch filename` (update file timestamps)           |
| top        | List processes running on the system                        | `top` (display dynamic information about running processes)|
| traceroute | Trace Route to Host                                         | `traceroute example.com` (trace route to a host)      |
| tr         | Translate, squeeze, and/or delete characters               | `tr 'a-z' 'A-Z' < input.txt` (translate lowercase to uppercase)|
| true       | Do nothing, successfully                                   | `true` (do nothing and exit successfully)             |
| tsort      | Topological sort                                           | `tsort filename` (perform topological sort)           |
| tty        | Print filename of terminal on stdin                         | `tty` (display filename of terminal)                  |
| umount     | Unmount a device                                            | `umount /mnt` (unmount a mounted device)             |
| uname      | Print system information                                    | `uname -a` (display system information)              

 |
| unexpand   | Convert spaces to tabs                                      | `unexpand -t 4 filename` (convert spaces to tabs)    |
| uniq       | Uniquify files                                              | `uniq filename` (remove consecutive duplicate lines)|
| units      | Convert units from one scale to another                     | `units "1 meter" "feet"` (convert units)             |
| unshar     | Unpack shell archive scripts                                | `unshar archive.shar` (unpack shell archive)          |
| useradd    | Create new user account                                     | `useradd newuser` (create a new user)                |
| usermod    | Modify user account                                         | `usermod -aG groupname username` (add user to a group)|
| users      | List users currently logged in                              | `users` (display currently logged-in users)         |
| uuencode   | Encode a binary file                                        | `uuencode filename encodedfile` (encode a binary file)|
| uudecode   | Decode a file created by uuencode                           | `uudecode encodedfile` (decode a uuencoded file)     |
| vdir       | Verbosely list directory contents (`ls -l -b')             | `vdir` (list directory contents verbosely)           |
| watch      | Execute/display a program periodically                      | `watch -n 1 command` (periodically execute and display the output of a command)|
| wc         | Print byte, word, and line counts                            | `wc -l filename` (count lines in a file)             |
| whereis    | Report all known instances of a command                      | `whereis command` (locate binary, source, and manual page for a command)|
| which      | Locate a program file in the user's path                    | `which command` (display the path of a command)      |
| who        | Print all usernames currently logged in                     | `who` (display currently logged-in users)            |
| whoami     | Print the current user id and name (`id -un')               | `whoami` (display current user's id and name)        |
| xargs      | Execute utility, passing constructed argument list(s)      | `find /path -type f -name "*.txt" | xargs grep "pattern"` (search for a pattern in multiple files)| 
| yes        | Print a string until interrupted                             | `yes "Y"` (endlessly print "Y")                      |
