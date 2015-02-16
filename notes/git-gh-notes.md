#Git & Github

Resource: [GitGuides](https://guides.github.com/introduction/flow/)

-  `git init` -initializes repo
- `git status` -tells you where you are and chgs
-  `git add --all`   -adds all files
- `git commit -a  -m "my message"` - commits w/msg

### Setup GH Repo

1. create gh repo online
2. add repo as remote on cli i.e. `git remote add origin https://github.com/ccsouthard/thinkful-examples.git`  - the remote is copy of local
3. push repo from cli  `git push -u origin master`
4. `git pull origin master` -keeps master up-to-date
5. check files
6. git merge slang
7. git checkout

### GitHub Interacting

- `git clone` url  - to clone repo from GH
- `git branch` and `git branch master`- checks branch, second adds another name
- `git branch -d slang` -removes branch slang
- `git push origin :slang` -pushes empty branch thus cleaning GH
- `git checkout master`- switches branch to master

#### Pull Requests
- create from GH 
-  initiate discussion about commits
-  share ideas and screenshots/review work
-  Pull Requests are designed to encourage and capture conversation
-  after review, merge w/master, good for history of how and why changes are made

### GH Pages

 - `git checkout -b gh-pages` 
- `git push origin gh-pages`
 