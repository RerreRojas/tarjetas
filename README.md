# TarjetasComponent
Este componente de Vue.js representa un formulario para ingresar información sobre una tarjeta y muestra una vista previa de la tarjeta utilizando los datos ingresados.

## Estructura del Proyecto

El proyecto está dividido en tres secciones principales:

* Formulario para Ingresar Datos: Permite al usuario ingresar y seleccionar información sobre la tarjeta.
* Vista Previa de la Tarjeta: Muestra una representación visual de la tarjeta utilizando los datos ingresados.
* Estilos: Define el aspecto visual del formulario y de la tarjeta.
  

### Explicación del Código
#### Formulario de Entrada
* Título de la tarjeta: Selecciona el título de la tarjeta (por ejemplo, "Visa Classic Crédito").
* Chip SRC: Selecciona la imagen del chip.
* Número: Ingresa el número de la tarjeta.
* Fecha de expiración: Ingresa la fecha de expiración de la tarjeta.
* Propietario: Ingresa el nombre del propietario de la tarjeta.
* Tipo de tarjeta SRC: Selecciona el tipo de tarjeta (por ejemplo, "Visa").
#### Vista Previa de la Tarjeta
* Título de la tarjeta: Se muestra en un encabezado `<h3>`.
* Chip SRC: La imagen del chip se muestra utilizando la directiva v-bind para enlazar la fuente de la imagen (:src).
* Número: Se muestra en un encabezado `<h2>`.
* Fecha de expiración: Se muestra la fecha de expiración ingresada.
* Propietario: Se muestra el nombre del propietario en el pie de página (<footer>).
* Tipo de tarjeta SRC: La imagen del tipo de tarjeta se muestra utilizando la directiva v-bind para enlazar la fuente de la imagen (:src).

##### Estilos

* Formulario: El formulario está estilizado con un diseño de rejilla para alinear las etiquetas y los campos de entrada.
* Tarjeta: La tarjeta tiene un fondo oscuro, con texto en color blanco y se utiliza un diseño de columna flexible para alinear los elementos.
  
#### Dependencias

Este componente no tiene dependencias adicionales aparte de Vue.js.

#### Ejecución

Para ejecutar este componente, asegúrate de tener un proyecto Vue.js configurado. Copia el código proporcionado en tu archivo .vue y asegúrate de que las imágenes referenciadas en chipSRC y tipoTarjeta existan en la ruta especificada.


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
