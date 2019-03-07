Last login: Tue Mar  5 21:10:07 on ttys000
Brandons-MacBook-Pro:~ brandongoldenberg$ git remote
fatal: not a git repository (or any of the parent directories): .git
Brandons-MacBook-Pro:~ brandongoldenberg$ git remote add origin https://github.com/goldenb12/my-first-repo.git
fatal: not a git repository (or any of the parent directories): .git
Brandons-MacBook-Pro:~ brandongoldenberg$ clear

















Brandons-MacBook-Pro:~ brandongoldenberg$ echo "# my-first-repo" >> README.md
Brandons-MacBook-Pro:~ brandongoldenberg$ git init
Initialized empty Git repository in /Users/brandongoldenberg/.git/
Brandons-MacBook-Pro:~ brandongoldenberg$ git add README.md
Brandons-MacBook-Pro:~ brandongoldenberg$ git commit -m "first commit"
[master (root-commit) bd90321] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
Brandons-MacBook-Pro:~ brandongoldenberg$ git remote add origin https://github.com/goldenb12/my-first-repo.git
Brandons-MacBook-Pro:~ brandongoldenberg$ git push -u origin master
Username for 'https://github.com': git remote
Password for 'https://git remote@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/goldenb12/my-first-repo.git/'
Brandons-MacBook-Pro:~ brandongoldenberg$ git remote
origin
Brandons-MacBook-Pro:~ brandongoldenberg$ git push -u origin master
Username for 'https://github.com': goldenb12
Password for 'https://goldenb12@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/goldenb12/my-first-repo.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
Brandons-MacBook-Pro:~ brandongoldenberg$ rm readme.txt
Brandons-MacBook-Pro:~ brandongoldenberg$ nano

  GNU nano 2.0.6                New Buffer                            Modified  

1. This is
2. an ordered
3. list

Here is `some code` in the middle of a sentence.

```
This is
a block
of code
```

Here is how you make [a link](https://www.wikipedia.org/).

![This is an image.](https://github.com/yihui/xaringan/releases/download/v0.0.2$





^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Page ^K Cut Text  ^C Cur Pos
^X Exit      ^J Justify   ^W Where Is  ^V Next Page ^U UnCut Text^T To Spell
