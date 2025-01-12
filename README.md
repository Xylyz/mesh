TAREAS:

1. Encontrar la manera de meter el código spawn en la escena de cada mob con el objetivo de vaciar la escena world, de lo contrario será un infierno leer si sigo metiendo más mobs. NOTA: Creo que es mejor no hacerlo debido a que puede ser confuso en caso de que ocurra un error de spawneo según los stages. Igual era una idea para facilitar la lectura del código del stage. Creo que tocará hacerlo con comentarios para mantener todo limpio. NOTA2: Creé un mob spawner scn para limpiar el código del stage. Ahora todos los mobs estarán conectados a esa escena para aparecer en el estage. Tal vez sirva para un stage 2, pero por lo pronto así sirve.
2. Cómo spawnear el mismo mob cinco veces para que parezca un escuadrón.
   
- NOTA 1: Ya pude hacer los "escuadrones", pero activo cada escuadrón con la muerte de unidades. Tal vez lo mejor sea activar con un timer y no por muerte de mob.
- NOTA 2: Hoy (dic 28) no se avanzó absolutamente nada. Intenté resolver el problema de los escuadrones dentro de la escena stage, pero no pude spawnearlos en un orden deseado. Siempre aparecen todos y al mismo tiempo, sólo algunas veces, molestando con el código, podía hacer reaparecer el primer mob. No era lo deseado. Tal vez, una aproximación distinta a cómo estoy construyendo las escenas sea necesario. Encontré algo que se llama components, veré tutoriales y leeré algo en la documentación; lo poco que he visto podría servir incluso para resolver el problema 3.
- NOTA 3: Ahora los mobs salen en escuadrones sin ningún error por parte del inspector.
  
3. Implementar el código de hp en el jugador (no estoy seguro si implementarlo en los mobs o hacerlos morir de un solo tiro o crear proyectiles con diferentes cifras de daño). Hecho junto con un flash hit como feedback para el jugador.
4. Parallax. Hice uno sencillo con assets gratuitos.
5. Decidí hacer primero dos oleadas de enemigos para tener algo más "jugable".
6. Mañana debería mejorar las oleadas, quizá tener un máximo de cuatro. Las dos primeras con embestida, otras dos con enemigos que disparen proyectiles. Decidí poner los mobs ya hechos que sólo embisten para concentrarme un poco en el sistema de drops.
7. Diferentes tipos de enemigos. No se ha realizado nada todavía.
8. Sistema de Power-Ups. Por lo menos ya dejan caer el power-up, falta es tener un sistema mucho más flexible que permita agregar diferentes tipos de power-ups. Tal vez con resources o polymorphism, o quizá ambos, tengo que aprender bien cómo hacer eso.
9. Picking "enemy" parts.
10. Boss.
11. Cambio al stage 2.
12. Nuevas partes de enemigos.
13. La meta es llegar al cambio de jugabilidad a un A-RPG donde se mejora al personaje con las partes de los enemigos conseguidos en el SHMUP. Aquí se conseguirán mejoras para la nave y se hará un tease para la construcción de una nueva nave.
