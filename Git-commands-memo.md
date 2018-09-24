



# Git commands memo.

| COMMAND                                         | DESCRIPTION                                             |
| :---------------------------------------------- | :------------------------------------------------------ |
|                                                 |                                                         |
| **Create**                                      |                                                         |
| git init                                        | Initialising git in a folder                            |
| git remote add origin [repository url]          | Adds link to remote repo                                |
| git clone                                       | Makes a complete copy of the repo locally               |
|                                                 |                                                         |
| **Delete**                                      |                                                         |      |                                                 |                                                         | 
| rm -rf .git                                     | Undo Initialising git in a folder                       |
| git rm -r --cached [folder/file-name]           | Delets folde/file from remote repository                |
| git add [file name]                             | Adds file to staging                                    |
| git add . / git add —all                        | Adds all the files to staging                           |
|                                                 |                                                         |
| git commit  -m “[message]”                      | Commits file with message                               |
| git  push -u origin master                      | First commit to a repo. -u allows to track changes      |
|                                                 |                                                         |
| **Braching**                                      |                                                         |   
| git branch -D [branch name]                     | Delete branch                                           |
| git log --all --decorate --oneline --graph      | Shows commit history graph                              |
| git merge [branch name]                         | merges branch into main                                 |
| git checkout [branch name]                      | Moving into a branch                                    |
|                                                 |                                                         |
| git alias                                       | Creates command shortcut                                |