Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
NAME: VINUTHAA NN
REG NUMBER: 212224040362
Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

3.a) Installation and Configuration of Oracle VirtualBox
Aim:
To install and configure Oracle VM VirtualBox.

Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
Steps:
1.Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
2.Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
3.Configure VirtualBox:

Open VirtualBox.

Click New → Name VM → Select Type (Linux/Windows) and Version.

Allocate:

Minimum 2 GB RAM

Create Virtual Hard Disk (20 GB recommended).

Start Virtual Machine and provide ISO to install OS.

Result:
Thus, Oracle VM VirtualBox was installed successfully.

3.b) Installation and Configuration of Kali Linux
Aim:
To install and configure Kali Linux in Oracle VirtualBox.

Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
Steps:
1.Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
2.Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
Allocate Memory:
Minimum 2 GB RAM (recommended 4 GB).
4.Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
6.Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
7.Login to Kali Linux:

Use root credentials.
8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox image
Screenshot 2025-08-28 103507
Snapshot 2: Kali Running in Virtual image
Screenshot 2025-08-28 103519
Result:
Thus, Kali Linux guest OS was installed and configured successfully.

3.c) Execution of Linux Commands in Kali
About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
Commands:
1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

cs1
2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

cs2
3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

cs3
4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

cs4
5) cd Command
The cd command is used to change the current directory.

Syntax: cd

cs5
6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

cs6
7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

cs7
8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

cs8
9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

cs9
10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

cs10
11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

cs11
12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

cs12
13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

cs13
14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

cs14
15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

cs15
16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

cs16
17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

cs17
18) tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

cs18
19) chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name

cs19
20) make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

cs20
21) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

cs21
22) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder

cs22
23) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

cs23
24) gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..

cs24
25) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

cs25
26) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

image
27) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

image image
28) mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"

cs28
29) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

cs29
30) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

cs30a cs30b
Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
