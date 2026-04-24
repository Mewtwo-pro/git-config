# Comandos Git utilizados en el Script

### Inicialización y Remoto

```
git init

```
```
git remote add origin <url>
```

### Gestión de Ramas
```
git checkout -b <nombre_de_rama>
```
### Flujo de Trabajo (Add & Commit)
```
git add <archivo1> <archivo2> ...
```
```
git commit -m "mensaje"
```
### Publicación
```
git push -u origin <nombre_de_rama>
```
### borrar las credenciales
```
rm ~/.git-credentials
```
```
rm ~/.config/git/credentials
```
### Configuración de Credenciales
```
git config --global credential.helper store
```