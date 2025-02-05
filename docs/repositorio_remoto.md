# ⚙️Creación del repositorio remoto.
![Texto alternativo](../images/repositorio%20remoto%20imagen%201.jpg)

### 📌Accede a GitHub:
 Ve a GitHub e inicia sesión con tu cuenta. Si aún no tienes cuenta, puedes crear una de forma gratuita.

#### 🔗Crear un nuevo repositorio:

En la página principal de GitHub, haz clic en el botón verde que dice "New" (Nuevo) o dirígete a la URL: https://github.com/new.
#### 📝Rellena los campos necesarios:
Repository name (Nombre del repositorio): El nombre de tu repositorio (puede ser el mismo que tu proyecto local).
#### ⌨️Description (Descripción):
 (opcional) Una breve descripción de tu proyecto.
Public / Private: Decide si quieres que tu repositorio sea público o privado.
No marques la opción de Initialize this repository with a README, ya que ya tienes un repositorio local con archivos.
Haz clic en Create repository.
GitHub te proporcionará un conjunto de URLs para poder usar con Git. Copia la URL HTTPS del repositorio, que se verá algo como esto:

arduino
Copiar
https://github.com/tu-usuario/tu-repositorio.giy
### 📂Paso 2: Crear un repositorio local (si no lo tienes)
Si ya tienes un repositorio local en tu computadora, puedes saltar este paso. Si no:

Inicia tu terminal (o CMD si estás en Windows) y navega a la carpeta donde quieres tener tu proyecto.
Inicializa un repositorio Git en tu proyecto local (si no lo has hecho ya):
bash
Copiar
``` 
git init
```

Añade los archivos al repositorio local:
bash
Copiar
```
git add 
```


Haz un primer commit:
bash
Copiar
```
git commit -m "Primer commit"
```

### 🛜Paso 3: Sincronizar tu repositorio local con el remoto en GitHub
Enlazar el repositorio remoto: Asegúrate de estar dentro de la carpeta de tu proyecto en la terminal. Luego, agrega el repositorio remoto en GitHub usando el siguiente comando (sustituye la URL con la que copiaste previamente):

bash
Copiar
```
git remote add origin https://github.com/tu-usuario/tu-repositorio.git
```

Verifica que el repositorio remoto esté correctamente agregado: Puedes verificar la URL del repositorio remoto con este comando:

bash
Copiar
```
git remote -v
```



Copiar
origin  https://github.com/tu-usuario/tu-repositorio.git (fetch)
origin  https://github.com/tu-usuario/tu-repositorio.git (push)
Sube los archivos al repositorio remoto: Si es la primera vez que estás subiendo tus archivos a GitHub, utiliza el siguiente comando para hacer un push:

bash
Copiar
```
git push -u origin master
```

En algunos casos, si estás usando una rama principal llamada main, el comando sería:

bash
Copiar
```
git push -u origin main
```

Esto subirá tu commit al repositorio remoto en GitHub. La opción -u establece la rama remota como la predeterminada para los futuros push.

### ✅Paso 4: Verifica en GitHub
Ahora, abre el navegador y accede a tu repositorio en GitHub. Verás que los archivos de tu repositorio local se han subido correctamente.
### 🖥️Paso 5: Sincronización futura
A partir de este momento, cada vez que realices cambios en tu repositorio local, debes seguir estos pasos para sincronizarlo con GitHub:

Realiza cambios en tu proyecto y guarda los archivos.
Añade los cambios al área de preparación:
bash
Copiar
```
git add .
```

Haz un commit con los cambios:
```
bash 
```

Copiar
```
git commit -m "Descripción de los cambios"
```

Sube los cambios al repositorio remoto:
bash
Copiar
```
git push origin master
```

O si estás usando la rama main:
bash
Copiar
```
git push origin main
```
