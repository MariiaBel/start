# Start for projects

---

## Do before working with your project

git config --global.name "github name"
git config --global.email "github registration email"

Check you ssh keys:
ls -al ~/.ssh 

For generation new key:
ssh-keygen -t rsa -b 4096 -C "your_email"

Add new key to your keys storage:
ssh-add ~/.shh/your_key_name (usually id_rsa)

Add new key to github:
Open file key_name.pub -> copy all words -> new shh in github setting keys

Check working with github
ssh -T git@github.com

-----------
 
## Helper
 
Checking repositories:
git remote -v

Add new repository:
git remote add remoteRepoName git@github.com:name_repo/name_project.git


