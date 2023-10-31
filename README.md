# This is my end to end project

# check if git is already config 
git remote -v

# To remove git old config
git reomte rm origin

# To config git
git config --global user.name "monit-009"
git config --global user.email "monitdatascience@gmail.com"
git remote add origin https://github.com/monit-009/project-environment-setup.git
...
git remote -v
# git initilize the git
...
git init
...
git add file_name
git add . #add all files
git commit -m "message"
git push origin branch_name
git pull origin branch_name
