##Add origin
```git
git remote add origin https://github.com/tannana86/product-bundle.git
git branch --set-upstream-to origin/dev
```

##Configuration
```git
git config --global user.name "Selim F."
git config --global user.email "sfraoua@gmail.com"
//ignore chmod
git config --global core.filemode false
```
##Conf example
```
[core]
	repositoryformatversion = 0
	filemode = true
	bare = false
	logallrefupdates = true
[remote "origin"]
	url = https://github.com/tannana86/rockmongo.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
	remote = origin
	merge = refs/heads/master
```
##Error : cannot do a partial commit during a merge
```git
git commit -i myfile.php
```

##Remove cached
==================
```git
git rm -r --cached .
```

##Delete origin branch
==================
```git
git push origin --delete branch-name
```