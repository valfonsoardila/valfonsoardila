# Git Flow <img src="https://github.com/VictorArdila/VictorArdila/assets/89551043/25d307e3-ef06-41e0-8cb1-a979f4f130ac" alt="GitFlow" width="35" height="35">
Para trabajar con el esquema de mis repositorios lo trabajo asi: 
`Cambiar nombre de ramas al iniciar proyecto`
Inicializa git
```bash
git init
```
Agrego los cambios locales
```bash
git add .
```
Hago el commit
```bash
git commit -m "Creacion de estructura inicial"
```
Creo la rama 
```bash
git branch nombre
```
Reviso que se hay creado correctamente
```bash
git branch 
```
Selecciono la rama dev que ya fue creada
```bash
git checkout nombre
```
Le asigno al repo local la url del repo remoto para sincronizarlo
```bash
git remote add link.git
```
Envio los cambios
```bash
git push origin nombre
```

`Para eliminar un archivo en el repo remoto`
```bash
git rm -r --cached __pycache__
```
```bash
git commit -m "Eliminando __pycache__ del repositorio remoto"
```
```bash
git push origin nombre_de_tu_rama
```
