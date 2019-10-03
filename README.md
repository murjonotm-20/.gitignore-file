$ .gitignore password.txt
$ ls -a
. .. .git .gitignore password.txt readme.txt
$ echo "123456" >> password.txt
$ echo "password.txt" >> .gitignore
$ git status
On branch master

No commits yet

Changes to be committed
   (use "git rm --cached <file>.." to unstage)
   
             new file: readme.txt
         
Untracked files:
   (use "git add <file>..." to include in what will be committed)
   
             .gitignore
