# Git-Command
This contains all the codes use for git.

<Configure Git>
~ Root Directory

=> git config --global user.name "ShounakMahata18"
=> git config --global user.email "shounakmahata18@gmail.com"
=> git config --list                                                                           [To show all the changes]

<VS Code terminal Cmd>

=> git clone <link>                                                                            [To clone a link in VS Code]
=> git status  
    1)Untracked         [Create a new file that git does not know before]
    2)Modified          [Change or modify previous tracked file]
    3)Unmodified        [Unchanged or mot modified]
    4)Staged            [file is ready to be commited]
=> git add <file name> or git add <.>                                                           [To add or at the staged area]
=> git commit -m "massage"                                                                      [To commit the record]

=> git push origin main                                                                        [push the commit to my github account]

<Create folder in Vs Vode and push it into GitHub acc>

=> git init                             [To Create a new folder into git repo]
=> git remote add origin <link>         [From the newly created repo]
=> git remote -v                        [To check the current remoote]
=> git branch                           [To check branch]
=> git branch -M main                   [to change the master to main branch]
=> git push origin main         git push -u origin main [-u for is for the default push operation on origin main 1st] => git push[2nd]

<Git Branches>

=> git checkout -b feature1             [To create a new branch]
=> git checkout <branch name>           [To change a branch]
=> git branch -d <branch name>          [To delete neighbour branch]
=> git diff <branch name>               [To Find the difference between current and <branch name> branch]
=> git pull origin main                 [To fetch and download content from remote repo to local repo to match the content]
=> git merge main                       [To merge two branches]

<Undo Changes>

1) For add or staged area
=> git reset <file name>  or git reset  [Undo all the git add . files]
2) Reset after a single commit
=> git reset HEAD ~ 1
3) Undo multiple commit
=> git log                              [All commit and their hashes]
=> git reset <Hash>                     [Undo only in git not in vs code]
=> git reset --hard <Hash>              [Undo in both git and vs code]