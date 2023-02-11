                            LESSON 4
Now open your repository in your code editor and create file e.g "index.html"
After that open your terminal in current repository

To check the changes use following command
                command
git status

Then press enter after that you will see
_____________________________________________________________________________
$ git status
On branch branch-name

No commits yet       

Untracked files:     
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track) 
_____________________________________________________________________________________
Then Use Command 
                    command
git add .

_______________________________________________________________________________________
Then Use Command 
                    command

git commit -m "First Comment"


This command is use to pass Comment 

You will see In terminal:
_________________________________
$ git commit -m  "First Comment"
[main (root-commit) 115cd91] First Comment
 1 file changed, 101 insertions(+)
 create mode 1006 index.html
 _________________________________

_______________________________________________________________________________________
Then Use Command to push Your file to GitHub Repository:
                Command

git push

You will see in terminal 
_________________________
$ git push
Enumerating objects: 1, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 1 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 380 bytes | 380.00 KiB/s, done.
Total 1 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
remote:   https[REPOSITORY-URL]
To        https[REPOSITORY-URL]
   3f0ef1c..73a4dc6  main -> main
_______________________________________________________________________________



Now goto your GitHub Accout there you will see file "index.js"
its mean now you can push your files in your repository.






