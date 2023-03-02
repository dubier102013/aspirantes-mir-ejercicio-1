pwd
mkdir ejercicios
mv ejercicios ../
cd ..
code .
cd ejercicios
cd ejercicio1
touch README.md
git config --global user.name "Dubier Molina"
git config --global user.email dubier102013@gmail.com
cd ..
git init
git add .
git commit -m "Versión Inicial"
cd ejercicio1
open .
git add REAME.md
git commit -m "Agrega solución primer ejercicio"