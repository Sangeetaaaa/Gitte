Gitte - Initialize Git, Add all your files, Commit it, Add Remote and push it with just one command
=====

Just by using $ gitte push you can save a lot of your efforts while pushing your code to github


$ gitte push -r https://github.com/Sangeetaaaa/Gitte.git -m "initial commit"

note: This will push your code to master branch


# Installation

```sh-session
$ npm install -g gitteee
```

# Usage
```sh-session
  $ gitte push -r https://github.com/Sangeetaaaa/gitte-gitcmd-automation.git  -m "Intial Commit"

  $ gitte push
```

### DESCRIPTION

$ gitte push -r add-your-remote  -m "commit-message"

This command will initialize git, add all your files to stagging area, commit it with your given message, will add remote and will push your code to master branch.  


$ gitte push 

This command will add all your files to stagging area, commit it and will push to the master branch

note: This command will show err if remote was not added before.

