# Shell Scripting Interview Questions

1. What is Linux?
It is a family of open-source Unix operating systems based on the Linux kernel. 

2. Difference between Linux and Unix?
Linux is a clone of Unix. Linux default shell is BASH (Bourne Again Shell) while the Unix shell is Bourne Shell.

3. What is a kernel?
The kernel is a computer program at the core of a computer’s operating system that manages operations of computer and hardware. 

4. What is an interpreter?
Interpreter translates the program line by line into machine code.

5. What is a compiler ?
Compiler scans the whole program and converts it into machine code.

6. What is a shell?
Shell is a program and command line interpreter. It is an interface between user and kernel.

7. What is CLI and GUI?
CLI is a command line interface. This user interface enables the user to give commands to interact with the device.

GUI is a graphical user interface. This user interface enables users to interact with devices with the help of graphical icons and visual indicators.

8. Why would we use CLI over GUI?
CLI gives better control to the user. 
CLI is a best  option for professionals who work on more programming languages.
It  required less memory as compared to GUI. 
The speed of the CLI is faster than GUI.
9. What is shell scripting?
It is a text file which contains list or series of command or statements to be executed

10. What is the default login shell? How to change it?
/bin/bash is the default login shell. Using the command  “chsh” we can change the default shell.

11. What is the importance of shell scripting?
If you need to perform the same task repeatedly, you should use shell scripting 
By using shell scripting, you can make your own tools 
It is very useful for a system admin to automate daily tasks
12. What are the various stages of the Linux process?
Waiting: The process waits for resources
Running: The process is currently being  executed
Stop: The linux process stop after execution
Zombie: The process has stopped but it is still active in process table
13. What is the main difference between BASH and DOS?
BASH commands are case sensitive but DOS commands are not case sensitive.

14. What are the components of  Linux ?
Kernels, shells, GUI, system utilities and application programs  are components of Linux.

15. What is a root user?
It is an admin user that allows you full control of your system.

16. What are the environmental variables?
Environmental variable control shell function as well as other Linux programs.

17. What is LILO?
LILO is a boot loader used in Linux .It is used to load the operating system into main memory to start its operation.

18. What are the different types of commonly used shells on a Linux system?
Bash/Bourne Again Shell: This is the most common shell available on all Linux and based systems. It is open source and freeware.
CSH or C Shell: This Shell scripting program uses the C programming’s shell syntax and it’s almost similar to C.
KSH or Korn Shell: Korn is a Unix based Shell scripting program, initially based on the Bash Shell Scripting. This shell is quite advanced and it’s a high level programming language.
TCSH: There is no specific full form of TCSH. It is as it is. TCSH is an advanced version of Berkeley Unix C shell. It again supports C style syntax.
19. Which command is used to execute a shell file?
First Set execute permission on your script using chmod command
chmod +x script-name-here.sh

To run your script:
./script-name-here.sh
Another option to execute shell script:
sh script-name-here.sh

20. Name of Editors which are available in almost all UNIX?
vi/vim 

21. What is interactive and non-interactive shell?
/bin/bash and /bin/sh is interactive shell 

/sbin/nologin shell is non-interactive shell

22. What is the absolute and relative path?
Absolute path is the full path of the directory. It always starts with “/” .

eg.  cd  /var/tmp/abrt/

Relative path is necessary from current location to reach particular directory doesn’t start with “/”.

eg. cd .. ,   cd –

23. How to create, read and delete files?
touch command is used for creating files.  eg. #touch filename 

cat command is used for reading files.     eg.  #cat filename

rm command is used  for delete a file    eg. #rm –f  filename 

24. How to create and delete a directory ?
mkdir command is used for creating a directory.  Eg.  # mkdir filename

rmdir command is used for remove directory  eg.   #rmdir filename 

25. How to create multiple text files and directories?
To  create multiple text file touch file name {} command is used 

 eg. suppose we want create 4 files then we type #touch filename{1..4}

To create multiple directory mkdir filename {} command is used

eg. suppose we want to create 4 directory  then we type mkdir filename {1..4}

26. What is the use of head and tell command?
Head command is used for display started 10 lines

Tail command is used for display started 10 lines

27. How to find the current shell which you are using?
$echo $SHELL command is used for find current shell

28. How to find an available shell in your system?
Cat /etc/shells command is used to find available shells in your system.

29. How to create shortcuts in Linux?
To create shortcut “link” command use. There are two types of link: hard link and soft link.

30. Tell me the difference between hard link and soft link?
Deleting the original file does not affect the hard link but Deleting the original file makes the soft link inactive.

31. How will you pass and access arguments to a script in Linux?
For pass arguments in script “scriptname arg1 arg2 arg3 …” 

For access arguments in script can be accessed inside the script as “$1 , $2 .. $n”

32. What is the significance of $#?
It represents the total number of arguments passed by string.

33. What is the difference between $* and $@?
$* consider the entire set of positional parameters as a single string but  $@ treat each quoted argument as a separate argument.

34. Explain “s” permission bit in a file? 
“s” bit also called “set user id”(SUID) bit. “s” on file causes the process to have the privileges of the owner of the file during the instance of the program.

35. What are the different types of variables used in Shell Script?
System defined variable : system defined variable created by os itself. These variables are generally defined in capital letters. It can be viewed by the “set” command.

User defined variable : it created by system users. Value of variable can be view by using “echo $variablename” command.

36. What is the difference between = and ==?
=  use for assign value to variable

== use for string comparison

37. What is the use of a pipe operator? How to execute multiple commands in one line?
The pipe operator is used for one by one execution of command but commands should not be dependent on each other.

38. What are the different modes of vi editors?
Command mode : this is a mode where you start

Edit mode : this mode allows you to do next editing.

Ex mode : In this mode you interact with vi with instruction to process

39. What is redirection?
Redirection is the process of direction data from one output to another.

40. How to find the status of the process?
Ps ux command user for find status of process.

41. How to check memory status?
Free command is useful for checking memory status.

42. How to debug a shell script?
To debug a shell script we execute the script with the “-x” or “-nv”  option.

43. Which command is used for comparing the string in the shell script?
To compare the string “test” command is used.

44. What is the difference between $! And $$?
$! Shows process id of the process that recently went into background 

$$  gives the process id of the currently executing process

45. Which command is used to find all information of the user?
“finger” command shows all information of users.

46. Which four fundamental components of every file system?
Boot block: it contains a small program called MBR which loads the kernel during system boot up.

Super block: super block contains all information about the file system.

Inode block: it contains inode for every file of the file system.

47. What is the Crontab?
Crontab stands for cron table because it uses the job scheduler cron to execute tasks. The crontab is a list of commands that you want to run on a regular schedule, and also the name of the command used to manage that list. 

48. How many fields are present in a crontab file?
The five fields contain information on when to execute the command .

minute(0-59)
hour(0-23)
day(1-31) 
month(1-12)
day of the week(0-6, Sunday = 0).
49. What are the two files of crontab command?
cron.allow which decides the users need to be permitted for using the crontab command.

cron.deny which decides the users need to be prevented from using the crontab command

50. What are the different commands available to check the disk usage?
df: It is used to check the free disk space.
du: It is used to check the directory wise disk usage.
dfspace: It is used to check the free disk space in terms of MB.
