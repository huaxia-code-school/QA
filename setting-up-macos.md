# Setting up your MacOs
## Sign up Github
* If you already have a github account send it to lihe.chen@gmail.com
* Otherwise Go to https://github.com/ , sign up a account with your email address, send the username to lihe.chen@gmail.com

## If you do not have Chrome, download and install it:
https://www.google.com/chrome/

## Recommended: install oh-my-zsh:
Document: https://github.com/robbyrussell/oh-my-zsh

## Most MacOs have nodejs installed. If you already have nodejs installed, directly go to Install http-server
To verify nodejs installation:
```
node -v
```
If you see a version, means installed.

![node -v](https://github.com/jenac/html-school/raw/master/pics/node-v.png)

## Install nvm
Document: https://github.com/creationix/nvm
Command: 
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
```
or
```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
```

### Test nvm works:
* Open shell, run command:
```
nvm list-remote
```
The following should show (a little bit difference):

![nvm list](https://github.com/jenac/html-school/raw/master/pics/nvmlist.png)


## Install nodejs
* In shell:
```
nvm install v10.15.3
```
* Set nodejs to use:
```
nvm use v10.15.3
```

### Test nodejs works:
```
node -v
```

## Install http-server
```
npm i -g http-server
```
![install http-server](https://github.com/jenac/html-school/raw/master/pics/installhttpserver.png)


## Install vscode: **recommended** most popular code editor
* Download and install vscode:
https://code.visualstudio.com/

## Serve your first html
* create your project folder, e.g `C:\projects`
```
mkdir C:\projects
```
* create your first html using vscode and save to `C:\projects`

### Run http-server under `C:\projects`
```
cd C:\projects
http-server
```
![run http server](https://github.com/jenac/html-school/raw/master/pics/http-server-run.png)

Open chrome and browse to the url showed in red circle

![browse](https://github.com/jenac/html-school/raw/master/pics/browse.png)

