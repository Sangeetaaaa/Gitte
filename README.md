Gitte
=====

Just by using $ gitte push you can save a lot of your efforts while pushing your code to github

How ?

While pushing your code to github you need to initialize git, then you probably need to add all your files to the staging area, commit it, add remote and then only you are ready to push your code.


This all can be done using only one command

$ gitte push -r https://github.com/Sangeetaaaa/gitte-gitcmd-automation.git -m "initial commit"

note: This will push your code to master branch


# Installation

<!-- usage -->
```sh-session
$ npm install -g gitteee
$ gitte COMMAND
running command...
USAGE
  $ gitte COMMAND
...
```
<!-- usagestop -->

### USAGE
  $ gitte push

  $ gitte push -r https://github.com/Sangeetaaaa/gitte-gitcmd-automation.git  -m "Intial Commit"

### OPTIONS
  -m,  commit message

  -r,  add remote

  -h, --help         show CLI help

### DESCRIPTION

$ gitte push -r https://github.com/Sangeetaaaa/gitte-gitcmd-automation.git  -m "Intial Commit"

This command will initialize git, add all your files to stagging area, commit it with your given message, will add remote and will push your code to master branch.  


$ gitte push 

This command will add all your files to stagging area, commit it and will push to master branch

note: This command will show err if remote was not added before.

