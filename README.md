# demo

demo
something something

# subheader

whatsupp
git clone git@github.com:mathewant10y/demo.git
git add . --- selects all files to be included in git
git status --- shows the status
git commit -m 'added index.html' -m "some description"
git commit -am ' ' --- only works for committing modified files not newly created files
git push --- pushes to github

# branches

git branch --- shows us which branch we are in (eg- main branch)
git checkout -b feature-readme ---switches and created a new branch named feature- readme
git checkout 'branch name' --- switches to the required branch

git diff feature-readme --- shows us the differences between the main branch and the new branch (done while on main branch)
git push -u feature-readme --- pushes the side branch to github (done while on side branch)

PR means a pull request ie a request to get your code pulled into the main branch from the side branch.
after pushing sided branch take github repository which will show the option to pull request. then merge the branch
d

git pull --- is done in local repository ( in vs code) to pull the modified main branch
after pr is merged the side branch is deleted
git branch -d feature-readme --- deleted the branch

# merge conflicts

they occur when merging two branches(main and side) which have different code entered
it can be resolved in the vs code editor
