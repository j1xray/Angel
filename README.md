mkdir 
mkdir data
mkdir modules
mkdir config
mkdir status

touch .gitignore

git add .
git commit -m "Adding repo Structure for Angel"
git remote add origin https://github.com/j1xray/Angel
git remote set-url origin https://j1xray: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@github.com/j1xray/Angel
git branch -M main
git commit -m "Leave a note here that will help you remember what your code is doing at any particular time"
git push origin main
