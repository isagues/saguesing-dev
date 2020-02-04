---
title: "Fabricando mi pagina"
date: 2020-02-03T22:09:08-03:00
draft: true
---
## Primer Paso: el por qué
La idea de hacer un blog/pagina personal es el resultado de dos factores <!--mas que nada-->. Primero es epoca de vacaciones y, estando en la playa, sin mucho que hacer surgen ideas de todo tipo. Ademas, siempre suena prometodor crear una pagina web propia.

Por otro lado, en mi tiempo navegando en las redes, pricipalmente reddit<!-- y sus subreddits (sub grupos dentro de la red organizado por temas) de programacion-->, me encuentro con este [post de Michael Lynch](https://mtlynch.io/solo-developer-year-2/). Fue muy interesante leer sobre su experiencia como desarrolador independinte. Aunque lo que mas me llamo la atencion fue su pagina. Es un espacio donde no se limita a hablar de un unico tema. Cuenta desde sus experiencias e ideas respecto a lo laboral hasta comentarios sobre libros que leyo. Asique, sin nada mejor que hacer de mis dias, decidi construir mi propia pagina.

## Segundo Paso: encontrar un camino para empezar

Mi conocimiento sobre desarro web es escaso. Salvando un proyecto de la secundaria de hacer una [pagina web](http://gameofthrones.atwebpages.com/index.html), no tengo ninguna otra experiencia ni concomiento. En consecuencia de esta falta, decidi investigar las tecnologias utilizadas actualmente. Centre mi busqueda a los frameworks. Me parecia una manera practica de iniciar en el tema sin necesidad de volver a revisar a fondo los conceptos basicos de HTML y CSS. 

En mi cabeza tenia presente el nombre Vue.js.<!-- , el cual habia conocido en el blog ya mencionado. Como venia del blog que ya mencione, me habia quedado en la cabeza el nombre Vue.js. -->  Es un framework de javascript que recomendaba Michael para ser usado por un unico desarrolador.  Despues de investigar un poco (pero sin mucho impetud) y no econtrar cual era su funcionalidad o que herramientas aportaba, llegue a la conclusion de que no habia arrancado por el lugar correcto. 

Despues de fallar con Vue, recorde la existencia de Bootstrap. Habia escuchado hablar un poco y parecia una buena herramienta para arrancar. Buscando algunos tutoriales y de que se trataba, enontre otra libreria mas. En vez de achicar las opciones las segui aumentando. <!--Busque algunos tutoriales de como arrancar y cuales eran las principales funcionalidades me encontre con otra libreria o framework (cada vez aparecian mas herramientas).--> Esta era w3.css y prometia ser mas liviano y practico que Bootstrap.
Antes de que las opciones sigan aumentando sin fin, decidi volver a donde habia empezado. Al revisar la pagina que me habia gustado, en busca de algun indicio de que herramienta habia sido utilizada (en el peor de los casos mandarle un mail al creador) encontre en el pie de la pagina: "Powered by Hugo & Coder".

En un principio, pense que seria otro framework mas, que siga ampliando mi lista de opciones. A diferencia de los frameworks ya mencionados, esta era un SSG (Static Site Generator-Generador de Paginas Estaticas). Despues de buscar sobre estos generadores, me di cuenta que podria ser la herramienta correcta. Estos programas permiten fabricar una pagina facilmente, en muy poco tiempo y con una buena variedad de diseños para aprovechar. No podia ser una respuesta tan prometedora, alguna trampa tenia que haber. Estas paginas no estan diseñadas para actualizar su contenido con una alta frecuencia. No tiene la posibilidad de trabajar con bases de datos tampoco. Y, una vez creadas, carecen de una buena interfaz para la actualizacion del contenido. <!-- La idea es que, practicamente, no usan scripts. Esto significa que no son buenas para actulizar contenido constantemente o en tiempo real. Tampoco permiten la interaccion con una base de datos.--> O por lo menos esto fue lo que pude captar.

Esta ultima opcion me parecio la mas adecuada para mi situacion. Usando este generador podria tener mi intento de pagina en poco tiempo y aprovechar el tiempo ganado en el contenido de la misma. Sin muchas ganas de buscar un tema por mi cuenta y, teniendo en cuenta que la pagina de Michael me habia gustado, decidi continuar con mi plagio. Me fije cual habia utilizado y me puse en campaña para utilizar el mismo.

<!-- Hasta aca llegue -->
## Tercera parte: la implementacion

Ya habia elegido el programa, ahora hacia falta ver como implementarlo. Ultimamente utilizo los manuales y la documentacion de las herraminetas nuevas para saber como usarlas. No esperaba que llegue el dia que prefiera usar un manual en vez de ponerme a probar. 

El primer paso fue la instalacion. Primero intente usar los pasos de la documentacion oficial de Hugo, pero estaba orientado para macOS. La version disponible para Ubuntu con apt-get era bastante vieja. POr lo tanto, para bajar la version actual use [esta guia](https://computingforgeeks.com/how-to-install-hugo-on-ubuntu-debian/). Como el comando de curl me bajo otra version (necesitaba la extended), la baje a mano y la instale con el comando que explica la guia. Con Hugo funcionando, siguiendo la guia de oficial y los comando de [Coder](https://github.com/luizdepra/hugo-coder) (el tema utilizado) tuve, en poco tiempo, mi pagina lista. <!-- Pero esta era visible de forma local.  --> Este programa te permite hacer dos cosas con la pagina lista. Se puede generar un servidor local y visualizar la pagina final desde un navegador. O, se puede compilar la pagina y buscar en la carpeta public (direccion default) los archivos HTML y CSS correspondientes.

Con la pagina lista, era momento de subirla a internet. Al buscar informacion para el hosting encontre [GitHub Pages](https://pages.github.com/). Este servicio me solucionaba dos problemas. Primero y principal, el hospedaje de mi pagina de manera gratuita. Por otro lado, resuelve uno de los inconvenientes de las paginas estaticas, la modificacion (agregado y borrado) de contenido. Lo que aporta el sistema de GitHub es actualizar la pagina desde un repositorio. Por lo tanto, la forma de administrar la pagina es la misma que cualquier otro caso de uso de git. 

## Cuarta parte: conclusion

En sintesis, el proceso de hacer la pagina fue bastante simple y llevadero. Al momento de escribir esto, no pude modificar la pagina tanto como me gustaria pero, tampoco le dedique tanto tiempo. Una vez instalado el programa, entendido como funciona y resuleto el problema de donde subir la pagina, creo que es una forma practica de generar paginas. Mientras estas se mantengan dentro de las limitaciones de la plataforma, se puede priorizar el tiempo en publicar el contenido y no perder tanto tiempo en la pagina y todo lo que esta conlleva. Cabe destacar que para la instalacion Hugo necesite usar un poco de mi conocimiento de Linux y para el manejo de GitHub Pages, ayudo la experiencia con la plataforma de GitHub.

