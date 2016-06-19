# hello-world
This project is for me to learn how to use git.

- First I'll clone the github version to my local version:
`git clone https://github.com/JohanSchott/hello-world.git`

- At any time one can use commands `git log`, `git status` and `git diff`. 

- Edit a bit in the README.md file.

- After that, update the local version: `git add README.md` and `git commit -m "update README"`.

- Now I update the remote version: `git push origin master`

- Then locally create a new branch: `git checkout -b [name_of_your_new_branch]`

- Edit repository by adding file `hello.py` containing `print('hello python')`.

- Add these changes and commit: `git add hello.py` and `git commit -m "adding python script`.

- Push this local branch to github: `git push origin [name_of_your_new_branch]`

- To inspect all branches, type: `git branch`

- Now merge the non master branch to the master branch: `git checkout master` and then `git merge [name_of_your_new_branch]`.

- To delete the now unnecessary non-master branch, type: `git branch -d [name_of_your_new_branch]` 

- To delete the remote non-master branch, type: `git push origin --delete [name_of_your_new_branch]`

- In the case of merge conflicts, one have to manually solve it. The command `git mergetool` can also be of help. 

- `git fetch` just download updates from the remote to the local directory. But does not update the local branch, thus the downloaded data in hidden locally. `git merge` will merge two branches and `git pull` will do the same thing as `git fetch` followed by `git merge`.  

