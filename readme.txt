now let start to learn git!
perpare:
	mkdir (directoryName)
	cd (directoryName)
	pwd
	ls -ah
First class:
	git config --global user.name "Your Name"
	git config --global user.email "email@example.com"
	git init
	git add (fileName)
	git commit -m "some message"
Second class ：
	git status
	git diff
Third class：
	git log [--pretty=oneline]
	git reflog
	git reset --hard head^
	cat (fileName)
Fourth class：
	before add:
	git checkout -- (fileName)
	after add:
	git reset HEAD (fileName)
	git checkout -- (fileName)
Fifth class:
	rm test.txt
	delete:
	git rm --> git commit
	back:
	git checkout -- (fileName)
Sixth class:
	ssh-keygen -t rsa -C "youremail@example.com"
Seventh class:
	git remote add origin git@github.com:(githubName)/(repositoryName).git
	git push -u origin master
Eighth class:
	git branch
	git branch (branchName)
	git checkout (branchName)
	git checkout -b (branchName)== git branch (branchName)+git checkout(branchName)
	git merge (branchName)
	git branch -d (branchName)
Nineth class:
	git merge --no-ff
Tenth class:
	git stash
	git stash apply
	git stash pop
	git stash drop
	git stash list