# git

### make a new repository

`git init`

- Make a "New Repository" on github.com, and copy and paste the `git remote add origin` line into your terminal to link your local repository with the one online 

### save your code

`git add .`

`git commit -m "my message"`

`git push origin master`

### note

The `.gitignore` file lets you add specific files and folders that you dont want saved on github. Always add the `/node_modules` folder!!!

### copy a repo

`git clone {url.git}`: copy an entire repository to your local computer. Then you can `cd` into it, and run `npm install` to install all the dependencies.
