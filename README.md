# Unity2DPractica2
Entorno Unity 2D;

### Introducción a Unity 2D - Físicas y Tilemaps:

## Objetivos:

Crear una escena simple sobre la que probar diferentes configuraciones de objetos físicos en Unity.
Incluye scripts para cada uno de los tipos de objetos anteriores y prográmales eventos OnCollision2D y OnTrigger2D que muestren un mensaje con cada uno de los tipos de evento en consola.

#Ninguno de los objetos será físico.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto1.gif)

**Descripción:

#Un objeto tiene físicas y el otro no.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto1.gif)

**Descripción:

#Ambos objetos tienen físicas.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto1.gif)

**Descripción:

#Ambos objetos tienen físcas y uno de ellos tiene 10 veces más masa que el otro.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto1.gif)

**Descripción:

#Un objeto tiene físicas y el otro es IsTrigger.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto1.gif)

**Descripción:

#Ambos objetos son físicos y uno de ellos está marcado como IsTrigger.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto1.gif)

**Descripción:

#Uno de los objetos es cinemático.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto1.gif)

**Descripción: **

Incorpora elementos físicos en tu escena que respondan a las siguientes restricciones:

#Objeto estático que ejerce de barrera infranqueable

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripción: ** 

#Zona en la que los objetos que caen en ella son impulsados hacia adelante

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripción: ** 

#Objeto que es arrastrado por otro a una distancia fija

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripción: ** 

#Objeto que al colisionar con otros sigue un comportamiento totalmente físico.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripción: **  

#Incluye dos capas que asignes a diferentes tipos de objetos y que permita evitar colisiones entre ellos.


![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripción: ** 

##Sistema de Tilemaps, Actividades a realizar: 

Partiendo de la escena implementada para la tarea de Sprites, selecciona un Sprite que te sirva para representar el personaje.
 En esta ocasión construiremos un mapa de juego, que delimitará la zona en la que tendrá lugar la acción. Para ello:
Obtener assets que incorpores a tu proyecto para la generación de un mapa plano. 

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripcion:** 

#Puedes elegir cualquier otra colección de recursos de tu elección previa consulta con la profesora.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripcion:** 

#Incorporar los recursos que hayas seleccionado en el punto 1 en el proyecto y generar 1 paleta. 

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripcion:** 

#Generar un mapa convencional que represente el entorno y límites de juego.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto2.gif)

**Descripcion:** 

En este ejercicio se trabaja con el uso de varios Tilemaps en la misma escena, cada uno tendrá un orden de renderizado diferente, por lo que puede afectar a su visibilidad.
Si te surgen problemas puedes actuar en el orden de la capa, el orden en la capa. También es conveniente revisar el valor de Z, una ayuda puede ser la visualización 3D del proyecto.

#Crea dos Tilemaps adicionales de obstáculos. Uno puede representar elementos decorativos y otro obstáculos.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto3.gif)

**Descripcion: ** 

#Agrega a la capa de obstáculos la configuración necesaria para que el Tilemap se construya de forma independiente y el obstáculo actúe como tal.


![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto3.gif)

**Descripcion: ** 

#Recupera el Rigidbody2D del objeto y aplica una fuerza vertical al objeto cuando se pulse la tecla que hayas configurado para el salto en el Input. Manager:

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto3.gif)

**Descripcion: ** 

#En este apartado se debe agregar el código que maneja que sólo se salte si el jugador está en el suelo. 
#Para ello se deben agregar una etiqueta al suelo, de forma que nos permita identificarlo y mediante una variable que actuará de flag, activar o desactivar el salto.

![til](https://github.com/Alexiades/UnityPractica2/blob/main/screeshot/Punto3.gif)

**Descripcion: ** 