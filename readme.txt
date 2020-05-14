echo "# testrepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/yorktips/testrepo.git
git push -u origin master

#Use Pull Request to merge to another branch
