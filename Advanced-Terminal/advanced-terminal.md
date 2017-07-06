# Terminal Advanced

## Skills

- [x] Can start and stop services with brew services, in the terminal
	- to stop a service 
	```
	brew services stop *NAME OF SERVICE*
	```
	- to start service
	```
	brew services start *NAME OF SERVICE*
	```
- [x] Can add a custom bin directory to their Shell config, in the terminal
	- first add a directory
	```bash
	mkdir tacobell
	```
	- then add this directory to the `$PATH`
	```bash
	export PATH=/Users/thi/bin:$PATH
	```
	- and then source this location
	```bash
	source ~/.tacobell
	```
- [x] Can use | (pipe) in the terminal
	- The pipe will take the output from one side and put it into the input of the other
- [x] Can use > (redirect) in the terminal
	- the redirection is used to redirect the output of a command into another location before the command executes
- [x] Can use `ctrl-z` in the terminal
 - `ctrl-z` will suspended a process and to get back just enter fg, fore-ground.
- [x] Can use `ctrl-r` in the terminal
 - `ctrl-r` will search the previous commands in the bash history
- [x] Can use the `tail` terminal command
	- `tail` will output the last portion of the file (10 lines by default)
- [x] Can use the `grep` terminal command
	- searches files for specific text
- [x] Can use the `wc` terminal command
	- will print out 3 groupings of numbers designating the bytes, word and line count.
- [x] Can use the `du` terminal command
	- this is used to find out the disk usage of a file or directory and each subdirectory
- [x] Can use the `man` terminal command
	- display help pages
- [x] Can use the `file` terminal command
 - `file` will give info on a file or directory and with a file it will print out the first portion of the line
- [x] Can use the `ps` terminal command
	- process status will give information on the processes currently being run on the memory
- [x] Can use the `kill` terminal command
	- end a command by specifying it's PID
- [x] Can use the `chmod` terminal command
	- change access permissions
- [x] Can use the `pbcopy` terminal command
	- will take the output of a command and save it to the clipboard
- [x] Can use the `pbpaste` terminal command
	- will output the contents of the clipboard
- [x] Can write an executable bash script
	- make a file with `!#/bin/bash` in the top line followed by a command. Use `chmod +x` to allow the file to be executable.
- [x] Can and modify your shell's `$PATH`, in the terminal
	-```bash
	export PATH=$PATH:/my/custom/path
	```
- [x] Can redirect `STDOUT` to a file, in the terminal
	- ```bash
	STDOUT &> file.txt
	```
- [ ] Can use UNIX command flags and arguments
	-
- [x] Can describe UNIX file permissions
	- There are three groups Owner Permissions, Group Permissions, and World Permissions. (r) read (w) write (x) execute
- [x] Can get a file's permissions, in the terminal
	- `ls -l`
- [x] Can set a file's permissions, in the terminal
	- `chmod +x`


## Suggested Search Terms

```
unix bash pipes
unix bash redirects
unix bash stdout
unix bash modify path
bash keyboard shortcuts mac
unix du
unix grep
os x pbcopy
```

## Suggested Resources

- http://www.catb.org/esr/writings/taoup/html/ch10s05.html


## Exercises

- [Adding A Custom bin Directory](./exercises/Adding-A-Custom-bin-Directory/README.md)
- [Manage Postgresql with brew services](./exercises/Manage-Postgresql-with-brew-services/README.md)
- [Guide to Pipes and Redirects](http://ryanstutorials.net/linuxtutorial/piping.php)