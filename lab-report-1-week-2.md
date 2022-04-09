# Lab Report 1

This is a tutorial showing how to log into a course specific account on ieng6.

## Step 1: Installing Visual Studio Code (VS Code) 

First, I went to the [VS Code](https://code.visualstudio.com) website and downloaded the version that correlated to my computer (i.e Windows, MacOS, Linux).

Once it was installed, I opened VS Code and my window looked like this:

![Image](LabReport1Step1.png)


VS Code might look different because it has various color schemes, styles, and themes.


## Step 2: Remotely Connecting

After I successfully downloaded VS Code, in order to connect remotely, since I am a Windows user, I downloaded [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse) and followed the instructions on the linked attached.  

Once OpenSSH was successfully downloaded, I went back to VS Code and I opened a new terminal, which I did by going to the toolbar in VS Code and pressing terminal, then pressing new terminal (Refer to the picture below).

![Image](LabReport1Step2pt1.png)

After I opened the new terminal, I typed in the following command: 

$ ssh cse15lsp22agx@ieng6.ucsd.edu

and then I logged in successfully my first time, it did not show me my password (which I was confused with at first), once I figured that out, it showed me my last login, my ip address, and I got a message that tells me I’m logged in and then my cluster status.

![Image](lab1pt4.png)

Note the "agx" part from above is unique to each student, so I went to the link 

[Account Lookup Tool](https://sdacs.ucsd.edu/~icc/index.php)  and l looked up my username.





