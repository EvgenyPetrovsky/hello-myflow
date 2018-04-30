# hello-myflow

Setting up simple workflow using branches and pull-request

1. clone repo and create local branch

```sh
git clone https://github.com/EvgenyPetrovsky/hello-myflow.git
git checkout -b add-gitignore
git push origin HEAD
```

2. make changes in the branch, commit and push them

```sh
git add <file>
git commit -m "<your-commit-message>"
git push origin HEAD
```

3. prepare branch for merge

```sh
git pull --rebase origin master
git git push origin HEAD
```
