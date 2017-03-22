### always run 'git init' in a directory.

# New project repository

Create repository in GitHub

Command line
1. git init
- git add -A
  - adds ALL files to your repository
- git commit -m “first commit”
  - need to name my 'project'
- git remote add origin
  - (copy and paste the URL from your new repo page on GitHub)
- git push -u origin master
  - this pushes all files in this directory

Existing project
1. git status
  - reminds you of what files you have already committed
- git add -A
  - preparing to save changes made to all files
- git commit -m "INSERT DESCRIPTION OF CHANGES"
  - adds message to your commit, where you can tell yourself what you accomplished since last commit(BE SPECIFIC)
- git push origin master
  - Hooray! You have saved your project changes to the cloud!

Other Commands
- git status
  - shows what's been synched
- cat README.md
  - display this file in the terminal
