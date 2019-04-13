# What is Source Control?
Source control (or version control) is the practice of tracking and managing changes to code. 


# What is Git?
Git is an open-source distributed source code management system. 

# Git works on local
![git local](https://github.com/huaxia-code-school/QA/raw/master/pics/git-basic.png)

# Git works with remote
![git remote](https://github.com/huaxia-code-school/QA/raw/master/pics/git-basic-2.png)

# Lab with git
* ## config git
```
git config --global user.name "Your Name Comes Here"
git config --global user.email you@yourdomain.example.com
```

# create a repo on github
![git remote](https://github.com/huaxia-code-school/QA/raw/master/pics/new-repo.png)

![git remote](https://github.com/huaxia-code-school/QA/raw/master/pics/new-repo-2.png)

**When creating a repository, you can choose to make it public or private. Public repositories are accessible to everyone using GitHub.com, while private repositories are accessible to you and the people you share them with.**

**Never commit personal username/password or any sensitive data into git**

* ## clone repo from remote
![git remote](https://github.com/huaxia-code-school/QA/raw/master/pics/repo-url.png)

findout repo url:

```
git clone ....
```

* ## create a html file, named first.html
```html
<html>
  <body>
    <h1>My 1st html</h1>
  </body>
</html>
```
* ## check git status
```
git status
```

* ## adding to stage 
```
git add first.html
```

* ## check git status again
```
git status
```

* ## commit your file to local repo
```
git commit -m "some message here"
```

* ## change first.html to:
```
<html>
  <body>
    <h1>My 1st/2nd html</h1>
    <h2> My change here <>
  </body>
</html>
```
* ## check git status again
```
git status
```
* ## commit your file to local repo
```
git commit -m "some message here"
```
* ## Push to remote
```
git push
```
