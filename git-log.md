### git log
Muestra el historial de commits

**Algunas opciones para git log**

`git log --oneline --graph`

--online: nos muestra el historial abreviado.

--graph: añade un pequeño gráfico ASCII mostrando el historial de ramificaciones y uniones. 

Esto es un ejemplo de como personalizar la salida del historial con el formato que indiquemos.

`git log --pretty=format:"%h - %an, %ar : %s"`
