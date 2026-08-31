# 1. Inicializa el repositorio local de Git
git init

# 2. Agrega el archivo README.md a la lista de cambios
git add README.md

# 3. Guarda el primer commit
git commit -m "Initial commit: Add profile README"

# 4. Cambia el nombre de la rama principal a main
git branch -M main

# 5. Vincula tu carpeta local con tu repositorio de GitHub 
# (Copia la URL exacta que te dio GitHub al crear el repositorio)
git remote add origin https://github.com/TU-USUARIO/TU-USUARIO.git

# 6. Sube el archivo a GitHub
git push -u origin main
