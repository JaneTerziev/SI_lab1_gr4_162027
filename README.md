Documentation for the work

For cloning the remote, the git clone *link* command was used.
After creating a repo on github, the command git remote --v was used to list
current origins. After that git remote rm *origin* was used to remove the current origin
and git remote add origin *link* was used to add a new one.

For adding files with a commit, git add . or git add filename was used and
after that git commit -m "message" was used.

To create a new branch, git branch *branchname* was used, then git checkout *branchname*.

At the end, git checkout master, git rebase *branchname* was used.
We could use merge instead of rebase but that would leave an extra commit message on the branch.

There were no conflicts for the merge because the branch was up to date with master because we created the branch through master.
