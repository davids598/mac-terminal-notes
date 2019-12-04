# mac-terminal-notes
A list of things that I have learned about the MacOS terminal that I have found to be useful, including keyboard shortcuts and useful commands.
### Core Commands
| Command | Description |
|---------|-------------|
|cd [folder] | Change Directory - Change the directory that you are currently in e.g. `cd Desktop`|
|cd | Changes your directory to your Home directory, usually set to your user account |
| cd ~ | Takes you back to your home directory |
| cd - | Takes you back to your previous directory |
| cd / | Takes you to the root of the drive you are currently in |
| pwd | Print Working Diectory - prints the path to the directory you are currently in |
| ls | Lists the files in the current directory |
| ls -l | Long version, shows permissions, owner of files, file size and last modified date |
| ls -a | Displays all files in the current directory including hidden files |
| ls -t | Displays all files in the current directory sorted by last edited time |
| ls -R | Displays all files (if in a folder, shows entire content of folder recursively) |
| open [file] | Opens a file |
| VI [file] | Opens a file with the VI text editor |
| VIM [file] | Opens a file with the VIM text editor |
| nano [file] | Opens a file with the nano editor |
| sudo | SuperUser DO - Runs a command with the priviliges of the superuser e.g. `sudo install gem cocoapods`|
| top | Displays active processes and ressource usage (Press Q to quit) |
| clear | Clears the terminal screen |

### File/Directory Commands
|Command | Description |
|--------|-------------|
| cat | Concatenate to screen (display a file or something on screen) |
| touch [file] [file2] | Create a file with the given name (Can create multiple files at once) |
| touch -a [file] | Changes the access time of the file to the current time |
| touch -m [file] | Chamges the modification time to the current time |
| touch -am [file] | Combines the last two commands |
| touch -r [file1] [file2] | -r = reference, use times for file1 for file 2 |
| touch -B [file] | Modifies timestamps by going Back X number of seconds, e.g. `touch -r file1 -B 30 file2` makes file2 30 seconds older than file1|
| touch -d [date] [file] | Changes the last access time of a file to a specific time, e.g. `touch -d 1 November 2019 10:22 [file]` |
