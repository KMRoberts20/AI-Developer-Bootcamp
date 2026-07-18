### Learning Pull Requests

🌿 Create a feature branch
☁️ Push that branch (not main)
🔍 Open your first Pull Request on GitHub
💬 Review the Pull Request
✅ Merge it
🔄 Sync your local repository afterward

# Day 7 – GitHub Collaboration

## What I Learned

Today I learned how professional software teams collaborate using GitHub.

Key concepts:
- Feature branches
- Pull Requests
- Code reviews
- GitHub Issues
- Forks
- Open source workflow

## Biggest Takeaway

Branches allow developers to work independently without affecting the stable main branch.

So your official Day 7 lesson:

✅ A Pull Request is not a merge
✅ A merge does not delete a branch
✅ Branches are pointers, not copies
✅ Developers decide when to delete branches
✅ Trust your reasoning and use evidence to adjust it

✅ You created the feature branch
✅ You made your changes
✅ You committed them
✅ You pushed the branch to GitHub
✅ You opened a Pull Request
✅ The PR was reviewed
✅ It will be merged into main

At this point, the branch has done its job.

The workflow is:

Create feature branch
          ↓
Develop feature
          ↓
Open Pull Request
          ↓
Merge into main
          ↓
Delete feature branch
          ↓
Start next feature branch
Why delete it?

Because this is a completed work branch.

Keeping it around would add clutter:

Branches:

main
feature/day-1-terminal
feature/day-2-files
feature/day-3-git
feature/day-7-collaboration
feature/login
feature/test
feature/random-experiment

Imagine a real company with hundreds of merged branches. It becomes difficult to know what is active and what is historical.

The Pull Request itself preserves the history.

Important distinction:

Deleting the branch does NOT delete the work.

Your commits are now part of main.

The history remains:

main
 |
 ● Add Day 7 collaboration notes
 |
 ● Previous commits

The branch label is simply removed.

After you click Delete Branch

Your GitHub repository will show:

main
  |
  ● Add Day 7 collaboration notes

The feature branch name disappears from GitHub.

Later, if you need the details, you can still find them through:

the Pull Request
the commit history
GitHub activity

### History of Day 07
The Complete Developer Workflow You Just Executed

Let's write this down because this is now part of your developer toolkit:

1. Start from a clean main branch
git status

✅ Confirmed clean

2. Create a feature branch
git switch -c feature/day-7-collaboration

You created isolated workspace.

3. Make changes

Created:

Bootcamp-Notebook/Day-07.md
4. Save your work in Git history
git add
git commit

Created a checkpoint.

5. Push your branch to GitHub
git push -u origin feature/day-7-collaboration

Shared your work.

6. Open a Pull Request

You created a review process:

feature/day-7-collaboration
              ↓
             main
7. Review the change

You examined:

Conversation
Commits
Files changed
8. Merge the Pull Request

Your work became part of main.

9. Delete the completed feature branch
git branch -d feature/day-7-collaboration

Cleaned up.

10. Synchronize your local repository
git pull

Brought your Mac up to date.