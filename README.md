#basic-commands-for-rhel

[Kiosk@foundation~]$
    kiosk - username
    foundation -  hostname
    ~ - user home directory and working location
    $ - local user

su - root = for switching user to root
cat /etc/redhat-release = to see the version of redhat
uname -r = to check the kernel version
lscpu = to see system spec
free -m = to see RAM spcae
lsblk = list the harddisk blocks
df -h = parted mount
whoami = to see the username
pwd = present working directory
ls = contents available in working directory
ls -a = to see hidden files ( *** if it starts with [.] then it is a hidden directory[blue] or file[black] *** )
ls -l = to list file and directories in a long listing format
ls -i = to see inode number
ls -la = detail format of hidden files
ls -lh <filename> = particular file permission
ls -ld <directoryname> = particular directory permissions
mkdir <name> = to create directory
mkdir <name> <name1> <name2> = to create multiple directories using 1 command
mkdir -p <name>/<name1>/<name2> = to create multiple hierarchial directory ( *** name is parent and rest are child *** )
mkdir .<name> = to create hidden directory
cd <name> = to enter to a directory
cd .. = to comeback to previous location
cd = to go back to working user home directory
nautilus <foldername> = to open directory graphically
touch <filename> = to create a file
cp <file1> <directory1> = to copy file1 to directory1
mv <source> <destination> = to move file
mv <oldname> <newname> = to rename file or directory
rmdir <name> = to remove directory
rm -rvf <name> = force remove directory or file which is not empty
ctrl+c = return to normal form
  
( *** DONOT USE "<" ">" while executing the commands, those are for refernces *** )


#SHORTCUT-KEYS

alt+f2 [gnome-terminal] = to open terminal
ctrl+shift+n = to open another terminal
windows+tab = switching different terminals
ctrl+shift+t = to open sub terminal
ctrl+page up/down = switching between sub terminals
ctrl+d = close sub-terminals
ctrl+shift+(+) = to increase font size
ctrl+(-) = to decrease font size
ctrl+l = to clear the page
vim / cat / gedit = to access files any of the 3 methods can be used with the filename

