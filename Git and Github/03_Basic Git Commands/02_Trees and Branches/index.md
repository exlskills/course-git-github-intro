### Moving On to Trees

Now lets say that you want to jump onto a new part of your project, but do not want to mess up your in production  working code.

In this case, you can create a branch that contains all the previous work as a template of sorts.

### Reasons for using branches

* Mess with your code base without worrying about creating errors in production version
* Play with other open-source codebases without messing up the production version
* Create a new checkpoint or template
* Work on different parts of app in continuous fashion

### Commands for branches

```
git branch 'name of branch'
```
This makes a new branch for you to work on.

```
git checkout 'branchname'
```
Allows you to go an use a different branch (think switching between branches)

```
git merge 'name of branch you want to merge'
```
This merges two branches so that they become one again.
