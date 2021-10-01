## Shell Scripting
A shell script is a computer program designed to be run by the Unix shell, a command-line interpreter. The various dialects of shell scripts are considered to be scripting languages. Typical operations performed by shell scripts include file manipulation, program execution, and printing text.

#### A shell script is a computer program designed to be run by the Unix/Linux shell which could be one of the following:

1. The Bourne Shell
2. The C Shell
3. The Korn Shell
4. The GNU Bourne-Again Shell
----------------------------------
Some examples of shell scripts: 
---------------------------------
#!/bin/sh

# Author : Zara Ali
# Copyright (c) Tutorialspoint.com
# Script follows here:

echo "What is your name?"
read PERSON
echo "Hello, $PERSON"

-----------------------------------
Output:
-----------------------------------
$./test.sh
What is your name?
Amit Raj
Hello, Amit Raj


### Shell Types
In Unix, there are two major types of shells −

Bourne shell − If you are using a Bourne-type shell, the $ character is the default prompt.

C shell − If you are using a C-type shell, the % character is the default prompt.

The Bourne Shell has the following subcategories −

Bourne shell (sh)
Korn shell (ksh)
Bourne Again shell (bash)
POSIX shell (sh)
The different C-type shells follow −

C shell (csh)
TENEX/TOPS C shell (tcsh)

### Shell comments:
#!/bin/bash

# Author : Amit Raj
# Copyright (c) Tutorialspoint.com
# Script follows here:
pwd
ls
