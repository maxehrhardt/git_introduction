# What is Git?
![linus](images/linus.jpg)  
Git is a version control system (VCS) programmed by Linus Torvald in 2005 to support the work on the Linux kernel.


# How to start?
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
### 2. Create 



# Resources

# Command Library

| Command | Options | Explanation
| --- | --- | --- |
| `git init` | - | This command initializes a new git repo in the current  folder |
| `git add` | <ul style="list-style-type:none;"><li>.</li><li>[filepath]</li></ul> |<ul style="list-style-type:none;"><li>Adds all changes to commit</li><li>Only adds the changes of given file to commit</li></ul> |