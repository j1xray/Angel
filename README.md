mkdir Trojan
mkdir data
mkdir modules
mkdir config
mkdir status

touch .gitignore

git add .
git commit -m "Adding repo Structure for Angel"
git remote add origin https://github.com/j1xray/Angel
git remote set-url origin https://username:Token@github.com/username/nameofrepo
git branch -M main
git push origin main
