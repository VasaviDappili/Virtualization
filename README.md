 # Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
# NAME: DAPPILI VASAVI
# REGISTER NUMBER:212223040030
# Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
To install and configure Oracle VM VirtualBox.

# Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
# Steps:
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

# Result:
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

# snapshots:
AWS Account Creation Snapshot
# Snapshot 1: Installing Oracle VirtualBox image

<img width="927" height="497" alt="image" src="https://github.com/user-attachments/assets/3f15ccc8-4eb8-4dd5-8f32-3618a31bc84f" />

# Snapshot 1: Installing Oracle VirtualBox image

<img width="935" height="573" alt="image" src="https://github.com/user-attachments/assets/2766003c-351d-44d8-8e82-9548b0f517a7" />

# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali
# About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.

# commands:

# 1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

<img width="855" height="68" alt="image" src="https://github.com/user-attachments/assets/19e82581-b5ff-4c9e-9aef-08040f1ef600" />

# 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="250" height="67" alt="image" src="https://github.com/user-attachments/assets/c1a7ff05-6790-4e5d-bfe5-0ca0d9fd3faf" />

# 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="930" height="116" alt="image" src="https://github.com/user-attachments/assets/39945a16-6967-44bb-b3f8-94c7526336df" />

# 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="888" height="127" alt="image" src="https://github.com/user-attachments/assets/68ed081b-547b-4a9f-9c6a-8f33218ea7a0" />

# 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

<img width="354" height="158" alt="image" src="https://github.com/user-attachments/assets/d5d33186-2d02-4e5f-a0fb-207290f8ec34" />

# 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE].

<img width="350" height="183" alt="image" src="https://github.com/user-attachments/assets/a4616cce-a75e-4790-8053-9edc2ccf0cda" />

# 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

<img width="334" height="133" alt="image" src="https://github.com/user-attachments/assets/0f63c457-fc62-47d1-bcf4-a08398c36309" />

# 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="501" height="40" alt="image" src="https://github.com/user-attachments/assets/187cd93f-2fbd-4b88-b540-1e4c4dbef920" />

# 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="296" height="88" alt="image" src="https://github.com/user-attachments/assets/70be3104-3233-428d-93d4-315c1feae1f5" />


cs9
# 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

<img width="363" height="265" alt="image" src="https://github.com/user-attachments/assets/44f8c94e-e942-41d2-afd4-906cdfa92a79" />


cs10
# 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="394" height="528" alt="image" src="https://github.com/user-attachments/assets/67d057cf-fd68-48d8-9817-0dcb5a655350" />


cs11
# 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

<img width="462" height="171" alt="image" src="https://github.com/user-attachments/assets/dfd36ebb-1dbf-49fa-a1d2-edc697c0bdf7" />


cs12
# 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="299" height="238" alt="image" src="https://github.com/user-attachments/assets/cbfa4ca7-dc65-494c-bd45-e3a561b76aea" />


cs13
# 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="931" height="48" alt="image" src="https://github.com/user-attachments/assets/942b7ce8-2752-42e9-8392-de912e71677e" />


cs14
# 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

<img width="349" height="74" alt="image" src="https://github.com/user-attachments/assets/066c827d-4ad0-4360-ae4e-164b226fa560" />


cs15
# 16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="465" height="299" alt="image" src="https://github.com/user-attachments/assets/e7fb27a3-2f7f-4f78-88a8-e897e5fc91bb" />


cs16
# 17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

<img width="450" height="118" alt="image" src="https://github.com/user-attachments/assets/4f616d99-24c1-4c47-8cad-8025899fe1bd" />


cs17
# 18) tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

<img width="369" height="159" alt="image" src="https://github.com/user-attachments/assets/a89a211c-bec1-4829-8a39-e5c9a8f3a570" />


cs18
# 19) chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="472" height="132" alt="image" src="https://github.com/user-attachments/assets/b0e2d411-7cd9-4038-b6df-1ff1969cc545" />


cs19
# 20) make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]…'

<img width="233" height="67" alt="image" src="https://github.com/user-attachments/assets/fbd44807-c423-4772-afa5-86fc099c06c0" />


cs20
# 21) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="861" height="104" alt="image" src="https://github.com/user-attachments/assets/5996c208-2c1d-429f-a444-d2128e91d396" />


cs21
# 22) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder

<img width="493" height="118" alt="image" src="https://github.com/user-attachments/assets/8644b437-445f-4fd8-8e19-3c52d08716f1" />


cs22
# 23) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

<img width="605" height="101" alt="image" src="https://github.com/user-attachments/assets/bc8d85ba-4a30-45c9-8e17-4656583de484" />


cs23
# 24) gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..

<img width="926" height="148" alt="image" src="https://github.com/user-attachments/assets/932fd5cd-2720-4ae6-a56c-f21cd81bbefe" />


cs24
# 25) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

<img width="246" height="303" alt="image" src="https://github.com/user-attachments/assets/228e55aa-043d-4420-9099-d76eddeedd7d" />


cs25
# 26) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="515" height="294" alt="image" src="https://github.com/user-attachments/assets/d8d53084-c74a-4736-aed8-ccb171ee3a6a" />


image
# 27) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="1920" height="1165" alt="image" src="https://github.com/user-attachments/assets/cff6d22b-f3cd-419f-98b9-6242cd207274" />

<img width="1920" height="1165" alt="image" src="https://github.com/user-attachments/assets/7c220ab3-f10a-456a-8891-6021d3527a45" />


image image
# 28) mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"

<img width="743" height="67" alt="image" src="https://github.com/user-attachments/assets/9ed151d2-3db6-43a7-a21d-6856016c8751" />


cs28
# 29) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="930" height="298" alt="image" src="https://github.com/user-attachments/assets/43f1bd45-9939-423b-bb0a-6acce32828db" />


cs29
# 30) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="293" height="85" alt="image" src="https://github.com/user-attachments/assets/833e53b4-0ab7-4e3c-96f6-469465f85185" /> <img width="351" height="75" alt="image" src="https://github.com/user-attachments/assets/25280736-1916-47c6-af88-4e37fd5e48c3" />



cs30a cs30b


# Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.




