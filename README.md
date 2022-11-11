
- **Practicas**
  - [00Requerimientos](https://github.com/Launch-X-Latam/MisionFrontEnd/blob/main/01%20-%20INTRO/practicas/1.-requerimientos.md)
  - [01HTML](https://github.com/Jalx1000/JAL-Launch-X-Latam/tree/01HTML)
  - [02CSS](https://github.com/Jalx1000/JAL-Launch-X-Latam/tree/02CSS)
  - [03JS](https://github.com/Jalx1000/JAL-Launch-X-Latam/tree/03JS)

**Crear una rama vacía con Git**

[Para crear una rama sin padre](https://noviello.it/es/como-crear-una-rama-vacia-en-el-repositorio-de-git/)
Podemos usar la opción de --orphanlínea de comando para crear una nueva rama sin padres:
```git checkout --orphan new-empty-branch``` 
El comando anterior creará una nueva rama sin padres. Ahora puede eliminar los archivos del directorio de trabajo, para que no se comprometan con una nueva rama:
```git rm -rf .``` 
Ahora puede agregar nuevos archivos a esta nueva rama, confirmarlos y enviarlos al repositorio remoto de git.