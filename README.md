# Linux-basics
## Here's a simple representation of hierarchy:
## Linux (Kernel)
    ├── Debian (Distribution)
    │    ├── Ubuntu (Distribution based on Debian)
    │    └── Other Debian-based distributions
    ├── Fedora (Distribution)
    ├── Arch Linux (Distribution)
    ├── CentOS (Distribution)
    └── Other Linux distributions

## Shell vs Bash
**Shell:** A general term for any command-line interpreter used in Unix-like operating systems. There are many types of shells, each with its own unique features and syntax. <br>
**Bash:** A specific type of shell that is an enhanced version of the Bourne Shell, with advanced features for both interactive use and scripting. Bash is widely used as the default shell on many systems.

## Different types of shell and Bash (mainly used by people)
**1. Bash (Bourne Again Shell) :** Ideal for scripting, automation, and general command-line tasks. Its widespread use makes it a standard choice in many development environments. <br>
**2. Korn Shell (ksh) :** Widely used in enterprise environments for its scripting power and interactive features. <br>
**3. Bourne Shell (sh) :** Still widely used for scripting and as a fallback shell due to its simplicity and universal availability. <br>
**4. Fish (Friendly Interactive Shell) :** Ideal for developers looking for a straightforward, intuitive shell with powerful interactive features. Less suited for complex scripting due to its unique syntax. 


## Process Management


**Display information about running processes** <br>
ps aux

**Display a real-time view of running processes** <br>
top

## Disk Usage
**Display disk space usage** <br>
df -h

**Display directory space usage** <br>
du -sh directory_name


**Terminate a process by its PID** <br>
kill pid

**Terminate all processes by name** <br>
killall process_name

# Some more initiation commands
**moving the files** <br>
mv source_file destination

**Move a file to a directory:**
mv file.txt /path/to/directory/

Eg: mv file.txt /path/file.txt

**Copy the file and paste some other directory**
cp file.txt /path/file.txt

**moving to the root node**
cd /
because linux system follows the tree like structure


## Some important commands and their info
1. if there is no permission then to change in the root node then we can use "sudo" and if wanna act as root node then can use "sudo su" but this is not recommonded.
2. sudo apt update --> tell the what are software can be upgrade.
3. sudo apt upgrade --> command will install the new versions of software available as per latest.
4. ls -R --> will show directory content as well as inside directory what are the files it will also show it means it runs recursively.
5. touch .roodra --> here we can make hidden files (if we start with . extention) but ls command will not show the hidden files so use "ls -a" , it will show hidden files as well.
6. "history" --> command will show all the commands run by me.
7. echo --> command will print anything ahead of it. eg: echo roodra then it will print "roodra"
8. linux is case sensitive
9. with the help of apt we can install any software eg: sudo apt install apache2.
10. Linux permission ---> like who can read, write and execute the files or our directory. chmode calculator calculates the number and give permisiion access to the owner , group and public.
11. ps -a --> shows all the background process
12. ps as well work
13. kill --> kill command will stop the process ID (PID) like eg: kill 23214  (this is the PID) then it will shut kill that particular process.
14. using vim we can edit files --> sudo install vim
15. using vim command we can edit the text files within the terminal --> eg: vimm roodra.txt  -->hit enter will open file then click i then start writting for save  esc : --> then "wq" and if we do not want to save then q . wim will exit.
16. 



## File and Directory Operations

```sh
# List directory contents
ls

# Change the current directory
cd /path/to/directory

# Print the current working directory
pwd

# Create a new directory
mkdir new_directory

# Remove an empty directory
rmdir directory_name

# Remove files or directories
rm file_name
rm -r directory_name  # Remove a directory and its contents

# Copy files or directories
cp source_file destination_file
cp -r source_directory destination_directory

# Move or rename files or directories
mv old_name new_name
mv file_name /path/to/destination

# Create an empty file or update the timestamp of an existing file
touch new_file

# Concatenate and display the content of files
cat file_name

# View the content of a file one screen at a time
more file_name
less file_name

# Display the first few lines of a file
head file_name

# Display the last few lines of a file
tail file_name

