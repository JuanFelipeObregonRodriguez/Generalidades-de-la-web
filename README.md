# Generalidades-de-la-web

resumen por Juan Obregon Rodriguez - 1151657

Todo comienza en la década de los 90, conocida como la época oscura para el diseño web. En sus inicios, el diseño web se basaba en pantallas negras con píxeles monocromáticos que le daban el toque de color. En pocas palabras, no existía el diseño web, ya que el texto dominaba la pantalla.

Hacia 1991 se publicó la primera página web “World Wide Web”, de la mano de Tim Berners-Lee, un físico inglés considerado uno de los grandes creadores de la web. Este sitio web tenía como único objetivo informar qué era la World Wide Web (o red informática global). Hoy, más de 27 años después, podemos garantizar que sus usos sin duda se han multiplicado, y que la evolución del diseño web está más activa que nunca.
 
La invención de los navegadores que permitían mostrar imágenes representa el primer paso en la evolución del diseño web en sí mismo. Las tablas llegaron para otorgarle orden al contenido, siendo la forma que permitía mezclar diseños estáticos y fluidos, a través de tablas dentro de tablas.

De alguna forma las tablas fueron el punto de partida de lo que hoy es el diseño responsivo.

Durante un buen tiempo el método de tablas fué el más utilizado para diseñar páginas web. Y de alguna forma esto produjo una separación entre el diseño y el desarrollo. Mientras los diseñadores creaban los diseños, los desarrolladores buscaban la forma de que funcione, administrando la información en diferentes elementos.

JavaScript llegó para resolver varias de las limitaciones del HTML. Y fué con su aparición que el diseño web ganó dinamismo. Sin embargo, una de las cuestiones más comentadas como punto en contra es que hace más lenta la carga de la página.

Si bien en la actualidad muchos evitan JavaScript para resolver cuestiones que pueden realizarse utilizando CSS, aún se mantiene fuerte tanto en front-end como en back-end. Siendo el front-end lo relacionado a aquello que se ve en un sitio web. Mientras que el back-end garantiza que los datos correctos se envíen al navegador y crean la funcionalidad del sistema.

 


Llegó Flash e impresionó con la posibilidad de efectos visuales, quebrando las barreras que existían en el diseño web del momento. Era el sueño cumplido a través de una sola herramienta. Con un archivo que se envía al navegador para ser mostrado.

Esta época marcó un hito, pero con el tiempo quedó a la vista que los efectos e interacciones no eran abiertos para las búsquedas que indexan HTML, además de consumir poder de procesamiento. Ésto hizo que con el tiempo pierda fuerza.


Cascading Style Sheets – Hojas de Estilo en Cascada

Este lenguaje se hizo popular con una propuesta que separa el contenido de la forma de presentación. Es decir, que en HTML de trabaja el contenido, mientras que en CSS se define el formato y la apariencia.

El CSS paso por un proceso de evolución que demoró varios años hasta lograr sus mejores resultados. Al comienzo la visualización variaba dependiendo el navegador, lo que dificultaba la actividad del desarrollador.

La web 2.0. 2003
Comienza la era de la información basada en los usuarios, y la web 2.0 se hace popular junto con las redes sociales y blogs.

Con interfaces visualmente más agradables y con alta usabilidad, entramos en una fase más evolucionada del diseño web, en el que se comenzó a pensar tanto en los usuarios como en los buscadores. El foco en la experiencia de navegación mediante el uso del diseño web.

teniedo en cuenta la cronologia, la web se ha vuelto en un adan de complejidad, con ella se desarrollaron nuevas arquitecturas, las cuales cambiaron su enfoque tradicional por la masividad del internet y la migracion masiva de la informacion a la nube. la arquitectura basica se constituye de los siguientes componentes:

Arquitectura básica de una aplicación web
Para que un sitio o aplicación web funcione mostrándose al público es necesaria una arquitectura que disponga como mínimo los siguientes elementos:

El navegador: Representa el concepto de cliente realizando peticiones solicitando recursos a diferentes servidores web a través de URL.

El Servidor: Almacena de forma organizada la estructura de la información del sitio web para servir los contenidos en relación a las peticiones del navegador.

El protocolo http: Es el protocolo basado en TCP/IP a través del cual el navegador realiza peticiones al servidor para que este responda.

HTML: Es el formato básico de los documentos que componen las páginas web, está basado en etiquetas y sirve para estructurar la forma de mostrar los contenidos de las páginas.

CSS: Las hojas de estilo en cascada sirven para favorecer estéticamente los elementos y contenidos estructurados a través de las etiquetas HTML, dotándoles de personalidad en cuanto a su diseño, forma y colores.

Tecnologías del lado del cliente o del lado del servidor
Además de reunir los requisitos anteriores básicos para funcionar, un sitio o aplicación web puede crearse utilizando diferentes tecnologías que se dividen en dos grandes categorías:

Tecnologías de cliente: Son aquellas que permiten crear interfaces de usuario y establecer comunicación con el servidor basadas en HTML, CSS y JavaScript, en este caso, el navegador actúa como intérprete.

Tecnologías de servidor: Permiten implementar comportamientos de la aplicación web en el servidor, los lenguajes de programación más utilizados son Java EE, .NET, PHP, Ruby on Rails, Python, Django, Groovy, Node.js, etc…

Arquitecturas web de contenido estático o dinámico
Se dice que el contenido que muestra una determinada página o sitio web al completo es contenido estático cuando no permite la interacción del usuario de ninguna forma, por el contrario las páginas que invitan a interactuar con el visitante a través de diferentes elementos como formularios, botones, mapas, etc… ofrecen contenido dinámico.

Cliente estático y servidor estático: En este modelo el navegador hace una petición al servidor mediante el protocolo http, el servidor transforma la URL a ruta de disco y devuelve el fichero al navegador que lo dibuja o renderiza mostrando la estructura de la página en HTML y su contenido como fotos y vídeos, también la estética de su diseño gracias a los estilos CSS.

En este caso no existe ningún tipo de interacción utilizando JavaScript, el servidor devuelve siempre los mismos recursos, así que desde este punto de vista la web es estática.

Cliente estático y servidor dinámico: Este modelo se compone de 3 capas, ya que intervienen por un lado el navegador y el servidor web, pero también una base de datos asociada a este último.

Cuándo el servidor recibe una petición, devuelve contenido del disco o ejecuta código para generar el recurso dinámicamente, este código normalmente realiza consultas a la base de datos para recuperar la información, generando la página HTML y contenidos de forma dinámica.

Cliente dinámico y servidor estático: En contenido está alojado en el disco duro del servidor de forma estática, pero el cliente es dinámico porque las páginas incluyen código JavaScript que se ejecuta en el navegador.

Este código JavaScript puede realizar acciones y efectos gráficos, mostrar y ocultar información, desplegar elementos interactivos, adaptar los contenidos, etc…

Cliente dinámico y servidor dinámico: Se combinan los conceptos de los dos casos anteriores, utilizando JavaScript para efectos gráficos  y comportamientos interactivos, pero también para realizar peticiones en segundo plano (AJAX) y aplicaciones de página única con API REST.

JavaScript se puede utilizar para no tener que recargar completamente la página al pulsar un enlace, realizando peticiones al servidor web en segundo plano (ocultas al usuario). Cuando llega al navegador el resultado de la petición, el código JavaScript actualiza solo las partes necesarias de la página.

A esta técnica se la conoce como AJAX (Asynchronous JavaScript And XML) y mejora mucho la experiencia de usuario ya que al realizar las peticiones el servidor puede devolver fragmentos de HTML generados dinámicamente, recursos estáticos en disco como imágenes, PDF, mostrar errores, cambiar colores, información estructurada en XML o JSON, etc…

Tecnologías estándar del lado cliente
El W3C (World Wide Web Consortium) es una comunidad internacional que desarrolla estándares abiertos que aseguran el crecimiento de la web a largo plazo, tales como HTML5&CSS, Scripting and AJAX, normas de accesibilidad, gráficos, audio y vídeo, web semántica, XML y muchos más.

HTML: (Hypertext Markup Languaje) proporciona la información estructurada en secciones, párrafos, título, imágenes, etc… la versión actual el HTML5, y ofrece muchas librerías avanzadas para la inserción de contenidos multimedia, canvas, comunicaciones y concurrencia.

CSS: (Cascading Style Sheets) se encarga de la distribución de los elementos y su estilo con colores, tipos de letra, fondos, efectos, etc…en documentos HTML, XML, SVG o incluso interfaces de usuario de otras tecnologías.

Scripting: Gracias al scripting las páginas pueden programarse con distintos lenguajes de script, aunque principalmente se utiliza JavaScript, que modifica la página gracias a su capacidad de ejecutar código cuando se interactúa con ella.

JavaScript inicialmente era un lenguaje interpretado pero actualmente también se ejecuta con máquinas virtuales en los navegadores aumentando la velocidad de ejecución y eficiencia de memoria. Es de tipado dinámico y funcionalmente orientado a objetos (basado en prototipos).

Existen multitud de bibliotecas (APIS) para el desarrollo web y de aplicaciones, pero las más utilizadas son JQuery y Underscore.js.

DOM: Es el modelo de objetos del documento (Document Object Model) y consta de una librería (API) para  manipular el documento HTML cargado en el navegador, permitiendo la gestión de eventos, o la inserción y eliminación de elementos.

Tecnologías de servidor

Los estándares son muy importantes en los navegadores web (cliente) ya que es importante que la web sea compatible con cualquier dispositivo, sin embargo estos estándares no son necesarios en el servidor, por que cada organización desarrollará su servidor con la tecnología que crean conveniente.

En el servidor se utilizan tecnologías propietarias o abiertas para el desarrollo de aplicaciones web, existen multitud de ellas, entre ellas las más usadas son PHP, Java EE y ASP.NET, y las menos usadas Ruby on Rails, Grails (Groovy), Django (Phyton), Perl, ColdFusion, hay muchas más, pero entre ellas comentamos a continuación las más destacadas.

Java EE: Es una tecnología basada en Java desarrollada por una coalición de empresas lideradas por Oracle, IBM, Red Hat, etc… muy utilizada a nivel empresarial, la mayoría de implementaciones y herramientas para desarrollo son software libre, y existen comunidades de desarrolladores y empresas que realizan complementos.

PHP: Es una tecnología con lenguaje propio, desarrollada por PHP Group y con licencia libre. Es la tecnología de lado de servidor con la que se han implementado más servidores en Internet, es multiplataforma y se integra normalmente con Apache y MySQL en entornos Linux gracias a un paquete llamado LAMP.

ASP.NET: Se trata de una versión evolucionada del ASP clásico, está integrada en la tecnología .NET de Microsoft junto con el lenguaje C#, tiene licencia propietaria y para plataformas Windows y una comunidad de desarrolladores má limitada que otras alternativas.

Bases de datos
Las bases de datos más populares y utilizadas para el desarrollo de aplicaciones web son las bases de datos relacionales. Hay muchas bases de datos relacionales tanto comerciales como de software libre como MySQL, Derby, Oracle, MS SQL Server, PostgreSQL.

Actualmente el sistema gestor de bases de datos más utilizado es MySQL, es multiplataforma y está desarrollado en C, tiene licencia de código abierto GPL y consta de una herramienta interactiva para hacer consultas y crear bases de datos, en su conjunto se ha hecho muy popular en el desarrollo web.

