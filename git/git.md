## General
| Command             | Description |
| -----------------   | ----------- |
| `git --version`     | get the git version |
| `git help`          | Help (googling is better) |

## Setup
| Command             | Description |
| -----------------   | ----------- |
| `git init`          | initialize the git repo locally |
| `git clone <repo url>` | retrieve an entire repo from a hosted location |
| `git remote -v` | Check the remote repo URL |
| `git remote add origin <HTTPS or SSH URL>` | Adds a new remote to local git repo |
| `git remote set-url origin <HTTPS or SSH URL>` | Change remote URL from HTTPS to SSH and vica-versa* |
| `git config --global user.name ¨username¨` | configure user information (username) |
| `git config --global user.name ¨email-id¨` | configure user information (email-id to be associated with history marker) |
| `git config --list` | view all the git settings |
| `git config --list --show-origin` | view all the git settings and the origin they are coming from |
| `git config --global core.editor <editor name>` | set the default editor for git to use |
| `git config <key>` | get the key value from the config |

## Stage and commit
| Command             | Description |
| -----------------   | ----------- |
| `git status`        | show modified files and files staged for commit |
| `git add <file or .(all)>` | add/stage files for commit |
| `git commit -m ¨<message>¨` | commit your staged content (snapshot) |
| `git reset <file>` | unstage a file |

## Inspect
| Command             | Description |
| -----------------   | ----------- |
| `git log`        | commit history for the current active branch |
| `git log -n #` | list last n number of commits |
| `git log <branch1>..<branch2>` | commits between branch1 and branch2 |
| `git log <branch1> ^<branch2>` | commits in branch1 that are not in branch2 |
| `git log -p <file>` | lists the commits ands changes for a particular file over its history |
| `git log --oneline --decorate --graph` | pretty git logs |

## Compare
| Command             | Description |
| -----------------   | ----------- |
| `git log`        | commit history for the current active branch |
| `git log -n #` | list last n number of commits |
| `git log <branch1>..<branch2>` | commits between branch1 and branch2 |
| `git log <branch1> ^<branch2>` | commits in branch1 that are not in branch2 |
| `git log -p <file>` | lists the commits ands changes for a particular file over its history |
| `git log --oneline --decorate --graph` | pretty git logs |


## Some useful links
- [Switching remote URLs from HTTPS to SSH](https://docs.github.com/en/github/getting-started-with-github/getting-started-with-git/managing-remote-repositories#switching-remote-urls-from-ssh-to-https)
- [Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [Adding a new SSH key to your GitHub account](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
- [Creating a personal access token](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- [Git cheatsheet by GITHUB](https://education.github.com/git-cheat-sheet-education.pdf)
- [Repo containing extensive git cmds](https://gist.github.com/hofmannsven/6814451)
