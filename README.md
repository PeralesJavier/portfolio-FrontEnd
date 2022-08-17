# Create a new repository on the command line

echo "# portfolio-FrontEnd" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/PeralesJavier/portfolio-FrontEnd.git

git push -u origin main


# Push an existing repository from the command line

git remote add origin https://github.com/PeralesJavier/portfolio-FrontEnd.git
git branch -M main

git push -u origin main
