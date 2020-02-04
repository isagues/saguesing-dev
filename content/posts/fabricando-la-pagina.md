---
title: "Fabricando mi pagina"
date: 2020-02-03T22:09:08-03:00
draft: true
---
## Primer Paso: el por qué
La idea de hacer un blog/pagina personal es el resultado de dos factores <!--mas que nada-->. Primero es epoca de vacaciones y, estando en la playa, sin mucho que hacer surgen ideas de todo tipo. Ademas, siempre suena prometodor crear una pagina web propia.

Por otro lado, en mi tiempo navegando en las redes, pricipalmente reddit<!-- y sus subreddits (sub grupos dentro de la red organizado por temas) de programacion-->, me encuentro con este [post de Michael Lynch](https://mtlynch.io/solo-developer-year-2/). Fue muy interesante leer sobre su experiencia como desarrolador independinte. Lo que mas destaco es su pagina la cual, cuenta tanto sus experiencias e ideas respecto a lo laboral, como comentarios sobre libros que leyo. Asique, si nada mejor que hacer de mis dias, decidi construir mi propia pagina.

## Segundo Paso: encontrar un camino para empezar

Mi conocimiento sobre desarro web es escaso. Salvando un proyecto de la secundaria de hacer una [paginan web](http://gameofthrones.atwebpages.com/index.html), no tengo ninguna otra experiencia ni concomiento. Debido a mi falta de conocimiento, decidi buscar las tecnologias utilizadas actualmente. Mi busqueda estaba mas que nada centrada en frameworks. Me parecia una manera practica de iniciar en el tema sin tener que volver a revisar a fondo los conceptos basicos de HTML y CSS. 
<!-- Hasta aca llegue -->
Como venia del blog que ya mencione, me habia quedado en la cabeza el nombre Vue.js. Es un framework de javascript que recomendaba el autor por ser conveniente para un unico desarrolador.  Despues de investigar un poco (pero sin mucho impetud) y no econtrar cual era su funcionalidad o que herramientas aportaba, llegue a la conclusion de que habia arrancado por cualquier lado. 

Desdpues de fallar con Vue, me acorde de la existencia de Bootstrap. Habia escuchado hablar un poco y parecia una buena herramienta para arrancar. Busque algunos tutoriales de como arrancar y cuales eran las principales funcionalidades me encontre con otra libreria o framework (cada vez aparecian mas herramientas). Este era w3.css y prometia ser mas liviano y practico que Bootstrap.
En este momento fue donde dije, por que no mejor revisar la pagina que me habia gustado y ver si habia algun indicio de que herramienta habian usado (en el peor de los casos mandarle un mail al creador). Para mi fortuna, en el fondo de la pagina decia " Powered by Hugo & Coder ".

Esperaba que sea otro framework mas que siga ampliando mi lista de opciones. Pero fue un poco mejor, resulta que es un Generador de Paginas Estaticas (SSG en ingles ). Despues de buscar un poco que era lo que significaba ser un SSG me di cuenta que podria ser la herramienta correcta. Estos programas permiten fabricar una pagina facilmente, en muy poco tiempo y con una buena variedad de temas para aprovechar. Ahora viene la pregunta es, ¿cual es la trampa?. La idea es que, practicamente, no usan scripts. Esto significa que no  son buenas para actulizar contenido constantemente o en tiempo real. Tampoco permiten la interaccion con una base de datos. Esto fue lo que pude captar despues de unas busquedas rapidas.
 
En sintesis, decidi ir por el camino del generador de paginas. Lo que me permitio fabricar un intento de pagina, en cuestion de horas. Y para esto decidi continuar con mi plagio al blog de Michaek usando el mismo generador y el mismo tema que me habia gustado

## Tercera parte: la implementacion

Una vez que me decidi con Hugo empece a ver como implementarlo. Ultimamente estoy leyendo manuales y documentacion para saber como usar las herramientas que necesito, no esperaba que llegu este dia. Para utilizar Hugo es necesario instalarlo primero.

Primero intente usar los pasos de la documentacion oficial, pero estaba orientado para macOS. La version disponible para Ubuntu con apt-get era bastante vieja. Para bajar la version actual use [esta guia](https://computingforgeeks.com/how-to-install-hugo-on-ubuntu-debian/). Como el comando de curl me bajo otra version, la baje a mano (la version extended) y la instale con el comando que explica la guia. Con Hugo funcionando, siguiendo la guia de oficial y los comando de [Coder](https://github.com/luizdepra/hugo-coder) (el tema utilizado) tuve, en poco tiempo, mi pagina lista. Pero esta era visible de forma local. 

Al buscar informacion para el hosting encontre [GitHub Pages](https://pages.github.com/). Este servicio me solucionaba dos problemas. Primero y principal, el hospedaje de mi pagina de manera gratuita. Por otro lado, resuelve uno de los inconvenientes de las paginas estaticas, la modificacion (agregado y borrado) de contenido. Lo que aporta el sistema de GitHub es actualizar la pagina desde un repositorio. Por lo tanto, la forma de utilizarlo es la misma que cualquier otro caso de uso de git y la pagina muestra los contenidos depositados en la rama de master. 

## Cuarta parte: conclusion

En sintesis, el proceso de hacer la pagina fue bastante simple y llevadero. Al momento de escribir esto, no pude modificar la pagina tanto como me gustaria pero, tampoco le dedique tanto tiempo. Una vez instalado el programa, entendido como funciona y resuleto el problema de donde subir la pagina, creo que es una forma practica de generar paginas. Mientras estas se mantengan dentro de las limitaciones de la plataforma, se puede priorizar el tiempo en publicar el contenido y no perder tanto tiempo en la pagina y todo lo que esta conlleva.


