### Merging with Github

You can use Github to back up some of you work and share code over the network.

### Creating a Repository in Github

To create a repository in Github go to your profile and press `new repository`.

* Name your repository something you will remember and can choose public or private.
* Public is open-source so anyone on the web can view the code and a private repository makes it so that only you and your team can view it.


Once you have a repository created on your local machine and in Github, you can use Github in the same way you use it locally. The only difference is that you need to push your changes up to the network repository after committing.

### Pushing a Repo to Github
```
git add 'file name'
git commit -m 'message of commit'
git push -u origin master
```
This can be thought of having another branch that is remote, and adding your changes from a local machine to the network machine.

Now check your Github and see the green boxes begin to fill!

### Git Pull
 Pulling repositories is used for when someone you are working with makes changes to the repo and allows you to update to their changes to be working on the same branch.

```
 git pull 'name of branch'
```

### Cloning a Repository
* `git clone 'url of repository found in github'`
* `git remote add origin 'github url'`
* `git push -u origin master`
* `git push origin 'branchname'`
