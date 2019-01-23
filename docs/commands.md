## Commands Tables

### Configuration

`git config [--system|--global|--local] <command>`

Look for system, global or repo level configuration file. Lower level entries overwrite the parents.

|Read Config|Note|
|-|-|
|`git config --global --list`| list the configuration global for the user |
|`git config --local --list`| list the configuration specific for this repo |
|`git config --get user.email`| get user email used |

|Write Config|Note|
|-|-|
|`git config --local user.email foo@example.com`| set local user email for this repo|

### Log

|Read History|Note|
|-|-|
|`git log --oneline --decorate --all --graph`|one line per commit, show header/branch pointers, show all, use graph|
|`git log --author gianluca`| list commit from a specific person|
|`git log -3 --oneline`|show the last 3 commits in simplifieed format (oneline|
