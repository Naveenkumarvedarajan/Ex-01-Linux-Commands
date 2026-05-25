# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

<img width="933" height="188" alt="image" src="https://github.com/user-attachments/assets/434c6b5e-2194-4c43-a977-f1818741e6d4" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="930" height="69" alt="image" src="https://github.com/user-attachments/assets/8ededb71-f150-47a6-9fd5-4110bde48f69" />
 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="844" height="64" alt="image" src="https://github.com/user-attachments/assets/0734155a-a4e0-4104-84c9-25ea01a81987" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="604" height="42" alt="image" src="https://github.com/user-attachments/assets/39af3b55-56bb-4689-b79f-6f9be9fbc37c" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="521" height="45" alt="image" src="https://github.com/user-attachments/assets/fd7a85a1-1bee-4d0f-bd76-13b2bf64153b" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="644" height="81" alt="image" src="https://github.com/user-attachments/assets/e846bb93-87f4-4b8f-8e93-689d186ea923" />
 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="617" height="50" alt="image" src="https://github.com/user-attachments/assets/afcbca96-b5a3-47bb-9131-061b7eca984d" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="406" height="25" alt="image" src="https://github.com/user-attachments/assets/11050f9e-1f70-4ff5-ad56-565d92732c53" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="543" height="69" alt="image" src="https://github.com/user-attachments/assets/b747ab2b-8ad0-4257-8c3f-a5cd421b0f59" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="620" height="22" alt="image" src="https://github.com/user-attachments/assets/8b1863f4-3bae-4c0c-8662-8699535b072b" />
 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="773" height="192" alt="image" src="https://github.com/user-attachments/assets/ca1cd4fd-cd36-4a9e-8fe3-46271e44a6e6" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="535" height="220" alt="image" src="https://github.com/user-attachments/assets/1a3365e0-ad27-496c-97ed-e89964866d13" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="537" height="222" alt="image" src="https://github.com/user-attachments/assets/c0e31bad-7b1d-4256-8772-ad28598eb0fa" />
 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="820" height="84" alt="image" src="https://github.com/user-attachments/assets/e9ba39e4-d69a-4796-9a33-5e132d866ef5" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="642" height="44" alt="image" src="https://github.com/user-attachments/assets/60f0b844-ca07-4184-9110-e33b9f61b8bc" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="730" height="148" alt="image" src="https://github.com/user-attachments/assets/0ccd1d12-2837-4f7c-a685-72560a5aaecb" />

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

<img width="914" height="217" alt="image" src="https://github.com/user-attachments/assets/bb53bcea-d2d9-4248-ad02-58d993780485" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="651" height="71" alt="image" src="https://github.com/user-attachments/assets/ad3ad23e-4e13-46a8-a45a-c140e82ed549" />

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="936" height="195" alt="image" src="https://github.com/user-attachments/assets/ad2ab1f5-b558-4546-a75d-16810a14dc19" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="772" height="52" alt="image" src="https://github.com/user-attachments/assets/ae6cfc3b-4f9a-48ec-87f7-fd3b0f6a5de8" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="935" height="247" alt="image" src="https://github.com/user-attachments/assets/6d408349-5190-40ad-ae33-5fac50aa0887" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="659" height="178" alt="image" src="https://github.com/user-attachments/assets/4456c989-b398-46c6-8a0e-de30e395e93c" />
 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="585" height="238" alt="image" src="https://github.com/user-attachments/assets/e3bcfc14-6d20-4a2b-9898-ede8dd3debbb" />

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="914" height="249" alt="image" src="https://github.com/user-attachments/assets/3ead056e-774b-4e10-ab3a-6535641bcb7f" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="889" height="90" alt="image" src="https://github.com/user-attachments/assets/1aae49e7-3062-477e-bd68-9558a37da427" />
 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="936" height="299" alt="image" src="https://github.com/user-attachments/assets/f4b04621-4e60-468f-82e2-e17ffe869f2b" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
