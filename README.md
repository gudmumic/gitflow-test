# gitflow-test
Create a repository following the gitflow workflow

## Create develop branch
- `git flow init`

![git flow init](./images/gitflowInit.JPG)

- Push branch to remote repository

## Create a feature branch
- `git flow feature start feature_branch`

![git flow start feature branch](./images/startFeatureBranch.JPG)

## Publish a feature branch and create pull request
- `git flow feature publish feature_branch`

![git flow publish feature branch](./images/publishFeatureBranch.JPG)

Create the pull request from the link 

## Finish a feature branch
- `git flow feature finish feature_branch`

This command will close and merge feature branch locally into develop branch

![git flow finish feature branch](./images/finishFeatureBranch.JPG)

- push develop branch to remote respository

## Create a release branch
- `git flow release start release_version

![git flow initialise release branch](./images/initReleaseBranch.JPG)

## Finish releae branch
- `git flow release finish release_version

![git flow finish release branch](./images/finishReleaseBranch.JPG)




