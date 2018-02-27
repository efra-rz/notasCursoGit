Las **etiquetas** en git nos sirver para marcar puntos en la historia como puntos importantes para evitar tener que memorizar el hash de cada commit

### git tag
**Lista las etiquetas**
Este commando lista las etiquetas en orden alfabético; el orden en el que aparecen no tiene mayor importancia.

### Etiquetas ligras
**git tag v1.1-dev**
Una etiqueta ligera no es más que el checksum de un commit guardado en un archivo, no incluye más información. Para crear una etiqueta ligera, no pasamos las opciones -a, -s, ni -m.


### Etiqueta anotada
**git tag -a -v1.0 -m 'my version 1.0'**
Se guardan en la base de datos de Git como objetos enteros. Tienen un checksum; contienen el nombre del etiquetador, correo electrónico fecha; y tienen un mensaje asociado.

### git tag -l "v1.*
Lista las etiquetas que coincidan con el patron especificado.
