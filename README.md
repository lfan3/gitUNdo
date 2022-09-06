# gitUNdo

## learing how to undo with git
-unstaged
  git restore filename
  git checkout filename
-change commit message
  git commit --amend -m "new msg"
-do not add new commit
  git commit --amend
- cherry-pick
  git cherry-pick commithash
  git reset --soft --mixed(default) --hard commithash
- clean untracked file
  git clean -df (directory +files)
- git reset vs git revert
  1)git revert creat a new commit of undo action. reset change the git history
  2)git revert on reverting commithash, reset to the wanting commithash
