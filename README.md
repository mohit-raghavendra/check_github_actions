## check_github_actions

A simple repository that has a couple of of markdown files. 
A Github Action is set up to run the english linter for markdown files [write-good](https://github.com/btford/write-good) on the markdown files present in the repository every time a new changes are pushed to the repository. 

There are a few mistakes in these files, that are made on purpose. 
The linter will catch these mistakes and display them when the jobs
are run in the workflow after a push. 
