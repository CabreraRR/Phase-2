# Committing Atomic Changes With Git

## Skills

- [x] Can define a Git alias
	- to apply a git alias you can inut `git config --global alias.*SHORTCUT* *COMMAND*`
	for exampnle...
	```bash
	git config --global alias.ci commit
	```
	this will make the `git commit` command shortened to `git ci`
- [ ] Can add Git metadata to your shell prompt
	- 
- [x] Can use `git pull --rebase`
	- this command will fetch data from the remote and merge it into the working commit. For small fixes this will look better in the commit history and less messy.
- [x] Can use `git reset`
	- this will reset the working branch to reset to the previous commit (`HEAD`)
- [x] Can use `git reset HEAD^`
	- this will reset the working directory back to one commit behind the `HEAD`
- [x] Can use `git add -p`
	- this command will allow the user to compare and review the contents of the changesbefore adding to the index
- [x] Can use `git checkout -p`
	- will allow the user to compare the difference between the current working directory and the tree
- [ ] Can use `git reset -p`
	- allows the user to check the difference between the index and the `HEAD`
- [x] Can use `git stash`
	- will put all the changes to the working directory in a stash that will hold it temporarily
- [x] Can use `git stash pop` {git stash --help}
	- will apply one of the stashes to the current working directory
- [x] Can create a Git branch
	- `git branch *BRANCH NAME`
- [x] Can merge Git branches
	- `git merge *BRANCHNAME*` will merge the named branch with the current working directory

## Google search terms

```
how to resolve a merge conflict using git
git workflow
how to save git changes without creating a commit
git how to sync a branch with the master branch
git cheatsheet
```

## Suggested Resources

### Reading

- https://www.atlassian.com/git/tutorials/comparing-workflows
- http://rogerdudler.github.io/git-guide/
- https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging
- https://www.digitalocean.com/community/tutorials/how-to-use-git-branches
- [Git Cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)

### Watching

- ['Git Tutorials || 3.Branching and Merging'](https://www.youtube.com/watch?v=uR-9NGrpU-c)
- ['Git: Working with Branches'](https://www.youtube.com/watch?v=JTE2Fn_sCZs) 
- ['Git & GitHub: Branching (8/11)'](https://www.youtube.com/watch?v=a6D-9MIdWKk)
- [Git Checkout -p](https://www.youtube.com/watch?v=I6oD_eXXYpE) 

## Practice
- Complete the `git.rocks` tutorial in the following sequence
  - http://git.rocks/advanced/
  - http://git.rocks/branches/
- Complete the exercises at [Learn Git Branching](http://learngitbranching.js.org/)
