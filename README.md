# learning-git


#GIT

##what is git?

Git is version control system used by almost all the organizations

##How can you control parallel development and how multiple developers can contribute the code parallelly?

Git branches is th eonly solution for parallel develsopment

##What is git branch?

A branch is a version of your repository, or in other words, an independent line of development. A repository can contain multiple branches,which means there are multiple versions of the repository

Among all, main/master branch is something which you should always a checkout to create a new/feature branch

##Git branch naming strategy?


Branch naming will be based  on your organisation
Either you will work on developing
a) a feature
b) a hotfix
c) a bug

So, majority of the times, your branch name should be the following way
a) feature/story-number
b) hotfix/story-number
c) bug/story-number
d) story-number

##Common GIT commands

$git branch                       // shows list of branches and current branch
$git branch branchName             // creates a branch from the main branch
$git checkout branchName       // switches to the created branch
$git checkout -b branchName          // creates a new branch from the main branch as source and switches to the created branch
$git push origin remoteBranchName  //Pushes the changes to remote branch. If the branch doesn't exist on remote git,it crates by the same push

whenever you push any changes and if they look good and stable on main branch, then you will raise or create a git tag

git tag: almost like a tag attached to the jar-creating a name to a commit which can be referred later

git and linux are like oceans, infinite things are there to learn. Both of them are created by the same person : Linus Torvalds
