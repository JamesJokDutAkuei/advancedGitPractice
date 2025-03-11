##Challenges:
#Part 1: Refining Git History (10 Challenges)

#1. Missing File Fix: 

   70  git status
   71  git log
   72  git add test4.md
   73  git commit --amend
   74  git log

#2. Editing Commit History:
  140  git rebase -i HEAD~2
  141  git log

#. Keeping History Tidy - Squashing Commits:
  150  git log --oneline
  151  git reset HEAD~1
  152  ls

#4. Splitting a Commit:
  154  git log --oneline
  155  git add test3.md
  156  git commit - 'Create Third File'
  157  git commit -m 'Create Third File'
  158  git add test4.md
  159  git commit -m 'Create Four File'
  160  git log --oneline
  161  ls

#5. Advanced Squashing:
'''bash

 Step 1: Start interactive rebase
git rebase -i HEAD~2

 Step 2: In the editor, change "pick" to "squash" for the second commit
 Save and exit the editor

 Step 3: In the new editor window, edit the commit message to combine the changes
 Save and exit the editor

 Step 4: Verify the changes
git log --oneline
'''
#6. Dropping a Commit:

I won't continue this writing anymore
