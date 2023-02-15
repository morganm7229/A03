To use git, you must cd into a directory that you would like to clone. Once you are in that category, go to the github repository you would like to work on, and do git clone [https link copied from repository].
That will allow you to copy the repository into your filesystem, and you can work on it from there. When you are ready to push files to github, do git add [file], then git add -m "commit message", and then git push origin master (or if in another branch, use that instead of master).
To switch branches, you can do git branch [branch name]. Git branch -b [branch name] you will make a new branch.

To use webstorm, click on New Project, pick where you want the project to be, and then in the project tab you can left click, and create a new file. To save a file, do ctrl + s.

To use github, go to the top right, hit the +, and then hit new repository, give it a name and description, and then you can start managing your code from there. For pull requests, you can go to the repository page, and then you'd see a button pop up above the code notifying you there's been a new push from git, and you can make a pull request, use the dropdown lists after clicking the button to determine which branch gets pulled into which, and then hit merge and the code has been successfully merged.

**Branch** - a variation of the codebase, usually fixated on a specific feature.

**Clone** - copy/pasting an entire repository into your file system.

**Commit** - staging your code that is tracked by github to be pushed to github.

**Fetch** - retrieves commits, files, branches, and tags from a remote repository.

**GIT** - the tool used for managing your code in the console

**Github** - the site where your code is stored

**Merge** - Pulling one branch into another, making them one branch, with the changes from one affecting and going into the other

**Merge conflict** - when a file that exists in each branch being merged is changed in a way that does not merge cleanly (usually changing the same things/lines in each file)

**Push** - sending your code to github, for the branch you specify in the command

**Pull** - takes the code from the source specified and updates your code with the changes made on github

**Remote** - git repository that is hosted on the internet or another network

**Repository** - A specific project on git, where all of the code for that project is

References - 

https://phoenixnap.com/kb/git-fetch 
 
https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts 

https://www.gitkraken.com/learn/git/tutorials/what-is-git-remote 
