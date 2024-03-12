git clone https://github.com/briandy28/my_web_page
cd ~/my_web_page
git checkout -b new_features
git config --global user.email briandy.talaigua@udea.edu.co
git config --global user.name briandy28
git add aboutme.html
git commit -m "Agrega nuevo archivo aboutme.html"
git add styles/*
git commit -m "Agrega nuevo directorio (styles) y en esteun archivo aboutme.css"
git add aboutme.html
git commit -m "Modifique la linea 7 y mi informacion de las redes sociales en el archivo aboute.html"
git add index.html
git commit -m "Agregue nuevo archivo index.html"git log --oneline
git revert 4695cac
git checkout main
git merge new_features
git push origin main
