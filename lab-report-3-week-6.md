# Lab Report 3

### Streamlining ssh Configuration
![Image](images/lab3-ssh.png)
![Image](images/lab3-config.png)
<br>
My public key is stored within my .ssh file and config file. I added the config file to automatically enter in my user name when I log in with ieng6.
<br>
I was then able to add a file with scp using my alias
<br>
![Image](images/lab3-scp.png)


### Set up Github access from ieng6
![Image](images/lab-remotekey.png)
<br>
I created a public key in a remote account and stored it in github. The private key is stored in the ieng6 .ssh folder in id_rsa. 
<br>
![Image](images/lab3-remotessh.png)
<br>
I was then able to commit and push from remote access.
<br>
![Image](images/lab3-push.png)

### Copy from whole directories using scp -r
I was able to copy markdown-parse with scp -r
![Image](images/lab3-scp.png)
![Image](images/lab3-scp2.png)
<br>
After copying over the markdown-parser directory to my remote account, I then ran junit tests.
<br>
![Image](images/lab3-test.png)
<br>
To make things faster, I ran scp for markdown-parser and the tests in one line
<br>
![Image](images/lab3-line.png)
![Image](images/lab3-line2.png)
