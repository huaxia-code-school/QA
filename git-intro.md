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

# Questions and Answers

### Q: What is the purpose of Config git?

A: In software development, multiple developers will commit to same repo. The git config for `user.name` and `user.email` is to identify who made the changes. The `user.name` do not need match your Github username, the `user.email` does not need to match the your Github email either.

### Q: Clone repo from remote: what remote?

A: A remote usually means the repo on the server. In our context is the repo on Github.com. There are some other source control providers also provide git repo service: Bitbucket, Azure Devops and so on. In addition, can a local repo has multiple remote? The answer is **yes**. For now it is too complicate for us. Let's focus on 1 remote right now.

### Q: Create a html, named first.html: where? Github or vscode? And how?

A: Here means on your local working directory. Once you cloned a repo, a sub folder will be created. It is your **working directory**. The sub folder by default has the same name with your remote/github repo. In the sub folder you will find a `.git ` folder, that is your **local repo**. See the first picture you will get better understanding. 
How to create the first.html? Use vscode is a good way. Actually anyway is OK. As long as the file is under your **working directory**.
Can you create the html directly on Github.com? The answer is **Yes**. 

### Q: When I typed in `code .` It opened vscode. 

A: Yes, it open vscode and directly open the folder where you typed the command. Then you can create html using vscode. 

You can get the same by open vscode first, then use the menu File -> Open Folder ... and select the folder where you typed the command.

### Q: Check git status: which status? Github repo status or vscode status?

A: It is your working directory status. It shows which files are changed, which files are in staging and so on. 

The command need to be run under the **working directory**. The following command also need run under **working directory**: 
* `git commit`
* `git add` 
* `git push`
* `git pull`



