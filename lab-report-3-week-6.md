# Lab Report 3
This lab report will be implementing all of the Group Choices from [Lab 5](https://docs.google.com/document/d/1NQ17hecUPFKeoFyrEvK9DBlCS1JkDbMW6Ygrf_CJJJU/edit).

## Streamlineing ssh Configuration
First a config file was created in the .ssh config file. The picture below shows the the files in the .ssh repository. 

![image](labReport3Images\LabReport3Configls.png)

To edit this config file, vim was used, which is an editor that allows one to edit a file in the terminal. To use vim you run ```vim <file>``` in the command line. Then press "i" on the keyboard. This enables one to edit the file. Once the edit is made press the escape button and type in ```:wq``` which saves the edits and exits vim. The screenshot below shows the editor in the terminal. 

![image](labReport3Images\LabReport3UsingVim.png)

As seen in the image above, A host is made, which can be anything. This will be typed in instead of the User name in seen in the image above. The HostName is the remote server that will be logged into. The image below shows the contents of the config file after the edit was made:

![image](labReport3Images\LabReport3ConfigCat.png)

Once this is saved, to log into the ieng6 server only the Host made in the config needs to be typed in, rather than cs15lsp22xxx@ieng6.ucsd.edu. The image above shows logging into the remote server:

![image](labReport3Images\LabReport3pt1.png)

This makes logging in much faster and efficient!

## Setup GitHub Access from ieng6




