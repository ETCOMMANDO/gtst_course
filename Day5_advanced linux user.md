> some advanced user commands

+ To change password
   + sudo passwd username 
+ To change user id 
   + sudo user  -u newid username 
+ To change user on terminal 
   + su-username 
+ To remove user
   + sudo userdel -r username 

>sudoers file
+ IS a linux and unix administration use to allocate  system
+ changer ownership 
    + chown user:group file name 
+ permission 
    + r - stand for read = 4
    + w - stand for write = 2
    + X - stand for execute = 1

> chmode command
+ This command used to change file permissions 

 + syntax ( chmode<parameter>filename)
 + The parameter can be numberic or symobized

 >package install on linux
 + we will use debian pakage manager. on debian pakage manager called" apt " or "dpkg"
 + The repository http.kali.org
 
 >Advanced package tool / apt 
+  apt is  a free-software user interface thatwork with an online server to handle installation
+ The old "apt" used as " apt-get"
     + sudo apt update 
     + sudo apt upgrade
     + sudo apt search <software name >
     + sudo apt install<software name >
     + sudo apt remove <software name >
     + sudo apt purge  <software name >
> package dependencies
+ a software can built based on another program" modules"
+ Those package managers install the software + dependencies

>Dpkg / debian package manager
+ Dpkg is an offline package managing program 
  + syntax 
       + sudo dpkg -i <package name > = install
       + sudo dpkg -r <package name > = remove
       + sudo dpkg -p <package name > = update
       