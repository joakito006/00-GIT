# 00-git
# Primeros pasos con git

## Comandos

git init    #inicio el proyecto de git (1 sola)

git status        #me muestra el estado actual del trabajo

    #cree/modifiqué el archivo ejem.txt

git add ejem.txt     #agrego archivos al proximo commit
git add .            #agrega TODOS los archivos (excepto los del .gitignore) al próximo commit

git commit -m "mensaje del commit"        #crea un commit (una versión nueva del programa)


git commit --amend                #permite corregir el último commit SI NO SE SUBIO A LA NUBE


git log            #permite ver el registro de commits (fecha, autor, commit message)

git push    #subo mis nuevos commit a la nube


## .gitignore
Es un archivo que va en la misma carpeta donde arranca el proyecto (ubicación raíz)
Permite aclarar qué archivos quiero que mantenga fuera del control de git
Se pueden usar comodines (*.pdf), una instrucción por línea
