# A tutorial 
    ---- about how to login in specific account on `ieng6`

## Installing VS code

    You can install VS code strated by clicking on this link: 
   [ToInstall](https://code.visualstudio.com/download)
    (The website should look like this: 
   
   ![this](https://user-images.githubusercontent.com/103154918/162254994-652e192d-4505-4136-984a-ada96a65577a.png)

    Then, you can choose which one to download based on your own computer system

## Romotely connecting
    use the command `ssh cs15lsp22xxx@ieng6.ucsd.edu` (replacing "xxx" with your account name) on the terminal on your local computer
    
    example here:
![example](https://user-images.githubusercontent.com/103154918/162554678-5366a0d3-bf75-4e86-9114-0dd4c3201614.png)
    then enter your password

## Trying some commands
   1.`ls`command: list files and directories in your current directory (you can use `ls -a` to show hidden files) 
   2.`cd`command: change current directory to a new directory 
   3.`pwd`command: get the path for your current directory 
   4.`mv`command: move or rename files or directories from one place to another
   5.`cp`commqnd: copy files or directories to a specific place
   6.`touch`command: can be used to create a new file
   7.`cat`command: print out the content in a file
   8.`mkdir`command: make a new directory 
   9.`rm` command: remove a file (you can use `rm -rf` to recursively remove files in a directory)
  
   combined example here:
![](https://user-images.githubusercontent.com/103154918/162555203-eaaf1cf4-e0fa-4d64-bfa5-3fa3dda512e0.png)

 
## Moving Files with scp
    scp is used for uploading or downloading files to/from server
    `scp cs15lsp22xxx@ieng6.ucsd.edu:SourcePath DestinationPath`(for downloading)
    `scp cs15lsp22xxx@ieng6.ucsd.edu:DestinationPath SourcePath`(for uploading)
    (you can use `scp -r` to recursively upload or download all files in a directory)
    
    example for downloading from server here:
![](https://user-images.githubusercontent.com/103154918/162555354-7643483b-075f-497c-829e-811916f4321c.png)


## Setting an SSH key
    use `ssh-keygen` command to generate your rsa key, it also shows the path where the key is stored, use `cat [directory]` to see the key.
    you can copy the key and use it for fruther use, for example connecting to github. 
    
    example here:
![](https://user-images.githubusercontent.com/103154918/162555937-eccb6a12-36e8-41e7-9db4-cc942f01be67.jpg)

    

## Optimizing Remote running
    If you only have several commands to run, you don't have to login in the sever. Instead, you can use `ssh cs15lsp22xxx@ieng6.ucsd.edu "command"`to quickly run the command in one line without logging in the sever.
    example 1 here:
![](https://user-images.githubusercontent.com/103154918/163899903-9cbfda82-0ec2-4d1c-8543-3cc68138b19e.png)
    example 2 here:
![](https://user-images.githubusercontent.com/103154918/163899947-e2d6deb7-0705-49e0-b9ad-e1bd8796da2e.png)
    


    
