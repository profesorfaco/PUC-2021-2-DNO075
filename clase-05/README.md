# Infografía digital: HTML, SVG, CSS y JavaScript

### Clase 05 → 13/09/2021

[HTML](https://github.com/profesorfaco/dno075-2021-2/wiki/HTML) y [CSS](https://github.com/profesorfaco/dno075-2021-2/wiki/CSS) son lenguajes de descripción de páginas web. [SVG](https://github.com/profesorfaco/dno075-2021-2/wiki/SVG) es un dialecto de descripción de gráfico vectoriales que podemos usar en páginas web. Pero **[JavaScript](https://github.com/profesorfaco/dno075-2021-2/wiki/JavaScript) no es un lenguaje de descripción, es un lenguaje de programación**.

Como lenguaje de programación, JavaScript, permite escribir secuencias de instrucciones con las que una computadora realizará una tarea determinada desde y para una página web. 

Estas secuencias exigen estructuras más complejas, las que podríamos comenzar a explorar desde:

- [declaración de variables y tipos de datos](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Grammar_and_Types);

- [método `forEach()`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

- [método `sort()`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)

Si sabemos algo sobre declaración de variables y tipos de datos en JavaScript, podríamos reconocer en lo siguiente un arreglo con 6 elementos, siendo cada elemento una cadena de caracteres: 

`var retinal = ["size","value","texture","color","orientation","shape"]`

Si queremos imprimir en consola cada elemento de tal arreglo, podríamos escribir: 

`retinal.forEach(e => console.log(e))`

Si es que queremos ordenar alfabéticamente los elementos en el arreglo antes de imprimirlos, podríamos escribir:

```
retinal.sort();
retinal.forEach(element => console.log(element));
```

En términos laxos, lo que nos ofrece un lenguaje de programación es una serie de acciones que pueden ejecutarse según datos disponibles en un orden conveniente a la interacción.

Dominar un lenguaje de programación toma tiempo de estudio y práctica, pero el tiempo se puede acortar con el uso de *frameworks* y *libraries*:

- una *library* ofrece ingredientes seleccionados y preparados para que cocines un plato específico con el menor esfuerzo posible. 

- un *framework* es una cocina dispuesta para que prepares un tipo de comida específica, con eficacia y eficiencia (una cocina de restaurant que ofrece sushi es distinta de una de restaurant de pasas o parrilladas).

Existen muchas [*libraries*](https://www.tiktok.com/@ifluent/video/6992725135065124102) de Javascript; [Bootstrap](https://getbootstrap.com/) ofrece una que permiten el funcionamiento de componentes tales como:

- [Accordion](https://getbootstrap.com/docs/5.1/components/accordion/)

- [Carousel](https://getbootstrap.com/docs/5.1/components/carousel/)

- [Modal](https://getbootstrap.com/docs/5.1/components/modal/)

- - - - - - -  - 

### Ejercicio

**Escoja una infografia digital publicada en [Reuters Graphics](https://graphics.reuters.com/) para analizarla**. Evite esoger una infografía que despliegue contenidos mediante [interacción con el scroll](http://scrollmagic.io/). 

Para su análisis, tiene que:

- obtener una imagen de la infografía digital completa con el servicio de https://www.site-shot.com/ - Active el *full-size* entre las *Browser options* y defina una escala del 50% en las *Image options*. Si la infografía tiene muchas gradaciones de colores, con fotografías muy detallistas, prefiera la extensión de archivo JPG, en caso contrario mantenga la opción PNG. 

- aprovechar una copia de la imagen recién obtenida para identificar colores más usados en la infografía digital completa; puede seleccionarlos con la ayuda de  [Adobe Color](https://color.adobe.com/es/create/image).

- identificar las fuentes tipográficas con [WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm), una extensión de Google Chrome. Una vez haya identificado la tipografía, busque información sobre ella y una imagen en donde se desplieguen los distintos caracteres. 

- recortar gráficos figurativos, no figurativos y/o mixtos que se estén usando en la infografía.

Una vez hecho este trabajo, completen [la página web que encuentra preparada en esta carpeta de repositorio](https://profesorfaco.github.io/dno075-2021-2/clase-05/).

- - - - - - - - - - 

###### [← CLASE PASADA](https://github.com/profesorfaco/dno075-2021-2/tree/main/clase-04) — [CLASE SIGUIENTE →](https://github.com/profesorfaco/dno075-2021-2/tree/main/clase-06) 

