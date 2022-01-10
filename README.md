# my-empty-repo

In this repository, I write the command line instruction for create new Github repository.

## HTTPS

HTTPS: https://github.com/matteoghera/my-empty-repo.git

### …or create a new repository on the command line

```powershell
echo "# my-empty-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/matteoghera/my-empty-repo.git
git push -u origin master
```

### …or push an existing repository from the command line

```powershell
git remote add origin https://github.com/matteoghera/my-empty-repo.git
git branch -M master
git push -u origin master
```

###…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

## SSH

SSH: git@github.com:matteoghera/my-empty-repo.git


### …or create a new repository on the command line

```powershell
echo "# my-empty-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:matteoghera/my-empty-repo.git
git push -u origin master
```

### …or push an existing repository from the command line

```powershell
git remote add origin git@github.com:matteoghera/my-empty-repo.git
git branch -M master
git push -u origin master
```

###…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.