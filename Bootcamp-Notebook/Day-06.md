## Goal

By the end of today you'll know:

Why merge conflicts happen
How Git detects them
How to resolve them
How to verify everything worked
Why they're actually not scary

## Accomplishments

✅ Created a branch
✅ Made independent changes
✅ Merged branches
✅ Created a real merge conflict
✅ Read Git conflict markers
✅ Resolved the conflict manually
✅ Staged the resolution
✅ Created the merge commit
✅ Verified your repository status

## Questions/Need further clarification

Nothing - but I may need to spend a bit more time on this task.  It went so smoothly that the practice was over quick.

## Git Concepts Mastered
Branches are separate timelines

You saw:

main
  \
   conflict-demo

Each branch can evolve independently.

Git tracks changes, not just files

You saw:

1 insertion(+)
1 deletion(-)

Git understood the change at the line level.

Merge conflicts are not failures

A conflict means:

"Git found a decision that requires human judgment."

Not:

"Git broke."

Conflict markers

You read:

<<<<<<< HEAD
=======
>>>>>>>

and understood what each section meant.

Resolving conflicts

Your workflow:

git merge
        ↓
conflict happens
        ↓
edit file
        ↓
git add
        ↓
git commit