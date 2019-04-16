# bash-git-tools
Some aliasses and functions that can be included in the bash profile, for a higher productivity when working with git.

# how to use
- Clone this project somewhere you like
- Add a reference to your bash profile
- restart your terminal
````
$ cd [somefolder]
$ git clone https://github.com/jfvh/bash-git-tools.git
$ echo source ~/[PATH]/bash-git-tool/.bp_git_tool  >> ~/.bash_profile
````
# checking out branches
You can switch branches easily by 
````
$ gcheck
````
# merge branches 
You can merge branches easily with
````
$ gmerge
````
# commiting with branch name (GitCommitStory)
assumed that your branchname is feature/TICKET-0000 you can commit with your message prefixed by
````
gcs "the actual message"
````
Then the command executed will be `git commit -m "TICKET-0000 the actual message"`

## TODO
- list the branches by last used


