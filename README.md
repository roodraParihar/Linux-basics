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
**moving the files**
mv source_file destination



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

