Solution :
you have to add you ssh key in your git-hub profile. Follow steps to solve this problem

1. Right Click Folder you want to push in git
2. Select git-bash here problem
3. Write command ssh-keygen by this command your key is generated
4. Copy the key from cmd or go to (C:/User/your_user/.ssh/)
5. open id.rsa with notepad.
6. Copy your key
7. Now go to your git-hub profile
8. Go to settings
9. select **SSH and Gpg keys** 
10. select **New ssh key** option
11. add **window-key** in the title 
12. Paste your key in the description part below title field
13. Save

Now you are ready to push your folder

1. Now go to folder you want to upload
2. right click on the folder
3. Select git bash here 
4. git init
5. git add README.md
6. git commit -m "first commit"
7. git remote add origin https://github.com/<UserName>/<repo.git>
8. git push -u origin master

Hope this will be Helpful for you