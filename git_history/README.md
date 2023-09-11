# Understanding Git History

 In this Assignment, we will explore the concepts of Git history, the log command, and commands for reverting, undoing, resetting, and rebasing changes.

## Git Log:
The `git log` command is used to view the history and commit log of a repository. Running `git log` in the terminal displays a list of commits in reverse chronological order, with the most recent commit appearing first.
![Screenshot 2023-09-11 155120](https://github.com/HimanS-sys/intro_to_git/assets/68765011/cf29ddd4-7854-4afe-b19e-4917b75f9a0c)
</br>
## Git Revert:
The `git revert ""` command is used to create a new commit that undoes the changes made in a previous commit, effectively reverting the changes. This allows you to keep a clear history while undoing specific modifications.</br>
Replace "" with the commit hash of the commit you want to revert. Git will create a new commit that undoes the changes introduced by the specified commit.

![Screenshot 2023-09-11 161700](https://github.com/HimanS-sys/intro_to_git/assets/68765011/ab45ac2b-7761-44c2-a8f4-dfdc6e60cc2d)
</br>
## Resetting Changes:
The `git reset` command allows you to reset the state of the repository to a specific commit or to unstage changes. There are different modes of `git reset`, but two commonly used modes are:
- Soft Reset: `git reset --soft ` moves the branch pointer to a specific commit, preserving the changes as unstaged. This allows you to recommit the changes if needed.
  
![Screenshot 2023-09-11 170649](https://github.com/HimanS-sys/intro_to_git/assets/68765011/a4cccff3-93ac-4309-832b-0af9e97917b6)

- Hard Reset: `git reset --hard ` moves the branch pointer to a specific commit and discards all changes after that commit. This permanently removes any modifications, so be cautious when using this command.
  
![Screenshot 2023-09-11 171119](https://github.com/HimanS-sys/intro_to_git/assets/68765011/9a66e871-f184-401e-a6b5-3acfb36e3de0)

## Rebasing Changes:
The `git rebase ""` command is used to apply changes from one branch to another. It allows you to move or combine a sequence of commits onto a new base commit.</br>
replace "" with the branch you want to rebase onto</br>

Example:

* branch_a files

![Screenshot 2023-09-11 173621](https://github.com/HimanS-sys/intro_to_git/assets/68765011/8442bcb4-4c88-4cc6-99a2-e3d1c47c3934)

* branch_b files 

![Screenshot 2023-09-11 173704](https://github.com/HimanS-sys/intro_to_git/assets/68765011/98b7f85e-b3e9-4f38-90c1-4a9c2cd74270)




