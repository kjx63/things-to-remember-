# git local to remote repository 

### Resources 
https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12386660#questions
https://www.udemy.com/the-web-developer-bootcamp/learn/lecture/4057580#questions



# Inside the terminal 
$ git init 

$ git status 

#From Working Directory to Staging Area 
$ git add . 

#From Staging Area to Local Repository 
$ git commit -m "Initial Commit"

$ git log 


# Create a new repository in the GitHub page. 
1. Create a new repository --> Create repository (green button)
2. copy and paste "git remore add origin https://github.com..................." in the terminal 
3. 
$ git push -u origin master 


# update github 

https://stackoverflow.com/questions/24357108/git-updates-were-rejected-because-the-remote-contains-work-that-you-do-not-have
git push -f origin master

# Clone the git from the github
$ git clone "https:_________.git" 
↑ no "" needed ↑ 

$ cd "name of the file" 
- for example, cd yelpcamp-user-notifications

$ npm install 
↓　Resource from here ↓
https://github.com/nax3t/yelpcamp-user-notifications

# Exclude files 
1. create a file '.gitignore'
2. type the name of the files you want to exculde in the .gitignore file


## fatal: remote origin already exists. 
$ git remote rm origin // originの削除
$ git remote add origin  git@bitbucket.org:ユーザー名/アプリ名.git
$ git push -u origin master

## Create a website on Github Page 
- https://www.youtube.com/watch?v=bwThn0rxv7M
## Add a custum domain in Github Pages 
- https://www.youtube.com/watch?v=hUChaN-VRIc&t=2s
