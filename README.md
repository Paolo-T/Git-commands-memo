


# Git commands memo.

| COMMAND                                         | DESCRIPTION                                             |
| :---------------------------------------------- | :------------------------------------------------------ |
|                                                 |                                                         |
| **Create**                                      |                                                         |
| git init                                        | Initialising git in a folder                            |
| git remote add origin [repository url]          | Adds link to remote repo                                |
| git clone                                       | Makes a complete copy of the repo locally               |
|                                                 |                                                         |
| **Delete**                                      |                                                         |
| rm -rf .git                                     | Undo Initialising git in a folder                       |
| git rm                                          | Delets folder/file                                      |
| git rm -r --cached [folder/file-name]           | Delets folder/file from remote repository               |
|                                                 |                                                         |
| **Fetch/merge** (checkout remote branch technique)|                                                         |
| git fetch origin                                | Downloads remote content without erasing local          |
| git checkout -b [remote_feature_branch]         | Creates a local branch for the fetched content          |
| git diff                                        | Lists diffences between remote and local repo           |
| git merge                                       | merges different branches                               |
|                                                 |                                                         |
| **Branching**                                   |                                                         |
| git branch -a                                   | Shows branches and fetched repos                        |
| git checkout -b [branch name]                   | Creates branch                                          |
| git branch -D [branch name]                     | Delete branch                                           |
| git log --all --decorate --oneline --graph      | Shows commit history graph                              |
| git merge [branch name]                         | merges branch into main                                 |
| git checkout [branch name]                      | Moving into a branch                                    |
|                                                 |                                                         |
| **Sending**                                     |                                                         |
| git add [file name]                             | Adds file to staging                                    |
| git add . / git add —all                        | Adds all the files to staging                           |
| git commit -m “[message]”                       | Commits file with message                               |
| git commit -am “[message]”                      | git add + git commit -m                                 |
| git  push -u origin master                      | First commit to a repo. -u allows to track changes      |
|                                                 |                                                         |
| **Useful**                                      |                                                         |
| git alias                                       | Creates command shortcut                                |
| git log                                         | Inspecting                                              |



git checkout -b

ref: https://www.atlassian.com/git/tutorials/syncing/git-fetch
