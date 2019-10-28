| SL NO | Description                                                                                                                                  | Code                                                          |
|-------|----------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| 1     | The State Of A Repository                                                                                                                    | git status                                                    |
| 2     | Add file to staging area                                                                                                                     | git add filename                                              |
| 3     | Add file All to staging area                                                                                                                 | git add .                                                     |
| 4     | A diff is a formatted display of the differences between two sets of files.                                                                  | git diff filename                                             |
| 5     | To compare the state of your files with those in the staging area.                                                                           | git diff -r HEAD                                              |
| 6     | To save the changes in the staging area,                                                                                                     | git commit -m ‘message’                                       |
| 7     | accidentally mistype a commit message, you can change it using the --amend flag                                                              | git commit --amend - m "new message"                          |
| 8     | To view A Repository's History                                                                                                               | git log                                                       |
| 9     | To view A Specific File's History                                                                                                            | git log path                                                  |
| 10    | View A Specific Commit                                                                                                                       | git show 0da2f7                                               |
| 11    | Git's Equivalent Of A Relative Path                                                                                                          | HEAD~1                                                        |
| 12    | Who Changed What In A File                                                                                                                   | git annotate file                                             |
| 13    | What Changed Between Two Commits                                                                                                             | git diff HEAD~1..HEAD~3                                       |
| 14    |                                                                                                                                              | git diff ID1..ID2                                             |
| 14    | Git To Ignore Certain Files                                                                                                                  | create .gitignore file and mention files/path                 |
| 15    | Remove Unwanted Files git clean -n will show you a list of files that are in the repository, but whose history Git is not currently tracking | git clean -n                                                  |
| 16    | Change My Git Configuration The keys that identify your name and email address are user.name and user.email respectively                     | git config --global setting.name setting.value                |
|       |                                                                                                                                              | git config --global user.name "Sudhir Kumar"                  |
|       |                                                                                                                                              | git config --global user.email "sudhir.kumar@city-link.co.in" |
| 17    | unstage the additions                                                                                                                        | git reset HEAD                                                |
| 18    | Undo Changes To Unstaged Files                                                                                                               | git checkout -- filename                                      |
| 19    | Switch From One Branch To Another                                                                                                            | git checkout branchname                                       |
| 20    | What Branches My Repository Has                                                                                                              | git branch                                                    |
| 21    | Create A Branch                                                                                                                              | git branch branchname                                         |
| 22    | Merge Two Branches                                                                                                                           | git merge source destination                                  |
| 23    | The Differences Between Branches                                                                                                             | git diff branch-1..branch-2                                   |
| 24    | removes the file                                                                                                                             | git rm filename                                               |
| 25    | Create A Brand New Repository                                                                                                                | git init project-name                                         |
| 26    | Create A Copy Of An Existing Repository                                                                                                      | git clone URL                                                 |
| 27    | Find Out Where A Cloned Repository Originated                                                                                                | git remote -v                                                 |
| 28    | Pull In Changes From A Remote Repository                                                                                                     | git pull remote branch                                        |
| 29    | Push My Changes To A Remote Repository                                                                                                       | git push remote-name branch-name                              |
|       |                                                                         
              | git push -u origin master                                     |
| 30    | removes the local, remote branch  
              | git branch -d branch-name                                     |
|       |                                                                         
              | git push origin --delete branch-name                          |
