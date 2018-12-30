# Requisitos práctica final

Diseña una página web compuesta por tres columnas. En la primera de ellas, te vamos a pedir que introduzcas una serie de enlaces que representarán un menú de opciones. Más bien representarán unos anclas a los contenidos de la columna central.

# Columna central

En la columna central, vamos a incluir un listado de posts de un blog ficticio. Cada post deberá incluir lo expuesto en el prototipo mostrado. Por lo que, tendrás que jugar con todos los detalles en las tipografías, en la disposición, en el layout, en los márgenes. No sólo pienses técnicamente, piensa en los detalles y en cómo replicar con éxito la estructura. Identifica y haz las relaciones oportunas con los conceptos aprendidos.

# Header y footer

En la tercera columna, volvemos a poner referencias a posts, en este caso destacados. Esta vez, la disposición de estos cambia. Intenta identificar la mejor manera de realizar la composición estructural con HTML + CSS. Créalos teniendo en cuenta el orden de representación. Incluye logos, copyrights como símbolos, etc. 

# Hoja de ruta:

CSS básico --> creación de un archivo externo a través de style.css
Recopilación de todos los estilos en este archivo

CSS:

Resetear el documento mediante:

* {
    margin: 0;
    padding: 0;
}

Creación de los contenedores que van a conseguir realizar las tres columnas:

>#todo #izquierda y #derecha

Utilizamos la propiedad float para colocar los diferentes contenedores

Problemas encontrados: con la altura de cada uno de los elementos y con el footer, no se ve en todos los navegadores de forma correcta

> Diferenciamos con otro color el header para que realmente se vea la diferencia

Creamos los enlaces y los botones a través de listas desordenadas y ```li````
A través de :hover conseguimos que esta propiedad nos resalte los enlaces con diferentes colores para que se vea que lo estamos tocando con el ratón.

Utiulizamos la propiedad border-radius en diferentes ocasiones para redondear los elementos, en el caso de las imágenes hasta llegar a coseguir una imagen redonda. Muy util para los apartados de empresa.

A través del siguiente enlace: https://htmlcolorcodes.com/es/nombres-de-los-colores/ , conseguimos información sobre diferentes colores con nombres para CSS, una variedad de uso de colores. 

Aunque en este caso el proyecto no cuenta con ninguna calidad en cuanto a colores, se puede utilizar algún que otro recurso para conseguir que los colores sean más adecuados como en el caso de coolors: https://coolors.co

Introducimos una tipografía diferente en el apartado h1

Para el copyright usamos el ```&#169```

Se puede usar el recurso de FontAwesome para conseguir iconos en nuestros proyectos.




