### Commands for Configuration

|Read Config|Note|
|-------|----|
|`git config [--system\|--global\|--local] <command>`| look for system, global or repo level configuration file (lower level entries overwrite the parents)|
|`git config --global --list`| list the configuration global for the user |
|`git config --local --list`| list the configuration specific for this repo |
|`git config --get user.email`| get user email |
|**Set Config**|**Note**|
|`git config --local user.email foo@example.com`| set local user email for this repo|
