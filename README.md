# Tehreem-Fatima-Git-Linux-Commands
# Linux Commands
# 1. PWD command
PWD command is used to find the current working directory path in the linux. All of the directories in the path are separated by a "/". The very first "/" represents the the parent or root directory and the last name in the path represents the name of current directory.
The specific syntax for this command is pwd[flag]
The flag options are -L and -P.

# 2. CAT Command
Cat command or concatenation is used to read data from a file in linux and then it gives the content of the file as output.
Command -> $cat filename and then it gives the output. To display the file content with line number following command is used. $cat -n filename

# 3. mv Command
The mv command in Linux is used to move files or directories from one location to another. It can also be used to rename a file or directory.
The basic syntax for the mv command is:

mv [OPTION]... SOURCE DESTINATION

Where:

SOURCE is the path to the file or directory that you want to move.

DESTINATION is the path to the new location where you want to move the file or directory.

# 4. mkdir Command
The mkdir command in Linux is used to create a new directory.

The basic syntax for the mkdir command is:

mkdir [OPTION]... DIRECTORY...

Where:

DIRECTORY is the name of the directory you want to create. You can specify multiple directories by listing their names, separated by spaces.

Some common options for the mkdir command include:

-m or --mode: Specify the permissions for the new directory using a numeric mode.

-p or --parents: Create parent directories if they do not exist.

-v or --verbose: Print a message for each directory that is created.

# 5. locate Command
The locate command in Linux is used to search for files and directories on a system. It uses a database of files created by the updatedb command to quickly find the files you're looking for.

The basic syntax for the locate command is:

locate [OPTION]... PATTERN...

Where:

PATTERN is a string that you're searching for. This can be a file name, directory name, or any other part of the file path.

Note: The locate command may not show recently created or modified files until the updatedb command has been run to update the database.

# 6. df Command
The df command in Linux is used to display information about the disk space usage on a system. It shows the amount of available space and the amount of used space on all mounted file systems.

The basic syntax for the df command is:

df [OPTION]... [FILE]...

Where:

FILE is an optional argument that specifies the file system for which you want to display information. If no file system is specified, information will be displayed for all mounted file systems.

# 7. du Command
The du command in Linux is used to estimate the space used by a file or directory and all of its contents. The du command provides a summary of the space used by each file and directory in the specified location, and the total space used by all files and directories combined.

The basic syntax for the du command is:

du [OPTION]... [FILE]...

# 8. head Command
The head command in Linux is used to display the first few lines of a text file. It is commonly used to view the contents of a file or to extract the first part of a file for processing.

The basic syntax for the head command is:

head [OPTION]... [FILE]...
# 9. tail Command
The tail command in Linux is used to display the last few lines of a text file. It is commonly used to view the contents of a file or to extract the last part of a file for processing.

The basic syntax for the tail command is:

tail [OPTION]... [FILE]...

Where:

FILE is an optional argument that specifies the file for which you want to display the contents.

# 10. grep Command
The grep command in Linux is used to search for text patterns within one or more files. The grep command is a powerful tool for finding specific lines of text within a large set of files.

The basic syntax for the grep command is:

grep [OPTIONS] PATTERN [FILE]...
