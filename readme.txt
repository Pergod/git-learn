now let start to learn git!
perpare:
	mkdir (directoryName)
	cd (directoryName)
	pwd
	ls -ah
First class:
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