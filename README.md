# get-better-at-git
Notes from the Free Code Camp Git for Professionals Course

# The Perfect Commit

- Create commits that 'make sense'
- Make commits as small as possible, commiting only changes that are related
- Do not batch all local changes into one commit!!!
- Smaller commits are easier to understand
- For staging partials use `git add -p <filename>`
- Commit messages
  - Subject should be concise
  - Body should be more verbose and detailed
  - Commit message body should answer
    - What is different than before?
    - What is the reason for the change?
    - Is there anything that others should watch out for in this commit?

# Branching Strategies

- Well documented conventions are critical regardless of the strategy
- Most projects use the Github Flow model with one long running branch, integrating short running feature/bug fix branches

# Merge Conflicts

- You can always abort a merge/rebase with `git merge --abort || git rebase --abort`
- Merge conflicts can be resolved by simply cleaning up the file

# Merge vs. Rebase

- Merge
  - Simply integrates commits from one branch into another
  - The structure of the branches and their commits is preserved in the git history

- Rebase
  - Temporarily parks the commits of one branch, then integrates the commits from the new branch, then finally it "rebases" the parked commits on top of everything 
