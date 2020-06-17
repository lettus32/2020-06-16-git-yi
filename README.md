# 2020-06-16 Git

- `git init`: create a git repository in the current directory
- `git status': tells you what is going on
- `git add <FILENAME>`: adds <FILENAME> to the staging area (aka index)
- `git commit`: opens up nano, commits the files in staging with a message
- `git log`: shows the history of commits we have done
      `git log --oneline`: shows a shorer oneline version of  `git log`
- `git diff`:compare current state to last state
      - `git diff HEAD~1(FILE>`: compares current state from 1 state ago
      -`git diff <HASH> <FILE>`: compares current state from satte in <HASH>
      -`git diff --staged <FILE>`: comparing differences when files are in teh staging area
- `git checkout <HASH> <FILE>`: reverts the <FILE> from <HASH> back to your current state
- `git checkout <HASH>`: reverts entire folder state to <HASH>
      -`git checkout mastyer`: to go back to your latest work
- `HEAD`:this tells you where you are looking at in history
