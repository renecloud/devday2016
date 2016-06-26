#Laboratory 1. Setup Environment
Pre-requisities: You only need SSH Access to Internet, The instructor provide of file with a private SSH Key.
Copy file called **oowbr-private.key** on your local directory.

## Accessing to Your Enviroment
**On Windows:** You need to use some SSH Client like PuttySSH [download PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)

You can check how to configure private key on PuTTY [here](https://support.suso.com/supki/SSH_Tutorial_for_Windows)

In this screen you have to configure an private key:

![Screen to add private key](files/Putty-config-sshauth.png)

So you put an HOST that instructor given to you.

![Screen to open session to server](files/Putty-configuration.png)

**On Linux or Mac:** You need to use command line terminal typing "terminal" in search panel.

```
# ssh -i oowbr-private.key opc@p1.renecloud.io
```
## Checking tools
Check that linux kernel is 4.1.x 
```
# uname -a
Linux oowbr4 4.1.12-37.5.1.el6uek.x86_64 #2 SMP Thu Jun 9 15:56:37 PDT 2016 x86_64 x86_64 x86_64 GNU/Linux
```
Check docker installation
```
# sudo docker --version
Docker version 1.10.3, build 57bf6fd

# sudo docker run hello-world
...
Hello from Docker.
```
## Setting Up Admin Server
List all images on our local repository
```
# sudo docker images
REPOSITORY           TAG                 IMAGE ID            CREATED             SIZE
hello-world          latest              693bce725149        2 weeks ago         967 B
renecloud/weblogic   latest              8ad042d7793e        5 months ago        1.383 GB
```
List all our containers that are running
```
# sudo docker ps
CONTAINER ID    IMAGE       COMMAND         CREATED         STATUS          PORTS             NAMES
```
In fact there aren't instances yet

Run container as Weblogic Administrator
```





