# Git Clase 1
## ¿Que es git?
Es un sistema de control de versiones, se define como control de versiones a la gestión de los diversos cambios que se realizan sobre los elementos de algún producto o una configuración del mismo.

Git nos proporciona las herramientas para desarrollar un trabajo en equipo de manera inteligente y rápida por ejemplo una página web o una aplicación realizada por un grupo de trabajo.

Algunas de las características más importantes de Git son:

- Rapidez en la gestión de ramas, debido a que Git nos dice que un cambio será fusionado mucho más frecuentemente de lo que se escribe originalmente.
- Gestión distribuida; Los cambios se importan como ramas adicionales y pueden ser fusionados de la misma manera como se hace en la rama local.
- Gestión eficiente de proyectos grandes.
- Realmacenamiento periódico en paquetes.

## Los 3 estados de git

- Working directory
- Staging Area
- .git directory (Repository)

## Flujo de Trabajo básico
1.  Modificas uno o una serie de archivos en tu directorio de trabajo.
2.  Preparas los archivos, añadiéndolos en tu área de preparación.
3.  Confirmas cambios,toma los archivos tal y como están en el área de preparación y almacena es copia de manerapermanetne en tu directorio Git.

## Comándos básicos e Instalación

Para instalar git en windows es necesario ir a la siguiente web y descargar el programa gratuito en https://git-scm.com/ y despues pasar a configurarlo

Revisar version de git
```
git --version
```
Configurando git por primera vez
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
git config --global core.editor nano
git config --list
```
Revisar el valor de email
```
git config user.name
git config user.email
```
Comando de ayuda
- git help verb
- git verb --help

Ejemplo:
```
git help config
git config --help
```
Esta línea fue creada en la rama master.
