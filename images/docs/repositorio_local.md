# Funciones del repositorio local
### 📌Instalar Git (si aún no lo tienes):

 Si no has instalado Git, puedes hacerlo desde su página oficial. Sigue las instrucciones según tu sistema operativo.

### 📌 Abrir la terminal o línea de comandos: 
Abrir la terminal o línea de comandos:
Dependiendo de tu sistema operativo, abre la terminal o el símbolo del sistema:

En Linux o macOS: abre la Terminal.
En Windows: abre Git Bash o el símbolo del sistema (CMD).
### 📌Crear un directorio para tu proyecto (si aún no tienes uno): 
 Si aún no tienes una carpeta para tu proyecto, crea una utilizando el comando 

 ```
 mkdir
 ```


 


Esto creará una carpeta llamada nombre_del_proyecto y luego te moverás dentro de ella.

### 📌Inicializar el repositorio Git:
 Una vez dentro de la carpeta de tu proyecto, inicializa el repositorio con el siguiente comando:
 ```
 git init
```
Esto creará un subdirectorio oculto llamado .git, que contiene todos los archivos de configuración necesarios para el repositorio.

### 📌Ahora puedes agregar los archivos que quieras al repositorio. Si ya tienes archivos en la carpeta, puedes añadirlos con:
bash
Copiar git add .El punto (.) indica que se añadirán todos los archivos en la carpeta actual. Si quieres añadir archivos específicos, puedes sustituir el punto por el nombre del archivo.

### 📌Hacer el primer commit:
 Después de añadir los archivos, debes hacer un commit para guardar los cambios en el historial de Git. Usa el siguiente comando:

bash
Copiar
```
git commit -m "Primer commit"
```
El mensaje entre comillas debe ser una descripción de los cambios realizados, en este caso, es un mensaje genérico. 