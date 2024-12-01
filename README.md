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
