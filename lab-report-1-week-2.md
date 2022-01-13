# **How to log into ieng6(Windows)**
## **1)Installing Visual Studio Code**
---
In order to install this, first go to the page [download link for vsc](https://code.visualstudio.com/download).
This is what the page should look like: ![Image](./Images/installvsc.PNG)  
Next, click the download button for your OS, i clicked windows.  
## **2) Remotely Connecting**
---
Try to find your username on [link](https://sdacs.ucsd.edu/~icc/index.php). Mine happens to be cs15lwi22agw. Then open vsc, and click terminal>new terminal.
![Image](./Images/newterm.PNG)

* If you are on windows, download [OpenSSh](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse).  
* If it asks if you want to continue connecting, then type yes.  
* To ssh use this command: 
> `ssh <your username>@ieng6.ucsd.edu`. 
* For example: I would type 
> `ssh cs15lwi22agw@ieng6.ucsd.edu`.
* Click enter. It will prompt you for your password, which you should type in, and click enter when you are done.  
  
This is what it should look like:
![Image](./Images/ssh.PNG)  
  
  If you did it correctly, it should change the information before your cursor and display: 
  ![Image](./Images/ssh1.PNG)

## **3)Trying Some Commands**
---

![Image](./Images/trycmds.PNG)
* Here I tried the commands ls, ls -a, cd WhereAmI.java, and cat.
* I tried to change directories to a file(you can only change directories to a folder), which didn't work. 
## **4)Moving Files with scp**
---
To move files, use the command 
>`scp <filename> <destination> `  

For example: 
>`scp WhereAmI.java cs15lwi22agw@ieng6.ucsd.edu:~/`  

This will move a file called WhereAmI.java from the client computer to the home directory of the server computer.  


## **5)Setting an SSH Key**
---
## **6)Optimizing Remote Running**
---