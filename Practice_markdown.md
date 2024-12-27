## Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a git repo.

If we wanted to create a git repo in a new project we' create the folder and the initialize that repo using `git init`

```

mkdir /workspace/tmp/new-project
cd /workspace/tmp/new-project
git init
touch README.md
code README.md
# make changes to README.md

git commit -a -m "Add README.md

```

## Cloning

We can clone in three ways: HTTPS,SSH,Github CLI

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```

### HTTPS

```sh
git clone https://github.com/farman-arefin-outlook/Github_Foundations.git
```

## Commits

## Branches

## Remotes

## Stashing

## Merging

## Add

When we want to stage changes that will be included in the commit . We can use the . to add all possible files.

## Reset

Reset allows you to move Staged changes to be unstaged. This is useful when you to revert all files not to be commited.

```
git add .
git reset

```

> git reset will revert a git add.

## Status

Git status shows you what files will or will not be commited.

```
git status

```
