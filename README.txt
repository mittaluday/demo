Inserted Line Two
Repository to be deleted

HEAD refers the last commit on the current branch that we are working on


git reset HEAD <file_name>: Unstages a file
git reset --soft HEAD^: Uncommits the last commit. One carat after HEAD says that move to the commit one before HEAD
git commit --amend: Adds whatever is staged to the current commit.
git reset --hard HEAD^: Blows away the last commit
git reset --hard HEAD^^: Blows away the last two commits
git checkout -- <file_name>: Blows away all changes to file since last commit
