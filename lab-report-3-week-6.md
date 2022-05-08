# Lab Report 3
This lab report will be implementing all of the Group Choices from [Lab 5](https://docs.google.com/document/d/1NQ17hecUPFKeoFyrEvK9DBlCS1JkDbMW6Ygrf_CJJJU/edit).

## Streamlineing ssh Configuration
First a config file was created in the .ssh directory. The picture below shows the config file in the .ssh directory. 

![image](labReport3Images\LabReport3Configls.png)

To edit this config file, vim was used, which is an editor that allows one to edit a file in the terminal. To use vim you run ```vim <file>``` in the command line, make sure you are in the same folder the file is in. Then press "i" on the keyboard. 

![image](labReport3Images\LabReport3UsingVim.png)

This enables one to edit the file. Once the edit is made press the escape button and type in ```:wq``` which saves the edits and exits vim.In the config file, a host is made, which can be anything. This will be typed in instead of the User name seen in the image above. The HostName is the remote server that will be logged into. The image below shows the contents of the config file after the edit was made:

![image](labReport3Images\LabReport3ConfigCat.png)

Once this is saved, rather than typing

```ssh cs15lsp22xxx@ieng6.ucsd.edu```

in the command line to log into the remote server, you only need to type in 

```ssh <Host in config file>```

The image above shows logging into the remote server:

![image](labReport3Images\LabReport3pt1.png)

This makes logging in much faster and efficient!

## Setup GitHub Access from ieng6
The second part of this lab shows the setup for Github Access from ieng6. In order to do this, the public key from the remote computer must be added as a key on GitHub. In order to get the public key, do the following:

```
>>> ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/jolme/.ssh/id_rsa): /Users/jolme/.ssh/id_rsa_github

```

Once this is done, it should show the key, copy it, and go to GitHub, go to your profile, and go ssh keys, it is on the left side and paste the key in their. This is how my key looks in github

![image](labReport3Images\LabReport3sshOnGitHub.png)

To show the key stored in the user account, I went to .ssh and typed ```ls``` into the command line. Here is a screenshot:

![image](labReport3Images\LabReport3keylocation.png)







