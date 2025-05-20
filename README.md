# GitHub vs GitLab

| Feature/Creteria                                          |     🐙 GitHub                                            |                        🦊 GitLab                     |  
| ----------------------------------------------------------|:---------------------------------------------------------:| ----------------------------------------------------:|
|Owner                                                      | Microsoft                                                 | GitLab Inc.                                          |
|CI/CD Support                                              | GitHub Actions (Built-in)                                 | GitLab CI/CD (Powerful, Built-in)                    |
|Private Repos (Free Plan)	                                |Unlimited	                                                | Unlimited                                            |
|DevOps Features (Issue → Deploy)	                          |Basic + Integrations	                                      | Full DevOps Pipeline (All-in-one)                    |
|User Interface	                                            | Clean, popular, widely used	                              | Advanced, DevOps-focused                             |
|Self-Hosting	                                              | Only with GitHub Enterprise	                              | Full self-hosted version (free CE)                   | 
|Popularity	                                                | Extremely high (community projects)	                      | Moderate (corporate/internal projects)               |
|Open Source Support	                                      | Very high	                                                | Also good                                            |
|Merge Request vs Pull Request	                            | Pull Request	                                            | Merge Request                                        |
|Security / Permissions                                     |	Good	                                                    | More granular control                                |

# Basic Git Commands
| Command                                                   |     Description                                           |                        Example                       |  
| ----------------------------------------------------------|:---------------------------------------------------------:| ----------------------------------------------------:|
|git init                                                   | For New Repo                                              | git init                                             |
|git clone <url>                                            | import in local from remote repo                          | git clone https://github.com/user/repo.git           |
|git status                                                 | Current Repo Status                                       | git status                                           |
|git add <file>                                             | FIle push on stage area                                   | git add index.html                                   |
|git add .                                                  | All Repo file push on stage area                          | git add .                                            |
|git commit -m "msg"                                        | Repo changes or new file commit message                   | git commit -m "Add navbar section"t                  |
|git log                                                    | commit history                                            | git log                                              |
|git config                                                 | git setting configure                                     | git config --global user.name "Su......"             |

# Branching & Merging
| Command                                                   |     Description                                           |                        Example                       |  
| ----------------------------------------------------------|:---------------------------------------------------------:| ----------------------------------------------------:|
|git branch                                                 | Branch Show                                               | git branch                                           |
|git branch <name>                                          | New Branch                                                | git branch dev                                       |
|git checkout <name>                                        | Branch Switch                                             | git checkout dev                                     |
|git switch <name>                                          | Same as Checkout                                          | git switch dev                                       |
|git merge <branch>                                         | Branch Merge                                              | git merge dev                                        |

# Remote (GitHub / GitLab se linked)
| Command                                                   |     Description                                           |                        Example                         |  
| ----------------------------------------------------------|:---------------------------------------------------------:| ------------------------------------------------------:|
|git remote -v                                              | Remote URLs Show                                          | git remote -v                                          |
|git remote add origin <url>                                | Remote repo link                                          | git remote add origin https://github.com/user/repo.git |
|git push -u origin main                                    | First time push with upstream                             | git push -u origin main                                |
|git push                                                   | Local commits send to remote                              | git push                                               |
|git pull                                                   | Remote changes to local repo                              | git pull                                               |
|git fetch                                                  | Remote repo changes download                              | git fetch                                              |

# Undo / Reset / Fix
| Command                                                   |     Description                                           |                        Example                         |  
| ----------------------------------------------------------|:---------------------------------------------------------:| ------------------------------------------------------:|
|git restore <file>                                         | File convertlike last commit                              | git restore index.html                                 |
|git reset                                                  | Remove from Staging                                       | git reset index.html                                   |
|git revert <commit>                                        | Specific commit ko undo                                   | git revert a1b2c3d                                     |
|git stash                                                  | Current changes temporarily remove and save               | git stash                                              |
|git stash pop                                              | return to Stashed changes                                 |git stash pop                                           |

# Extra Helpful Commands
| Command                                                   |     Description                                           |                        Example                         |  
| ----------------------------------------------------------|:---------------------------------------------------------:| ------------------------------------------------------:|
|git show                                                   | Last commit detail                                        | git show                                               |
|git diff                                                   | Working directory and staging area's difference show      | git diff                                               |
|git tag                                                    | Version/tag assign (like v1.0.0)                          | git tag                                                |
|git cherry-pick <commit>                                   | apply specific commit                                     | git cherry-pick <commit>                               |
|git rm <file>                                              | file delete from Git                                      | git rm <file>                                          |


