# Proyecto 1: Una experiencia en WebXR
## Descripción de componentes
En este projecto, uso varios componentes:
* scripts: ejecutan codigo en javascript, como las fisicas, los controles, y muchas cosas más. le dan interactibidad a la experiencia.
Uso algunas dependencias, como controller-listener, player-movey raycaster-extras.
* eventos: se usan para escuchar el input de los controles
* a-entity: conforman la escena. las paredes, luces, mesa y dartos estan hechos de estos componentes. uso a-plane, a-light, y a-box.
  con recursos exteriores como texturas y modelos 3d se pueden crear objetos facilmente
* a-camera: esta dentro de un a-entity y tambien es otro. Pero este es la camara, y la entidad padre es el jugador.
## Compatibilidad 
Las pruebas de compatibilidad se han realizado en las gafas de metaquest2, los demas dispositivos no son compatibles.
Los controles solo reciben input de las gafas, por lo tanto no es posible hacerlos en otros dispositivos facilmente.
## Ventajas de la experiencia en WebXR
* Accesible: 
Ya que esta en navegador, es facilmente accesible, cualquier persona puede acceder al link de glitch o a github pages para jugar tu juego
* Dessarrollo rapido  
En el dessarrollo puedes hacer cambios e instantaneamente ver los resultados, ya que se usa html, no hay necesidad de hacer ninguna build. Por lo tanto el desarrollo 
es mucho más rápido.
* Contenido Instantaneo. 
Sin instalacion ni tiempo de carga excesivo, se puede jugar a mi experiencia de vr, haciendo mucho mas facil de convencer a alguien para que la pruebe. 
