# What is Git?
![linus](images/linus.jpg)  
Git is a version control system (VCS) programmed by Linus Torvald in 2005 to support the work on the Linux kernel.


## Git Setup
First we need to add our Github credentials to git.
- Open git-bash
- Type:  
`git config --global user.name`  
`git config --global user.email`
- Should both be empty
- Set those values with:  
`git config --global user.name "Hans Wurst"`  
`git config --global user.email "mail@mail.com"`

## Get an Existing Repository

## Create Your Own Repo
### 1. Create a repository on github.com  
You will see following message:  
```
…or create a new repository on the command line
echo "# git_introduction" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/maxehrhardt/git_introduction.git
git push -u origin master
                
…or push an existing repository from the command line
git remote add origin https://github.com/maxehrhardt/git_introduction.git
git push -u origin master
```
### 2. Create Your Local Code
- Create a folder with your favorite name 
- Right-Click -> Git Bash


# Resources

# Command Library

| Command | Options | Explanation
| --- | --- | --- |
|  |  |  |
| `ls` |  | Shows content of current folder |
| `cd` |  <ul style="list-style-type:none;"><li>..</li><li>[filepath]</li></ul> | <ul style="list-style-type:none;"><li>Goes one folder up</li><li>Changes to the given file path</li></ul>  |
| `git init` |  | This command initializes a new git repo in the current  folder |
| `git add` | <ul style="list-style-type:none;"><li>.</li><li>[filepath]</li></ul> |<ul style="list-style-type:none;"><li>Adds all changes to commit</li><li>Only adds the changes of given file to commit</li></ul> |