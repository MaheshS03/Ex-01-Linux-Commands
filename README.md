# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

## Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/541b6bbe-6ffd-4843-97dc-2f1dc144e1d6)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

 ![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/58bfc44b-b8d3-4b5a-b5ef-4f92fba0e768)

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/2f56a632-228c-49da-b382-037753958da1)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/7e469056-e0ca-4864-8b77-8f0bb4965508)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/a44552c6-bc9a-4c52-a8db-cae40584c26c)

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 ![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/30ce2422-09d4-45f1-83ad-dd37d6e71839)

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/7b4117ee-ca4f-4f39-80cb-0e71eb24652a)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/741e5ec6-4496-4ae1-a226-48fddf86bd50)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/5fd1a3c4-0340-4952-b9d4-09f9746d3f5b)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 ![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/99013c38-7c6c-460d-a7c4-80950651c115)

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/e2f0c859-eb80-4a40-9c90-a63cc18d2f13)

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/f4a0131c-1002-4384-9188-f57ec430483f)

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

 ![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/6ba4dea7-4ff9-4356-abb5-6e36e9550d0d)

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/372ca16a-7410-4974-af33-d8bc3624be35)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/b1fa10ca-4b7e-4b47-952f-391af3ae4226)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/46381a63-8dfd-4d67-b16e-a697e848425c)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/0dea36f2-3964-4323-bf74-f8044606e0ce)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/24f46ed7-0f0d-4508-a257-cdcc05d99e3d)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/b62b374d-8669-47fc-a48b-67005194a7d7)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/bec029da-1bd8-40ee-82f0-b3f793576111)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/6dd8163e-1da3-4217-84ba-cb45b45b15a0)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/d4a37963-e946-462e-aa8e-e1e5fdc19868)
 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/86d84493-9cce-4f99-b120-cef383c659c9)

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/d337579a-9df9-4c70-9fb3-23d4a60311ee)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/1a874c18-6c02-4ab6-9516-beda1c814bf0)
 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/MaheshS03/Ex-01-Linux-Commands/assets/128498431/a4d210b2-cdea-4f2a-99a6-700b5bdecd47)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
