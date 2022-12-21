> Linux file hierarchy 
+ Filesystem Hierarchy Standard (FHS) defines the directory structure and directory contents in Unix-like operating systems.

    1. /root - directoriesstart from room directory
    2. /temp - temporary files 
    3. /mnt - temporary mounted file
    4. /lib - bin & sbin commands stores
    5. /etc - system configiration files
    6. / bin - commands we use before stored here 
    7. / sbin(system binary)- they ask permition to run
    8. /home - home directory
    9. /boot - boot loader
    10. /media - mount point for removable media such as CD-ROMs
    11. /usr - contain binary ,library ,documentation & source code for second level programs
    12. /opt - contains add- on individual vendors .
    13. /dev - include terminal device , usb or any device attached to system



> Text editor
+ Text editor is used to process  text program . There are two type of text editor <br> 
    + command line  
        + vim
        + nano
        + neovim
        + emacs
    + graphical
       + pluma
       + gedit
       + vs code
       + sublime
1. vim - is a very powerful and it's hard to learn . vim have two modes
    + command mode - we can do command 
    + input mode - where we can write 
       + :w + enter - save
       + :q + enter - quit
       + :wq! + enter - force save and quit
       + :esc - get back to command mode
       + :%! - execute  command 

2. Nano - this text editor is user friendly , it's free and open source <br>
    + shortcuts    
       + ^ + s= save<br>
       + ^ + u= undo
       + ^ + e= Redo
       + ^ + x= exit
       + ^ + shift + c= copy
       + ^ + shift + x= cut
       + ^ + shift + v= paste
> Linux user managment
+ user have their own file & application. every user have group.Those user have power

+ in linux  there are 2 kinds of users.<br>
      1.Root id - 0<br>
      2. Normal user id - 1-999

# sudo - SUPER USER DO
> creating users

+ In linux there are two methods to creat user 
    + useradd - simple <br>
              - sh terminal<br>
              - sudo useradd username
    + adduser - detailed 
              -bash terminal
              - sudo adduser username 
### The user file stored inside /etc/password .
### The password are stored inside /etc/shadow .
### When you creat a user it creats a group with that name .
 + To access root user 
   + sudo su 
+ To leave root access
   + Type exit and enter