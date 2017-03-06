# learning-git
Dummy project to learn all features of git.

So, if you are looking for something useful, this repo is not for you.

To delete a local branch
git branch -d <branch_name>

To delete a remote branch
git push origin --delete <branch_name>

To view the upstreams
git branch -vv

Merge in a single commit object:
git merge --no-ff <other-branch>

Set an upstream
git push --set-upstream origin rewrite-wea

Create new branch from a tag:
git checkout -b <branch-name> <tag-name>

Show a tag info
git show v0.0.0

Tag a specific commit:
git tag -a v0.0.0 98138c5150dc5e0f6204062151b661327e136613

List all tags
git tag

Git log pretty:
git log --pretty=oneline [<branch-name>]

View and filter tags
git tag -l "v0.0*"

Create an annotated tag:
git tag -a v0.0.1 -m "My very first version."


Show difference between branches
git diff remotes/origin/master..master

Show the origin things
git remote show origin

Solve when you remove a local remote-tracking branch.
git branch --unset-upstream