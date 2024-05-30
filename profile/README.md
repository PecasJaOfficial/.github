# PecasJáOfficial

This README is being created globally for our organization, that is, it will be a place where I will describe some rules and the like.

## How to versioning

One very important thing for every repository on GitHub is versioning. To do this, we will be using a CLI tool called git.
This tool helps us with many things. However, how we will use it to organize ourselves is another story.

We will follow a versioning line called Gitflow. This pattern of working with git says that we will work with a very specific set of branches, namely:

- main
- develop
- staging
- hotfix
- bugfix
- feature

Each of these branches has a specific function within our project. Descriptions follow:

- **main**: this branch is our production branch, that is, this is where the finished code will be stored. We can only push to this branch when all the developed code has already been tested and is ready to be deployed
- **staging**: this is the branch used to test all developed codes. In other words, if we create a new screen and need to perform E2E tests, then the code will go to this branch to perform the tests and, if everything goes well, we update the develop and main branches with the tested code
- **develop**: this is the branch where all the code under development will live. If you are going to develop something, this is where you will do it and it is always from here that you will create new branches
- **feature**: this branch will be where we will develop new features. The name pattern for feature branches should always be `feature/<feature_name>`
- **hotifx**: this branch will serve as a quick fix for bugs that arise in the production environment
- **bugfix**: this branch will be used whenever code from the develop branch has gone to the staging branch for testing and bugs have been found. Thus, the code will be placed in a `bugfix/<bug_name>` branch and fixed.

## Communication

It is ideal that all communication about the software is via GitHub, this way we can centralize all information and questions here.
However, these conversations are restricted here when it comes to questions about the tasks we have assigned. These conversations must be carried out within the Issues opened for your task.
However, these conversations are restricted here when it comes to questions about the tasks we have assigned. These conversations must be carried out within the Issues opened for your task

## Issue Openings

Issues are a way for us to improve and create a history of bugs, improvements and everything we need to do in our software.

So, whenever you think it is necessary to create a new feature, an improvement or a bug fix, open an issue on GitHub, describe your ideas according to the pre-made GitHub template and tag me for approval and, if necessary , create a task to resolve the request
