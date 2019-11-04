1-** npm init -y **
2- npm i gh-pages
3-add homepage to package.json : 
"homepage": "https://Mansour-Tumeh@github.io/website",
4- add inside script :
 "deploy": "gh-pages -d dist"
 5 create a new repo and name it website
6 create .gitignore file and add node_modules 
7 git init 
8 git add .
9 git commit -m "first commit"
10 git remote add origin https://github.com/farhanmatar/farhan-website
11 git push -u origin master
12 npm run deploy