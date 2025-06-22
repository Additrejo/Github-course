# GIT & Github Course (Windows)
Repositorio de aprendizaje sobre GIT & Github.


## 📑 Índice.
#### ¿Qué es Git y GitHub?.
- [¿Qué es Git?](#¿-qué-es-git-?)
  - [Características principales](#-características-principales)
  - [🛠Usos comunes](#️-usos-comunes)
- [¿Qué es GitHub?](#-qué-es-github)
  - [ Funciones destacadas](#-funciones-destacadas)
  - [Relación entre Git y GitHub](#-relación-entre-git-y-github)


#### Instalación y configuración GIT.
- [Recursos](#recursos)
- [Downloads](#downloads)
- [Instalacion GIT](#instalacion-git)
   - [Instalación por descarga de archivo](#instalación-por-descarga-de-archivo)
   - [Instalación en consola](#instalación-en-consola)
   - [Comprobar instalación de GIT](#comprobar-instalación-de-git)
##### Comandos GIT.
- [Comandos básicos](#comandos-básicos)
   - [git --version](#git---version)
   - [git --help](#git---help)
- [Comandos básicos de navegación en la Terminal Linux, CMD, PowerShell, Git Bash](#comandos-básicos-en-la-terminal-linux-cmd-powershell-git-bash)
##### Configuración GIT.
- [Configuración de GIT](#configuración-de-git)
   - [Configuración Global (Nombre de usuario, Email)](#configuración-global)
##### Iniciando con GIT.
- [git init](#git-init)
- [Ramas en git (Branches)](#ramas-en-git)
   - [Git status](#git-status)
- [Git add y commit](#git-add-y-commit)
   - [Git add](#git-add)
   - [Git commit](#git-commit)
- [Git log](#git-log)
---

## recursos

* [Git Website](https://git-scm.com/) - Website Git, Download
* [Git Book](https://git-scm.com/book/en/v2) - Git Book.
* [Git Documentation](https://git-scm.com/doc) - Git Documentation.

---

## downloads

 * [Windows](https://git-scm.com/downloads/win)
 * [Linux](https://git-scm.com/downloads/linux)
 * [macOS](https://git-scm.com/downloads/mac)

---

# 📘 ¿Qué es Git y GitHub?

## 🔧 Git

**Git** es un sistema de control de versiones distribuido creado por **Linus Torvalds** en 2005. Permite llevar un historial completo de los cambios realizados en un proyecto, facilitando el trabajo colaborativo y el seguimiento de versiones.

### ✅ Características principales:
- Controla el historial de versiones del código.
- Facilita la colaboración entre varios desarrolladores.
- Permite trabajar con ramas (branches) para desarrollo paralelo.
- Es rápido, seguro y eficiente.

### 🛠️ Usos comunes:
- Seguimiento de cambios en proyectos de software.
- Reversión de errores a versiones anteriores.
- Coordinación en equipos de desarrollo.

---

## 🌐 GitHub

**GitHub** es una plataforma en la nube para alojar repositorios Git. Proporciona herramientas para colaborar, revisar código, gestionar proyectos y automatizar procesos.

### 🚀 Funciones destacadas:
- Hospedaje de repositorios públicos y privados.
- Pull requests para revisión y fusión de código.
- Issues para gestión de tareas y bugs.
- Forks para crear copias independientes de proyectos.
- Integración con CI/CD (GitHub Actions).

### 🤝 Relación entre Git y GitHub:
- **Git** se usa localmente para gestionar versiones de código.
- **GitHub** permite almacenar ese código en línea y trabajar en equipo.

> 🔗 Git es la herramienta. GitHub es la plataforma donde compartes tu trabajo con el mundo.

---

## Instalacion GIT  
La instalación puede hacer de dos formas.
1. Instalador por descarga de archivo.
2. Comando en la terminal.

## Instalación por descarga de archivo.
* Descargando el archivo y ejecutandolo con doble click.

## Instalación en consola
* Agregar en el simbolo del sistema de nuestro ordenador el siguiente comando. 

```bash
winget install --id Git.Git -e --source winget
```

Se desplegará la siguiente ventana de instalación.

![image](https://github.com/user-attachments/assets/caf889f4-7dc0-4c6d-a8fa-ec187927825d)

Finalizará la instalación.

![image](https://github.com/user-attachments/assets/49d690ab-36e2-4bdb-8063-33f9cfa1084a)

## Comprobar instalación de git
Ingresar el siguiente comando en la terminal
```bash
git
```
Saldrá lo siguiente junto con algunos comandos:  

![image](https://github.com/user-attachments/assets/6e09e8ce-bb90-407e-981a-1da6f35cf583)

---

## Comandos básicos.  
Estos son algunos comandos en terminal básicos para cualquiere terminal compatible con GIT.


### *git --version*  
_"El comando git --version sirve para mostrar la versión actual de Git que tienes instalada en tu sistema."_
```bash
git --version
```  
También podemos usar un comando más simple.
```bash  
git -v
```
![image](https://github.com/user-attachments/assets/182253f9-a29d-4843-a489-fe970eca827d)

### *git --help* 
_"El comando git --help sirve para mostrar la ayuda general de Git o la documentación de un subcomando específico"._
```bash  
git --help
```
![image](https://github.com/user-attachments/assets/43ef83a5-0011-40a6-b2f4-adbce88c7654)

## Comandos básicos en la Terminal Linux, CMD, PowerShell, Git Bash.

Esta es una tabla con los comandos equivalentes entre (Linux, CMD, PowerShell, Git Bash) :

| Acción                          | Linux/macOS       | CMD (Windows)     | PowerShell         | Git Bash           |
|---------------------------------|-------------------|-------------------|--------------------|--------------------|
| Listar archivos                 | `ls`              | `dir`             | `ls` (alias)       | `ls`               |
| Cambiar de directorio          | `cd carpeta`      | `cd carpeta`      | `cd carpeta`       | `cd carpeta`       |
| regresar carpeta                | `cd ..`           | `cd ..`           | `cd ..`            | `cd ..`            |
| Mostrar ruta actual            | `pwd`             | `cd`              | `pwd`              | `pwd`              |
| Limpiar la pantalla            | `clear`           | `cls`             | `Clear-Host` o `cls` | `clear` o `cls`    |
| Eliminar un archivo            | `rm archivo.txt`  | `del archivo.txt` | `Remove-Item archivo.txt` | `rm archivo.txt`   |
| Copiar un archivo              | `cp a.txt b.txt`  | `copy a.txt b.txt`| `Copy-Item a.txt b.txt` | `cp a.txt b.txt`   |
| Mover o renombrar un archivo   | `mv a.txt b.txt`  | `move a.txt b.txt`| `Move-Item a.txt b.txt` | `mv a.txt b.txt`   |
| **Crear una carpeta**          | `mkdir nueva_carpeta` | `mkdir nueva_carpeta`   | `mkdir nueva_carpeta` o `New-Item -Type Directory -Name nueva_carpeta` | `mkdir nueva_carpeta` |

#### 💡 Recomendaciones

- **Git Bash** es ideal si vienes de Linux o estás usando Git en Windows.
- **PowerShell** es más potente que CMD y permite scripts avanzados.
- **CMD** es básico pero sigue siendo útil para tareas simples.

---

## Configuración de GIT
### Configuración global. 
   Esta configuración afectará a nivel usuario en la pc en la que nos encontremos.
   * **Nombre de usuario:**  
     Estableceremos un nombre de usuario para GIT a nivel global en nuestra PC. 

```bash  
git config --global user.name "[tu_usuario]"
```
En la carpeta de usuario de nuestra PC creará el siguiente archivo.  

![image](https://github.com/user-attachments/assets/432e49f3-cea5-4341-b022-d6f78de38fca)  

Al abrirlo con un block de notas nos mostrará lo siguiente:  

![image](https://github.com/user-attachments/assets/79e75383-e181-4d38-9f29-4fa005e50599)

   * **Email de usuario**  
     Estableceremos un Email de usuario para nuestra PC.

```bash  
git config --global user.email "[tu_email]"
```
Al abrir el archivo de nuevo aparecerán nuestras credenciales de usuario.  

![image](https://github.com/user-attachments/assets/1681ea38-b15a-4d77-8f1e-d80724ae99b6)

Con esto tendremos las configuraciones necesarias para usar GIT.

---

## git init
._El comando git init se utiliza para inicializar un nuevo repositorio de Git. Es uno de los primeros comandos que se ejecutan cuando comienzas un nuevo proyecto con Git._


Dirigirse a la carpeta raiz del directo a tráves de CMD y escribir el siguiente comando:  

```bash  
git init
```

Por ejemplo
```bash  
C:\Users\addi_\Documents\GIT>git init
```
A continuación nos mostrará un mensaje que se ha creado un repositorio vacío.  
![image](https://github.com/user-attachments/assets/a4509bc4-e84f-4f40-ab0d-5ad37d33b7a4)  

_Git crea un subdirectorio oculto llamado .git dentro del directorio actual. Este subdirectorio contiene todos los archivos necesarios del repositorio — incluyendo historial, configuración y metadatos — que permiten a Git rastrear los cambios en los archivos del proyecto._

Si nos dirigimos a la carpeta veremos que se ha creado el archivo .git.  
![image](https://github.com/user-attachments/assets/26d87983-b104-415c-bf3c-b3651c69c83d)

_¿Cuándo usar git init?
Cuando estás empezando un nuevo proyecto y quieres usar Git para control de versiones.
Cuando tienes un proyecto existente que no está bajo control de versiones y quieres empezar a usar Git._

---

## Ramas en GIT  
_Una rama es una línea de desarrollo independiente. Te permite trabajar en nuevas características, correcciones o ideas sin afectar el código principal (generalmente llamado main o master)._

Para nombrar una a la rama principal es necesario agregar el siguiente comando:  
```bash  
git branch -m main
```
Aparentemente no aparece un cambio pero el nombre de la rama se actualizó a main.  
![image](https://github.com/user-attachments/assets/1af0e088-8a30-4e4b-a1fb-fd5c6fc15b70)

## Git status
_El comando git status se usa para ver el estado actual del repositorio, es decir, te muestra qué archivos:  
**- Han sido modificados.**  
**- Están listos para ser guardados (staged).**  
**- No están preparados para el commit.**  
**- Son nuevos y no están siendo rastreados por Git (untracked)**_  
**- Saber en que rama me encuentro.**

*Crear un archivo prueba en la carpeta dónde se creó el [git init](#git-init).

Escribirmos el siguiente comando en la dirección de la carpeta.
```bash  
git status
```  
![image](https://github.com/user-attachments/assets/6c8ac580-0ed8-4d54-8076-7fbf13bb15e4)  
Aparece la leyenda "On branch main" lo cual nos indica que estamos en la rama principal, así como el documento que hemos creado. 

---

## git add y commit  

### Git add
_El comando git add se utiliza para agregar archivos al área de preparación (staging area) en Git. Es un paso previo antes de guardar los cambios de forma definitiva con git commit._

Veremos que estamos en la rama principal y tenemos un archivo de prueba marcado en rojo.
Al momento ese archivo aun no está agregado a GIT, así que lo agregaremos con el comando:  

```bash  
git add helloworld.py
```

para verificar que se agregó correctamente consultamos de nuevo con [git status](#git-status):  
```bash  
git status
```
![image](https://github.com/user-attachments/assets/20d73e72-d9bb-4c6e-849c-ea30291aeae3)  
Podremos darnos cuenta que ya está en verde, esto significa que ya el stage ya lo tomó en cuenta pero aun es necesario hacer commit.

### Git commit

Agregamos el siguiente comando:  
```bash  
git commit
```
Enseguida nos aparecerá la siguiente ventana:  
![image](https://github.com/user-attachments/assets/e3840145-155d-4727-bc11-3d9886c6b3fd)  

Es necesario agregar un nombre en la parte superior del mensaje:  
![image](https://github.com/user-attachments/assets/e69b1a5f-0353-4185-a709-e487db7da006)  

Existe otra forma de hacerlo con el siguiente comando.
```bash  
git commit -m "[Mensaje al crear el commit]"
```
En este caso usaremos el siguiente:  
```bash  
git commit -m "Este es mi primer commit"
```
Dandonos como resultado lo siguiente:  
![image](https://github.com/user-attachments/assets/9cfd0e1f-e197-4bec-9d13-5d5f05568eb9)  
Si analizamos podremos ver la rama en la que se encuentra, su identificador unico, así como los archivos que se han modificado.  

Al revisar de nuva cuenta con [git status](#git-status) podremos ver lo siguiente:  

![image](https://github.com/user-attachments/assets/451b3fd4-30fc-4e43-ba3d-4d890f3f2d26)

---

## git log.
Para verificar si el commit se ha realizado ocupamos el comando:
```bash  
git log
```
![image](https://github.com/user-attachments/assets/e8a47499-ebdc-4f5c-a6fa-f5a991188a0f)  
En el podemos ver el  hash, su ubicación, autor, correo y fecha, ademas del mensaje que dejamos en el commit.  

Al crear otro archivo por ejemplo un Helloworld2.py y agregamos el comando [git status](#git-status) podremos ver como el nuevo archivo está en letras rojas con el mensaje sobre poder pasar el arhivo de forma local al stage.  
![image](https://github.com/user-attachments/assets/ad07086c-ef7b-4364-9306-23cedc5f1fa6)


para añadirlo es encesario agregar el comando  [git add](#git-add) + el nombre del archivo.
```bash  
git add helloworld2.py
```
Aparentemente no hará nada, lo que tenemos que hacer es hacer commit con el comando [git commit](#git-commit).
```bash  
git commit -m "Este es mi segundo commit"
```
![image](https://github.com/user-attachments/assets/c35bcb03-9ebc-47b4-9910-efcdd1105df7)  
Nos apareccerá que un arhichivo ha sido modificado y se ha insertado.  
```bash  
git log
```
Para comprobar agregamos nuevamente el comando  el comando [git log](#git-log)  


![image](https://github.com/user-attachments/assets/f11a9894-6a2d-49ab-90f7-d5e726eeb8c7)  
apareciendo los dos archivos con sus respetivos datos mencionados anteriormente.

Si modificamos el archivo y agregamos de nuevo el comando [git status](#git-status) 
```bash  
git status
```
podremos darnos cuenta que de nueva cuenta aparece en rojo, esto significa que el archivo ha sido modificado y no ha sido actualizado..  
![image](https://github.com/user-attachments/assets/62629063-84bb-412d-b337-cf49417c571c)  

Si editamos un segundo archivo y agregamos de nuevo el comando podemos ver como ahora aparece el segundo archivo sin guardar.  
![image](https://github.com/user-attachments/assets/8474ba88-2008-4c3d-b9ea-a37691e634bf)


