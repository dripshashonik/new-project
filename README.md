mkdir new-project
cd new-project
git init
echo "text" > README.md
git commit -m "init"
git add README.md
git push
git checkout -b development
echo "text2" > README.md
git commit -m "init2"
git add README.md
git checkout main    
git merge development
git commit
git push

