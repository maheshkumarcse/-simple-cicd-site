echo "# -simple-cicd-site" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/maheshkumarcse/-simple-cicd-site.git
git push -u origin main
