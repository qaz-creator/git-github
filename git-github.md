## Git and Github
### What are they?
- Git : a version control system, it tracks the changes of our files
- Github : share the git repositories

### Set up Git

`git config --global user.name "Mona Lisa"`

`git config --global user.email "email@example.com"`

### Upload Github from local

- `git clone http://.......`      clone the doc from github to a folder

- `git status`   

- `git add .`     add the documents

- `git commit -m "adding title"`     add the message

- `git remote add orginin https://..`

  origin is the name of URL

  `git remote -v`

- `git push -u origin master`   push to github
  - push whenever you want to sync your changes up to github

### When someone else makes changes

- permit other collaborators

  settings>collaborators

- get the change from local

  `git pull origin master`

  origin: url

  master: branch

### Create new branch

- create a new branch

  `git checkout -b relaxing`

- `git add playlist.txt`

- `git commit -m 'add relaxing songs'`

- `git push -u origin relaxing`

  relaxing: branch name

- `git branch`      check the branch

### Pull request to an open source

in the case clone a repo

then `git log`, you can see all the commit

fork the repo

clone our fork

`git add styles.css`

`git commit -m 'make everything purple'`

- `git remote -v`

  check if we have the automatical remote when we clone a repo

- `git push -u origin master`
- go to the fork , click `pull request`, `create pull request`

### Other orders

`git diff`      to see the different we made
