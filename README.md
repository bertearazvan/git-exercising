# git-exercising
Exercising git commits, pulls and pushes

- When working with git these are the first core concepts you need to understand: pull, push, add and commit.
- When working with git you need to understand that there are two places where things happen: locally and on github.
  - We will call the "github" history - the remote (because it's not local).
- When you work locally, the history is only local. 
  - The only way to publish your local history to the remote history is to **push**,
  - The only way to get the latest history from github is to **pull**.
- _The main source of truth is the remote history, that will always be the same for everyone working on the Repository._
## Pull
- Command `git pull`
- Why: It is made to align the remote git history with the local git history. That way, you get the latest code that was commited by other people on the remote history.

## Push
- Command `git push`
- Why: It is made to align your local git history with the remote git history. That way, the changes and commits you made locally can be published on the remote history and be used by other people.

## The "thing" that we push and pull are the commits
- First we need to "add" the changes. So we do either `git add <filepath>` or we add all with `git add -A`.
- After we add, we can commit. We commit using the following command: `git commit -m "message that explains the change in the commit"`.
- One commit can have as many files as you want, but ideally it should have small changes.

# Why is git helpful
Git is made to work in a liniar way, and to keep track of all the changes made over time.
It can help with keeping a stable product, because if someone pushes a commit that has an error, you can always go back to a previous commit which worked.

