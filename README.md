# lesson4-github
Use Github well. I will not go into detail because these things are already well documented across the internet. I will simply tell you what you should know. If you do not understand git, you will not be able to work well as a team and will constantly cause conflicts between each other's work.

Wow this seems so meta, using github to talk about github...

## What you should know
### Conflicts
You should know what merge conflicts are and be able to resolve them. This should be true for all members of the team. If one member is spending all of their time maintaining the git repo, then they are unable to develop.
### API keys
Don't push code that has API keys in them. If the repos are public, then people will steal these keys and 'farm them out' for their own use and spam. Instead import API keys into the necessary modules, and keep your KEY files in the gitignore so that they are not pushed to master.
### Branches
I will not require that you use branches, but you probably should. Look up some tutorials and understand how they work.
### Committing
Only commit the changes you care about. Don't commit everything in your directory, especially binary files. Things like the node_modules folder will differ from person to person and pushing your node_modules folder will likely break their setup.
### Diff
Use diff to figures out what changes you made and if you actually care about them or not. If you don't then pull the remote version of that file and throw away your changes.
### Pushing
Push as often as you can. You want your teammates to have the most up to date version of your code.
### Pulling
ALWAYS PULL BEFORE PUSHING! Often git will force you to, but you should do so anyways.
### Rebasing
When your branch gets too far off base from master, then rebase! It is a good idea to do so before submitting a pull-request and merging your code into master.
### Pull Requests
These are used with branches. They will be necessary to merge your branch code into master, unless you want to cherry pick instead, which is not recommended.
### Git Status
Tells you which files differ from remote, but not what those changes are.
### .gitignore
This is especially important. Use this file to stop from pushing junk files, large files, or files that will cause conflicts. As stated at the beginning this is also good practice for keeping your secret keys secret.
