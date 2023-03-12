# test
	echo "new branch line" >> new.file  - add new row in file
	git - help
	copy NUL .gitconfig  - create config
	git config --global user.email "mtaran@ukr.net"
	git config --global user.name "MikeTaran"
	git config --list --global - check config
	C:\Users\User>cd /d F:\IT\Git - key \d change disk
	git clone https://github.com/MikeTaran/test.git  - clone repo
	Changes not staged for commit:
	(use "git add <file>..." to update what will be committed) - commit
	(use "git restore <file>..." to discard changes in working directory)
	git add . - add all files
	git commit -a -m "test commit 1" - commit local repo
	git push - update GitHub
  
	****Main commands****
	git fetch  - Show to as if file from GitHub was changed
	git pull  - update local repo
	git log -  log
	git log --author MikeTaran - log by author
	git show bc1d6c53649180b47fd147d604ecc21a59ac9021 - full commit info
	git show - last commit info
	git diff - info about changes into file
	ls - direcrory info
	git reset HEAD~1 - restore commit for 1 lvl
	git checkout - откат изменений
	git stash- 

	***** Branch ****
	git branch first_branch  -  creation new branch
	git branch - info about branch
	git checkout first_branch - Switched to branch 'first_branch
	git push -u origin first_branch - To push the current branch and set the remote as upstream
	git checkout - Switched to branch 'main'
	git merge first_branch - updating main branch
	git branch -m first_name second_name - git checkout second_name Switched to branch 'second_name'(w/o files)
	touch second.name - add file
	git push -u origin :second_name - deleted branch
	git branch -d second_branch  - Deleted branch second_branch from local.
	git fetch origin second_branch  - restore branch (+ git checkout second_branch)
	
		********Git GUI*****
	git gui&  - open GUI through Bash
	gitk& - open full graf statistic branch commits
	
<<<<<<< HEAD
	new line
	second line
	
=======
>>>>>>> 4f99736c8fd56d5b8054baad5314f6bd5880a802

