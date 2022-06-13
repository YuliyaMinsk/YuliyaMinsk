# Move branch to new server

git clone --single-branch --branch branch-name link-to-old-repo
git remote add mine link-to-new-repo
git push -u mine
