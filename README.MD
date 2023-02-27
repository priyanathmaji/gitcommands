#Initializes git in the current directory
C:\Users\u407598\gitcommands>git init
Initialized empty Git repository in C:/Users/u407598/gitcommands/.git/

#Stage Changes using add command
#adds the file README.MD to the staging area
C:\Users\u407598\gitcommands>git add README.MD

#Creates a new commit with the message "first commit" and saves the changes in the staging area
C:\Users\u407598\gitcommands>git commit -m "first commit"
[master (root-commit) d8eb225] first commit
 1 file changed, 4 insertions(+)
 create mode 100644 README.MD

#renames the current branch to main
C:\Users\u407598\gitcommands>git branch -M main

#adds a new remote repo named origin with the URL 
C:\Users\u407598\gitcommands>git remote add origin https://github.com/priyanathmaji/gitcommands.git

#pushes the main branch to the origin remote repository and sets it as the upstream branch
C:\Users\u407598\gitcommands>git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/priyanathmaji/gitcommands.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.



############################################
C:\Users\u407598\gitcommands>git add README.MD

C:\Users\u407598\gitcommands>git add version.txt

C:\Users\u407598\gitcommands>git commit -m "added version.txt" 

C:\Users\u407598\gitcommands>git push

############################################

If you create the branch directly in git, you need to clone again, delete the .git folder and start again
C:\Users\u407598>git clone https://github.com/priyanathmaji/gitcommands.git





