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
Brandons-MacBook-Pro:~ brandongoldenberg$ nano README.md
Brandons-MacBook-Pro:~ brandongoldenberg$ git add -A
git commit -m "added README.md"
git push
^C
Brandons-MacBook-Pro:~ brandongoldenberg$ git commit -m "added README.md"
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
	modified:   README.md

Untracked files:
	.CFUserTextEncoding
	.DS_Store
	.anaconda/
	.anyconnect
	.bash_history
	.bash_profile
	.bash_profile-anaconda3.bak
	.bash_sessions/
	.chimera/
	.cisco/
	.condarc
	.cups/
	.flexlmrc
	.gitconfig
	.idlerc/
	.lesshst
	.octave_hist
	.oracle_jre_usage/
	.pymol/
	.subversion/
	.vscode/
	Applications/
	Desktop/
	Documents/
	Downloads/
	Library/
	Movies/
	Music/
	Pictures/
	Public/
	PycharmProjects/
	ibt_application.log
	ibtsa.log
	journal-2019-02-25
	my-first-repo/
	my-fourth-repo/
	my-second-repo/
	oasys.log
	octave-workspace
	short
	states.txt
	summary.txt
	workbench

no changes added to commit
Brandons-MacBook-Pro:~ brandongoldenberg$ git push
Everything up-to-date
Brandons-MacBook-Pro:~ brandongoldenberg$ git checkout update-readme
error: pathspec 'update-readme' did not match any file(s) known to git.
Brandons-MacBook-Pro:~ brandongoldenberg$ ls
Applications		Pictures		my-second-repo
Code			Public			my-third-repo
Commands		PycharmProjects		oasys.log
Desktop			README.md		octave-workspace
Documents		ibt_application.log	short
Downloads		ibtsa.log		states.txt
Library			journal-2019-02-25	summary.txt
Movies			my-first-repo		workbench
Music			my-fourth-repo
Brandons-MacBook-Pro:~ brandongoldenberg$ git merge master
Already up to date.
Brandons-MacBook-Pro:~ brandongoldenberg$ rm *.txt
Brandons-MacBook-Pro:~ brandongoldenberg$ rm *.jpg
rm: *.jpg: No such file or directory
Brandons-MacBook-Pro:~ brandongoldenberg$ ls
Applications		Music			my-first-repo
Code			Pictures		my-fourth-repo
Commands		Public			my-second-repo
Desktop			PycharmProjects		my-third-repo
Documents		README.md		oasys.log
Downloads		ibt_application.log	octave-workspace
Library			ibtsa.log		short
Movies			journal-2019-02-25	workbench
Brandons-MacBook-Pro:~ brandongoldenberg$ nano README.md
Brandons-MacBook-Pro:~ brandongoldenberg$ git add -A
^C
Brandons-MacBook-Pro:~ brandongoldenberg$ git commit -m "made readme more personal"
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
	modified:   README.md

Untracked files:
	.CFUserTextEncoding
	.DS_Store
	.anaconda/
	.anyconnect
	.bash_history
	.bash_profile
	.bash_profile-anaconda3.bak
	.bash_sessions/
	.chimera/
	.cisco/
	.condarc
	.cups/
	.flexlmrc
	.gitconfig
	.idlerc/
	.lesshst
	.octave_hist
	.oracle_jre_usage/
	.pymol/
	.subversion/
	.vscode/
	Applications/
	Desktop/
	Documents/
	Downloads/
	Library/
	Movies/
	Music/
	Pictures/
	Public/
	PycharmProjects/
	ibt_application.log
	ibtsa.log
	journal-2019-02-25
	my-first-repo/
	my-fourth-repo/
	my-second-repo/
	oasys.log
	octave-workspace
	short
	workbench

no changes added to commit
Brandons-MacBook-Pro:~ brandongoldenberg$ git push origin update-readme
error: src refspec update-readme does not match any.
error: failed to push some refs to 'https://github.com/goldenb12/my-first-repo.git'
Brandons-MacBook-Pro:~ brandongoldenberg$ cd my-first-repo
Brandons-MacBook-Pro:my-first-repo brandongoldenberg$ git checkout master
A	file1.txt
A	file2.txt
M	readme.txt
Already on 'master'
Brandons-MacBook-Pro:my-first-repo brandongoldenberg$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master

Brandons-MacBook-Pro:my-first-repo brandongoldenberg$ nano README.md

  GNU nano 2.0.6              File: README.md                         Modified  

- *Night* by Elie Wiesel
- *Harry Potter and the Sorcerer's Stone* by J.K. Rowling
- *Game of Thrones* by George R.R. Martin

### Food

Last night I dreamt about eating in these restaurants:

1. Chef Chu's in Los Altos.
2. Khanh's Garden in San Jose.
3. Achilles in San Jose.









^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Page ^K Cut Text  ^C Cur Pos
^X Exit      ^J Justify   ^W Where Is  ^V Next Page ^U UnCut Text^T To Spell
