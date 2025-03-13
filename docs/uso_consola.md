# 🗃️Uso de la Consola: Navegación y Creación de Directorios y Archivos

![alt text](../images/Uso_consola_imagen2.png)

La consola o terminal es una herramienta fundamental para interactuar con el sistema operativo de manera eficiente. Permite ejecutar comandos para realizar diversas tareas sin necesidad de una interfaz gráfica. A continuación, se describen los conceptos básicos sobre cómo navegar por el sistema de archivos y crear directorios y archivos.

### 🛜Navegación en la Consola

Para moverse entre directorios en la consola, se utilizan los siguientes comandos:

🟣pwd (Print Working Directory): Muestra el directorio actual en el que se encuentra el usuario.
``` 
pwd
``` 

🌟```ls```  (List): Lista los archivos y directorios dentro del directorio actual.
``` 
ls
``` 
🌟```ls -l``` : Muestra detalles adicionales como permisos, propietario y tamaño.

🌟```ls -a``` : Muestra archivos ocultos.

🟣```cd```  (Change Directory): Permite cambiar de directorio.
``` 
cd nombre_del_directorio
``` 
🌟```cd ..``` : Retrocede un nivel en la jerarquía de directorios.

🌟```cd ~``` : Regresa al directorio principal del usuario.

🌟```cd /``` : Va al directorio raíz.

### 📂Creación de Directorios y Archivos

Para gestionar archivos y carpetas desde la consola, se utilizan los siguientes comandos:

🔵```mkdir``` (Make Directory): Crea un nuevo directorio.
``` 
mkdir nombre_del_directorio
``` 
🌟```mkdir -p ruta/del/directorio``` : Crea la estructura completa de directorios si no existen.

🔵```touch``` : Crea un nuevo archivo vacío.
``` 
touch nombre_del_archivo
``` 
🔵```echo``` : Permite crear archivos con contenido de manera rápida.
``` 
echo "Contenido" > archivo.txt
``` 
🔵```cat``` : Muestra el contenido de un archivo.
``` 
cat archivo.txt
``` 
🔵```rm```  (Remove): Elimina archivos y directorios.
``` 
rm archivo.txt
``` 
🌟```rm -r directorio```: Elimina un directorio y su contenido.

🌟```rm -i archivo.txt``` : Solicita confirmación antes de eliminar.

