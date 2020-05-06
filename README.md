# Backend Challenges boilerplate - package.json

## Deploying on Heroku  

### Remote repo on Heroku  

A copy of the repo is hosted on Heroku, and added as a remote.  
You can find `(heroku)` and `(origin)` remotes using the command  
`git remote -v`  

### Pushing to your remote Heroku's master branch

following the format  
`git push <remote-name> <local-branch>:<remote-branch>`  
you can  
`git push heroku master`  
OR if not pushing a branch other than master  
`git push heroku branch-name:master`  

Note: rememer to push to your changes to your origin repo as well

