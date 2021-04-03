# HOLBERTON HEX #
## SHELL ##

### 0x00-shell_basics ###
* 0-bring_me_home:  script that changes the working directory to the user’s home directory.
* 1-listfiles: Display current directory contents in a long format.
* 2-listmorefiles: Display current directory contents, including hidden files (starting with .). Use the long format.
* 3-back: script that changes the working directory to the previous one.
* 4-lists: script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
* 5-copy_html: script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

### 0x01. Shell, permissions ###
* 0-execute: script that adds execute permission to the owner of the file `hello`.
* 1-multiple_permissions: script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.
* 2-everybody: script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.
* 3-James_Bond: script that sets the permission to the file `hello` as follows:
owner: no permission at all;
group: no permission at all;
other users: all the permissions.

### Requirements ###
* Allowed editors: `vi`, `vim`, `emacs`
* All your scripts will be tested on Ubuntu 14.04 LTS
* All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
* All your files should end with a new line
* The first line of all your files should be exactly `#!/bin/bash`
* A `README.md` file at the root of the `holberton-system_engineering-devops` repo, containing a description of the repository
* A `README.md` file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use backticks, `&&`, `||` or `;`
* All your scripts must be executable. To make your file executable, use the `chmod` command: `chmod u+x file`. Later, we’ll learn more about how to utilize this command
