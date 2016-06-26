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
ssh -i oowbr-private.key opc@p1.renecloud.io
```
