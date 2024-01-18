# git-branching
Learning Git Branching

## define terms
- Branch
- 1. Isolation
- 2. Parallel development

## Git commands
1. Create a branch
'''bash
   git branch "branchname"
'''

2. Switching between branches
'''bash
   - git swwitch branchname
   - git checkout branchname
'''

-    Directing switching to a new branch
'''bash
    git checkout -b branchname
''' 

3. Merging
'''bash
   git merge sourcebranch
'''

4. Conflicts
'''bash
   git mergetool
'''

5. List all branches

git branch
git branch -v


'git status'

- list merged commits
'git branch --merged'
- List unmerged commits
'git branch --no-merged' 