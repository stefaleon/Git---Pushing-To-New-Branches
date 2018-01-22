# Git - Pushing To New Branches

## Initial

```
$ git init
Initialized empty Git repository in C:/Code/Git - Pushing To New Branches/.git/
```
```
$ git add .
```

```
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md
```
```
$ git commit -m 'initial'
[master (root-commit) f96afb7] initial
 1 file changed, 20 insertions(+)
 create mode 100644 README.md
```

```
$ git remote add origin https://github.com/stefaleon/Git---Pushing-To-New-Branches.git
```

```
$ git push -u origin master
```




## New Branch

```
$ git checkout -b newbranch
Switched to a new branch 'newbranch'
M       README.md
```

```
$ git add .
```

```
$ git commit -m 'new branch'
```

```
$ git push -u origin newbranch
```




## Another Branch

```
$ git checkout -b anotherbranch
Switched to a new branch 'anotherbranch'
```

```
$ git add .
```

```
$ git commit -m 'another branch'
```

```
$ git push -u origin anotherbranch
```
