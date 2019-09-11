# ReadMe.md

This is my git cheat sheet.



## git commands

```bash
git init REPO-NAME
```

git init REPO-Name 
- Creates a respository called REPO-Name

```BASH
git status
```

- shows the stauts of the git repositaory


```Bash
git show
```
 
- shows the commit history and changes

```bash
git add FILENAME
```

- add the file filename and ANOTHERFILENAME to the stash 

```bash 
git commit -m "MESSAGE"
```
 
- commmits the stashewd files to the repo, and adds the the message that describe what has done

```Bash 
git log
```

- show the history of the commits made to this point in time

```Bash
git log --all --decorate --oneline --graph
```

- displays a 'graph' of the commits, one commits per line

```Bash
git config --global alias.adog "log --all --decorate --oneline --graph
```

- creates a git alias for the log all decorate online graph command.
- use this alias by entering `git adog`(much shorter)

```Bash
git remote add origin https://github.com/km0904/git-cheatsheet.git
```

- 

33 Other git things

**.gitignore** is a file that tells git files/folders that are not to be part of the repository (that is - ignored when added/commiting)

# comprehensive .gitignore found at:
# https://github.com/github/gitignore/blob/master/python
