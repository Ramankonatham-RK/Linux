# Linux Commands
## Basic

ls - List files and directories

Displays the contents of a directory.

Example:
```
ls
```
Lists the files in the current directory.

```
ls /home
```
Lists files in the /home directory.


ls -l - Long Listing ( Shows more details )
```
ls -l
```

ls -a - List the hidden files.

```
ls -a
```
cd - Change Directory

Used to change the current directory.

Examples:

```
cd /home/user
```
Moves one directory up.
```
cd ..
```

pwd - Print Working Directory

Displays the path of the current working directory.

Example:
```
pwd
```
mkdir - Make Directory

Creates a new directory.

Example:
```
mkdir new_folder
```
rm -f - Remove Directory

Deletes directory.

Example:
```
rmd -f folder
```

rm - Remove Files or Directories

Deletes files or directories. Use with caution.

Example:
```
rm file.txt
```

Deletes a file named file.txt.

```
rm -r folder
```
Deletes a directory and its contents recursively.

cp - Copy Files and DirectoriesCopies files or directories.

Example:

```
cp file1.txt file2.txt
```
Copies file1.txt to file2.txt.

```
cp -r folder1/ folder2/
```
Copies folder1 and all its contents to folder2.


mv - Move or Rename Files/Directories

Moves or renames files and directories.

Example:

```
mv file1.txt /home/user/backup/
```
Moves file1.txt to the backup folder.


```
mv oldname.txt newname.txt
```
Renames oldname.txt to newname.txt.

cat - Display File Content

Displays the content of a file.

Example:
```
cat file.txt
```
Displays the content of file.txt.

echo - Display a Line of Text
Outputs text to the terminal or a file.

Example:
```
echo "Hello, world!"
```

Prints "Hello, world!" to the terminal.

```
echo "Hello" > file.txt
```
Writes "Hello" to file.txt.


man - Manual Pages

Displays the manual for a command.

Example:

```
man ls
```
Shows the manual page for the ls command.

touch - Create an Empty File

Creates an empty file or updates the timestamp of an existing file.

Example:

```
touch newfile.txt
```

chmod - Change File Permissions

Modifies the permissions of files or directories.

Example:

```
chmod 755 script.sh
```
Sets the permissions to rwxr-xr-x for script.sh.

chown - Change File Owner/Group

Changes the owner or group of a file.

Example:

```
chown user:group file.txt
```
Changes the owner to user and group to group for file.txt.

ps - Show Running Processes

Displays active processes.

Example:

```
ps
```
Lists processes for the current user.

```
ps aux
```
Lists all processes running on the system.

kill - Terminate a Process

Terminates a process by its ID.

Example:

```
kill 1234
```
Kills the process with ID 1234.

df - Disk Space Usage

Shows the disk space usage of the file system.

Example:
```
df -h
```
Displays disk space usage in human-readable format (e.g., GB, MB).

top - Display System Resource Usage

Shows real-time system processes and resource usage.

Example:
```
top
```
grep - Search for Text in Files

Searches for patterns in files.

Example:
```
grep "text" file.txt
```
Searches for the word "text" in file.txt.

wget - Download Files from the Web

Downloads files from the internet.

Example:
```
wget http://example.com/file.txt
```
tar - Archive and Extract Files

Used to create and extract compressed archives.

Example (Create):

```
tar -cvf archive.tar folder/
```
Creates a tar archive of folder.

Example (Extract):
```
tar -xvf archive.tar
```
Extracts the contents of archive.tar.

sudo - Execute a Command as Another User (Usually Root)

Executes commands with superuser privileges.

Example:
```
sudo apt update
```
Runs apt update with root privileges.

history - Show Command History

Displays the history of commands entered.

Example:
```
history
```
nano / vim - Text Editors

Used to edit files from the command line.

Example:
```
nano file.txt
```
Opens file.txt in the nano text editor.
```
vim file.txt
```
Opens file.txt in the vim text editor.

shutdown - Shutdown or Restart the System

Shuts down or restarts the system.

Example (Shutdown):
```
sudo shutdown now
```

Shuts down the system immediately.

Example (Restart):
```
sudo reboot
```
Restarts the system.


