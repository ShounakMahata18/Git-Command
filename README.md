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