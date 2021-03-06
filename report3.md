# Lab Report 3
## ssh configure
Configure ~/.ssh/config to ssh to server easily
![](/report3-image/ssh_config.png)
So that we do not need to type the whole address while connecting, we can simply use the alias we set
![](/report3-image/ssh_connect.png)
scp also no longer require the whole address
![](/report3-image/scp_alias.png)

## GitHub access from ieng6
Public key was generated by `ssh-keygen` command and stored in `~/.ssh/rsa_id.pub` 
![](/report3-image/ssh-key.png)

Also setup in my GitHub account

![](/report3-image/public_key.png)

Private key is stored in `~/.ssh/id_rsa`
![](/report3-image/private_key.png)

Now we can commit change through ieng6
![](/report3-image/commit_git.png)

[link to commint](https://github.com/NuojinliXu/cse15l-lab-reports/blob/main/Haha)

## Copy with `scp -r`
We can copy a whole directory to ieng6 with `scp -r` command

![](/report3-image/scp-r.png)

Now we can run the test on ieng6

![](/report3-image/run-ieng6.png)

Or we can combine the whole process in one line of command

![](/report3-image/combined1.png)
![](/report3-image/combined2.png)