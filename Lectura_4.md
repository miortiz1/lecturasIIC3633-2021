# Content-Based Recommendation Systems
La lectura de esta semana comienza con una introduccion a los sirstemas recomendadores basados en contenido, los cuales para funcionar deben intentar representar 
las caracteristicas de un obejto en tablas o matrices, las cuales luego pueden ser usadas para comparar objetos entre si y junto con el feedback de un usuario
recomendarle nuevos items. Siguiendo la misma idea se nos introduce un concepto clave para los sistemas content-based, y son los perfiles de usuario, los cuales
almacenan grandes cantidades de información de un usuario, tanto como feedback explicito como implicito basado en sus interacciones.

 Más adelante en el texto se nos presentan varias estrategias para un sistema recomendador basado en contenido, explicando su funcionamiento y para que tipo de 
datos es mas efectivo.

 Creo que es muy interesante la forma de recomendar que se nos plantea en la lectura, sin embargo creo que existe un problema muy grande que no se puede pasar por alto:
la complejidad de cada item en general es demasiado grande y no pueden ser capturadas todas sus características para hacer una correcta recomendación. Si bien
para items simples puede arrojar buenos resultados, unas simples golosinas podrían llegar a ser dificiles de recomendar, ¿es posible representar un sabor con numeros, o 
simplemente recomendará todas las golocinas por ser dulces?, y como ese ejemplo se pueden encontrar facilemte muchos otros. O por ejemplo para textos, a pesar de que se
explican distintas estrategias en la lectura de como mejorar las recomendaciones de textos, todas estas llegan a ser insuficientes. Como se explica en el texto, no hay forma 
de distinguir si un chiste es divertido o no, si una historia es interesante o no, si un escrito tiene informacion relevante o no.

  Lo que si me pareceria interesante es usar este sistema en conjunto con collaborative filtering, de modo que partiendo de los gustos de otros usuarios se puedan reducir 
los items para recomendar y luego aplicar sobre estos un sistema basado en contenido para ver que item puede ser mejor para nuestro usuario, aunque está la desventaja que
puede ser muy consumidor en terminos de recursos y quedaria probar que tanto aumenta la correctitud de las recomendaciones.
