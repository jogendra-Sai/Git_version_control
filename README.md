# Git_version_control
This Repo will contain Git Version Control Commands

git init (Used to initialize empty repositority)

git status (Used to check untracked files)

git add(used to convert files to tracked status)

git add *(Used to add multiple files)

git restore --staged names.txt (It will remove added files before doing a commit)

git commit -m "message" (Used to commit files)

git log (Used to check commits info)

//For Example if you want to remove the commits
  => Assume when you perform "git log" 3 commits came
  => commit-1 (hdhghhdhdhdh%hdxhdhhd)
  => commit-2 (ndkdhjjfbdjhfbdb&jjdj)
  => commit-3 (jhfjfdgfhgjkfdjfgjgj&h)
  => You need to resore code up to commit-3 
  => Use git reset jhfjfdgfhgjkfdjfgjgj&h
//For Example you are implementing a new functionality and you want the code some where and want to get clean code base
  => git stash
  => git stash pop(to get back stashed changes)

git remote add origin URL(used to attach remote repo to project)  

git branch feature

git checkout feature(here feature is branch)


//After Forking 
git clone https://github.com/jogendra-Sai/people.git

PS C:\Users\jogendrasaibabu.n\Desktop\Shift\Git Clone> git remote add upstream https://github.com/cncf/people.git (this the branch from where we forked the project)
PS C:\Users\jogendrasaibabu.n\Desktop\Shift\Git Clone\people> git remote -v
origin  https://github.com/jogendra-Sai/people.git (fetch)
origin  https://github.com/jogendra-Sai/people.git (push)
upstream        https://github.com/cncf/people.git (fetch)
upstream        https://github.com/cncf/people.git (push)
PS C:\Users\jogendrasaibabu.n\Desktop\Shift\Git Clone\people> 
