# gittest
A sample for how to use the github and transform files

# create a new repository on the command line
echo "# gittest" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/mawenlong2016/gittest.git
git push -u origin master

# push an existing repository from the command line
git remote add origin https://github.com/mawenlong2016/gittest.git
git push -u origin master


