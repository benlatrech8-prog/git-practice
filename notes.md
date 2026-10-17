# Git Commands Learned

A quick summary of the git concepts and commands practiced in this repo.

- `git init` — start a new repository
- `git add <file>` — stage changes for commit
- `git commit -m "message"` — save staged changes with a message
- `git log --oneline --graph --decorate` — view commit history as a graph
- `git branch <name>` — create a new branch
- `git checkout -b <name>` / `git switch -c <name>` — create and switch to a new branch
- `git checkout <branch>` / `git switch <branch>` — switch between branches
- `git merge <branch>` — merge another branch into the current one
- Resolving merge conflicts — editing conflicted files, then `git add` + `git commit`
- `git revert <commit>` — undo a commit by creating a new commit that reverses it
- `.gitignore` — tell git which files/folders to ignore
- Pull requests — merging a feature branch on GitHub via a PR instead of a local merge
