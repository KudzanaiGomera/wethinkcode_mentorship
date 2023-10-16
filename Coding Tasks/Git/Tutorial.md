Git is a popular version control system. It was created by Linus Torvalds in 2005, and has been maintained by Junio Hamano since then.

## It is used for:

Tracking code changes
Tracking who made changes
Coding collaboration
What does Git do?
Manage projects with Repositories
Clone a project to work on a local copy
Control and track changes with Staging and Committing
Branch and Merge to allow for work on different parts and versions of a project
Pull the latest version of the project to a local copy
Push local updates to the main project

## Working with Git
Initialize Git on a folder, making it a Repository
Git now creates a hidden folder to keep track of changes in that folder
When a file is changed, added or deleted, it is considered modified
You select the modified files you want to Stage
The Staged files are Committed, which prompts Git to store a permanent snapshot of the files
Git allows you to see the full history of every commit.
You can revert back to any previous commit.
Git does not store a separate copy of every file in every commit, but keeps track of changes made in each commit!

## Why Git?
Over 70% of developers use Git!
Developers can work together from anywhere in the world.
Developers can see the full history of the project.
Developers can revert to earlier versions of a project.

## Platforms
- GitHub
- Bitbucket
- GitLabs

## Using Git with Command Line
$ git --version

$ git config --global user.name "username"
$ git config --global user.email "test@gmail.com"

$ git status

$ git add . && git commit -m "done with the button" && git push

$ git checkout master

$ git merge emergency-fix

etc

