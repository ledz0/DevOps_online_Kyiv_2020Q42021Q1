## Steps of Task5.1 execution.

1) Log in to the system as root.
2) Use the passwd command to change the password.
**'/etc/shadow'** - password is changed and stored and encrypted view.
![1](./screenshots/1.png)
3) Using command 'cat /etc/passwd', show all users in the system and see next data:
username:password:user ID (UID):group ID (GIP):personal information:shell user
![1](./screenshots/2.png)
4) I used command chfn with option '-o' to change other information
![1](./screenshots/4.png)
5) Example info about command: I saw info about 'ls' and 'sudo'
![1](./screenshots/5.png)
![1](./screenshots/6.png)
6) View the contents of files .bash*
![1](./screenshots/7.png)
7) Command finger in action.
![1](./screenshots/8.png)
8) Command ls in action, show content in directory. 
![1](./screenshots/9.png)

## Steps of Task5.2 execution.

1) Example tree command, with other options
![1](./screenshots/10.png)
2) Using command "file" with the next option "-i" for show type file.
![1](./screenshots/11.png)
3) - For return to home catalog, next command:  
- **"cd"**</br>
- **"cd ~"**</br>
- **"cd /home/ledz0/""**
4) ![1](./screenshots/5.png)
Option -l give additional insight information about folder content :

- type of file
- permissions
- number of symbolic links on that file/folder
- owner
- owner group
- size
- time of creating
Option -a shows hidden files in the target folder which start on "."
5) All steps from instruction: 
![1](./screenshots/12.png)
6)  All steps from instruction: 
![1](./screenshots/13.png)
![1](./screenshots/14.png)
7) Command **locate -A traceroute squid** - shows nothing because there are no files with the name "squid". Only "traceroute"
![1](./screenshots/15.png)
8-9) Next screenshot info about system mount partition. 
![1](./screenshots/16.png)
10) No results for /etc/ directory. 
![1](./screenshots/17.png)
11) Using find and grep commands. 
![1](./screenshots/18.png)
12) Command for screen-by-screen print:
 - ls -al /etc | less
![1](./screenshots/19.png)
13) Show Audio, Video and USB devices 
![1](./screenshots/20.png)
14) + Types of files :
  - regular files (-)
  - sockets (s)
  - pipes (p)
  - symbolic devices (c)
  - block devices (b)
  - symbolic links (l)
  - directories (d)