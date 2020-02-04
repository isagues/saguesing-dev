---
title: "Fabricando mi pagina"
date: 2020-02-02T22:09:08-03:00
draft: true
---
## Primer Paso: el por qué
La idea de hacer un blog/pagina personal es el resultado de dos factores mas que nada. Primero es epoca de vacaciones y, estando en la playa, sin mucho que hacer surgen ideas de todo tipo. Ademas, siempre suena prometodor hacer una pagina web propia.

Por otro lado, en mi tiempo navegando en las redes, pricipalmente [reddit](https://www.reddit.com/) y sus subreddits (sub grupos dentro de la red organizado por temas) de programacion, me encuentro con este [post de Michael Lynch](https://mtlynch.io/solo-developer-year-2/). Fue muy interesante ver su experiencia como desarrolador independinte pero lo que mas destaco es su pagina en la cual, cuenta tanto sus experiencias e ideas respecto a lo laboral, pero tambien, tiene un espacio para comentar un libro que leyo. Asique, si nada mejor que hacer de mis dias, decidi construir mi propia pagina.

## Segundo Paso: encontrar un camino para empezar

Salvando un proyecto de la secundaria de hacer una [paginan web](http://gameofthrones.atwebpages.com/index.html), mi conocimiento de diseño web es practicamente nulo. Esto no me podia frenar a la hora de crear la pagina por lo tanto, me puse a investigar que tecnologias se usaban ahora. Mas que nada me interesaba saber que frameworks habia. Me parecia una manera practica de meterme en el tema sin tener que volver a revisar a fondo los conceptos basicos de HTML y CSS. 

Como venia del blog que ya mencione, me habia quedado en la cabeza el nombre Vue.js. Es un framework de javascript que recomendaba el autor por ser conveniente para un unico desarrolador.  Despues de investigar un poco (pero sin mucho impetud) y no econtrar cual era su funcionalidad o que herramientas aportaba, llegue a la conclusion de que habia arrancado por cualquier lado. 

Desdpues de fallar con Vue, me acorde de la existencia de Bootstrap. Habia escuchado hablar un poco y parecia una buena herramienta para arrancar. Busque algunos tutoriales de como arrancar y cuales eran las principales funcionalidades me encontre con otra libreria o framework (cada vez aparecian mas herramientas). Este era w3.css y prometia ser mas liviano y practico que Bootstrap.
En este momento fue donde dije, por que no mejor revisar la pagina que me habia gustado y ver si habia algun indicio de que herramienta habian usado (en el peor de los casos mandarle un mail al creador). Para mi fortuna, en el fondo de la pagina decia " Powered by Hugo & Coder ".

Esperaba que sea otro framework mas que siga ampliando mi lista de opciones. Pero fue un poco mejor, resulta que es un Generador de Paginas Estaticas (SSG en ingles ). Despues de buscar un poco que era lo que significaba ser un SSG me di cuenta que podria ser la herramienta correcta. Estos programas permiten fabricar una pagina facilmente, en muy poco tiempo y con una buena variedad de temas para aprovechar. Ahora viene la pregunta es, ¿cual es la trampa?. La idea es que, practicamente, no usan scripts. Esto significa que no  son buenas para actulizar contenido constantemente o en tiempo real. Tampoco permiten la interaccion con una base de datos. Esto fue lo que pude captar despues de unas busquedas rapidas.
 
En sintesis, decidi ir por el camino del generador de paginas. Lo que me permitio fabricar un intento de pagina, en cuestion de horas. Y para esto decidi continuar con mi plagio al blog de Michaek usando el mismo generador y el mismo tema que me habia gustado

## Tercera parte: la implementacion

Instale Hugo usando la [pagina oficial](https://www.gohugo.io/) y una [wiki](https://computingforgeeks.com/how-to-install-hugo-on-ubuntu-debian/) para tener la ultima version en ubuntu. 


