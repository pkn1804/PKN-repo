# testing using GIT on Udemy
Just a repo for testing

# clone repo:
git clone https://github.com/pkn1804/PKN-repo.git <target_folder>

# status (use in git folder)
git status

# stage file
git add <filename>

# commit (-m = Message) (still only local after this)
git commit -m "Initial commit"

# push (thos example: master = branch)
git push origin master

#diff - shows changes for modified file
git diff <filename>

#show history
git log

#checkout (restore. hash from log, 'master' is remote version)
git checkout <commit_hash>


#tricks
I have a cool git command for you.

In your project, run this command to see a really nice log.

git log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'
I've been using this really cool git command for a long time called git lg. It's like git log but wayyyyyyyy better.

Here's the free code snippet, and what your .gitconfig file would look like when you add it to your global git config

https://codingforeverybody.com/snippets/git-lg