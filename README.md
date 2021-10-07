# demo with no live repo initial

# commands used and explaining the work they did.

'git init'  (Initialized the empty git repository )Executing this command will create a new .git subdirectory in your current working directory. This will also create a new main branch. 

'git status' To check any untracked and modified files

'git add README.md'  to add the specific file in repo, If there were more files and we have to add all of them so 
we can use 'git add ./' or 'git add .' , they both works the same /(forward slash)

'git status' again to check the changes to be committed.

'git commit -m "(some description)" '   here we have to write some description otherwise it will not commit, and brackets 
are not used though I put it just for boldness.

'git push origin master' it can be main in the place of master , btw both are just to denote the first branch of the repo
the above push command will give fatal error that 'origin' does not appear to be a git repository if we haven't created
the repo manually in github, because we are just pushing it to the live repo and if there isn't any live repo it won't push and will give error, so first we have to create a repo manually in github can be empty .

'git remote add origin (github repo url that we created)' means somewhere else not here
actually 'remote' means not in this repository. You can just create a different directory in like '../my-fake-remote-repo' and instantiate a --bare flagged git repo there and use that as your 'remote' repo. It's a pretty cool thing you can make your own simple home server to backup your things and not depend on tools owned by mega corps.

'git remote -v' to check any remote repo that we have connected to this local repo. 

then we push it with the same command we wrote above remote. 
then it will be pushed there.

git pull
