# git-cli cheatsheet

| git command                                                              | description                                                                                         |
|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| `git clone https://github.com/shmbrg/basics.git`                         | clones this repo via https                                                                          |
| `git status`                                                             | find yet unversioned files                                                                          |
| `git add my_file.py` <br> `git add .`                                    | marks specific or all files for next commit                                                         |
| `git commit -m "my commit message`                                       | commit changes with commit message                                                                  |
| `git push --set-upstream <remote> <branch>` <br> `git push -u <remote> <branch>` | set up remote tracking branch to your current branch                                                |
| `git push <remote> <branch>`                                             | push changes from your local branch to your remote branch (upstream branch has to be set initially) |
| `git branch -vv`                                                         | check upstream branch                                                                               |
| `git branch my_feature_branch`                                           | create new feature branch                                                                           |
| `git checkout -b my_feature_branch`                                      | switch to new feature branch while creating it on the fly                                           |
| `git checkout <branch>`                                                  | switch to different branch                                                                          |
| `git merge <branch>`                                                     | merge branch into `main` (do this on `main` branch)                                                 |
| `git pull <remote> <branch>`                                             | pull changes from remote branch |
