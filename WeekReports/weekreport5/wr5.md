---
Jerry Pachtinger
Fall 23
CIS106
---


**What are Command Options?**
Options modify or enhance the behavior of a command

**What are Command Arguments?**
command arguments are the items that a command works on

**Which command is used for creating directories? Provide at least 3 examples.**

mkdir

ex 1: create a directory in the current working directory
mkdir MyMusic

ex 2: create a folder in another directory using absolute path
mkdir ~/downloads/SNESroms

ex3: using an escape character to create a file name with a space in it
mkdir /MyMusic/BootyShakin\ music

**What does the touch command do? Provide at least 3 examples.**
The touch command creates files

ex 1: creating a file
touch myFile

ex 2: creating multiple files
touch coolFile.txt lameFile.js iamambivalenttowardsthisfile.md

ex 3: Creating a file using relative path and spaces int the name
touch Downloads/SNESroms/"bahamut lagoon"

**How do you remove a file? Provide an example.**
the command rm is used to remove files

rm iamambivalenttowardsthisfile.md

**How do you remove a directory and can you remove non-empty directories in Linux?** 
You can use rmdir or rm with the -r option (use with caution). Non-empty directories cannot be removed in Linux
Provide an example

rmdir Downloads/SNESroms

**Explain the mv and cp command. Provide at least 2 examples of each**
The mv command moves a file from one location to another and can rename it. The cp command makes a copy of the file leaving the original where it was

ex 1:moving a file to a new directory
mv Downloads/DKC2.sfc Downloads/SNESroms

ex 2: Renaming a file
mv MyGF.png SomebodyThatIUsedToKnow.png

ex 3: copying a file
cp Downloads/legallyacquiredROMimage.sfc Downloads/SNESroms

ex4: copying a directory
cp -r Downloads/SNESroms Downloads/Nothingtoseehere/justuschickens/nogamesinherebutifthereistheyrelegalbackups

