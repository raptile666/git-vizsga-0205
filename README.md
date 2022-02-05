git clone https://github.com/szpeter992/git-vizsga-0205.git
cd git-vizsga-0205
git branch console
git checkout console
git add .
git commit -m 'app.js módosítva a dokumentum szerint'
git add .
git commit -m '.css módosítva a dokumentum szerint'
git add .
git commit -m 'README és .gitignore hozzáadása'
git checkout main
git merge console
git remote add vizsga https://github.com/raptile666/git-vizsga-0205.git
git push -u vizsga main