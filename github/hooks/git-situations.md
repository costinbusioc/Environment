1. Move a commit to another branch if not pushed (from branch feature-a to branch feature-b)

git checkout master
git checkout -b feature-b
git checkout feature-b
git cherry-pick <commit-to-move-hash>
git checkout feature-a
git reset --hard <commit-to-get-back-to-hash>
