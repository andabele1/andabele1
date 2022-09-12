**###Arquitectura Monolítica vs Microservicios🎀**

**###¿QUÉ ES LA ARQUITECTURA MONOLITICA?**

Una arquitectura monolítica es un modelo tradicional de un programa de software que se compila como una unidad unificada y que es autónoma e independiente de otras aplicaciones. 

** ###¿QUÉ ES LA ARQUITECTURA DE MICROSERVICIOS?**
 es un método de arquitectura que se basa en una serie de servicios que se pueden implementar de forma independiente. Estos servicios tienen su propia lógica empresarial y base de datos con un objetivo específico. La actualización, las pruebas, la implementación y el escalado se llevan


![diagrama](https://www.google.com/search?q=monolitico+vs+microservicios&source=lnms&tbm=isch&sa=X&ved=2ahUKEwj64tub8f75AhXnQzABHdOjBVsQ_AUoAXoECAEQAw&biw=1599&bih=812&dpr=1.2#imgrc=iTB9quS2UDpBFM)


![XE](https://user-images.githubusercontent.com/111757782/188523109-831f3797-f2e3-4aae-bf6f-28b225b0e6dc.png)
 
**###CARACTERISTICAS DE LA ARQUITECTURA MONOLITICA**
Arquitectura monolitica
Son aplicaciones autosuficientes.
Realizan de punta a punta todas las operaciones para terminar una tarea.
Son por lo general aplicaciones grandes.
Son por lo general silos de datos privados, cada instalación administra su propia base de datos.
Todo el sistema corre sobre una solo plataforma.

**###CARACTERISTICAS DE ARQUITECTURA DE MICROSERVICIOS **
Alto nivel de desacoplamiento.
Nombres únicos.
En caso de que den algún problema, pueden iniciarse en otra máquina de forma que así no perderemos ningún dato ni información.
Su implementación, escalado y actualización se hace de manera independiente.
Están enfocados para desarrollarse en función de cada negocio o de cada cliente.


**###VENTAJAS ARQUITECTURA MONOLITICA**
Fácil para un equipo pequeño de desarrollo iniciar un nuevo proyecto y ponerlo en producción rápidamente.
Autonomo al momento de decision 
Las aplicaciones Monolíticas son rápidas, debvido a la simplicidad 
Toda la funcionalidad está disponible desde el principio de la aplicación, por lo que puede ejecutar todas las pruebas necesarias sin depender de nada más.
**
**###DESVENTAJAS ARQUITECTURA MONOLITICA****
Dado que todo el software es una sola pieza, significa que se usa el mismo conjunto de tecnologías para todo, eliminando el uso de otras tecnologías.
Escalar una aplicación monolítica significa escalar toda la aplicación usando recursos para la funcionalidad que puede que no necesite ser escalada.
Las aplicaciones monolíticas son fáciles de ejecutar en equipos pequeños, pero a medida que crece la aplicación y crece el equipo de desarrollo, se vuelve cada vez más difícil dividir el trabajo sin comprometer la funcionalidad.
Cualquier mínimo cambio en la aplicación implicará realizar una compilación del todo el artefacto y con ello una nueva versión que tendrá que ser administrada.
A menos que se tenga alta disponibilidad, si la aplicación Monolítica falla, falla todo el sistema, quedando totalmente inoperable.
En proyectos muy grandes, puede ser abrumador para un nuevo programador hacer un cambio en el sistema.

**###VENTAJAS ARQUITECTURA DE MICROSERVICIOS**
Al tratarse de servicios autónomos, se pueden desarrollar y desplegar de forma independiente. 
Un error en un servicio no debería afectar la capacidad de otros servicios para seguir trabajando según lo previsto.
Se pueden usar diferentes tecnologías y lenguajes de programación. Lo que permite adaptar cada funcionalidad a la tecnología más adecuada y rentable.
El reducido tamaño de los microservicios permite un desarrollo menos costoso, así como el uso de “contenedores de software” permite que el despliegue de la aplicación se pueda llevar a cabo rápidamente.
El mantenimiento es más sencillo y barato que en otras arquitecturas.
Se pueden utilizar funcionalidades típicas (autenticación, trazabilidad, etc.) que ya han sido desarrolladas por terceros.

**###DESVENTAJAD ARQUTECTURA DE MICROSERVICIOS **
Al tener cada microservicio sus propios recursos y bases de datos, consumen más memoria y CPU.
Al crear la arquitectura, se necesita más tiempo para poder fragmentar los distintos microservicios e implementar la comunicación entre ellos.
Los microservicios requieren desarrolladores experimentados con un nivel muy alto de experiencia y un control exhaustivo de las versiones. Además de conocimiento sobre solución de problemas como latencia en la red o balanceo de cargas.
Aunque disponer de un equipo tecnológico diferente para cada uno de los servicios tiene sus ventajas, si no se gestiona correctamente, conducirá a un diseño y arquitectura de aplicación poco uniforme.
Debido a que los componentes de la aplicación están distribuidos, las pruebas y test globales son más complicados de realizar.
Una arquitectura de microservicios puede suponer un alto coste de implantación debido a costes de infraestructura y pruebas distribuidas.

**###COMPARACIÓN ARQUITECTURA MONOLITICA Y DE MICROSERVICIOS **
![](https://click-it.es/arquitectura-monolitica-vs-arquitectura-de-microservicios-cual-debo-elegir/)
### La arquitectura monolitica tiene una implementacion mas facil que la de los microservicios, mientras que los microservicios tiene una implementacion continua haciendo que esta sea mas rapida y tiene un mayor numero de actualizaciones, haciendola mas complicada de implemetar a algun proyecto. 
### Los microservicios tienen una mayor flexibilidad que la arquitectura monolitica, esto hace que con los microservicios se puedan utilizar mas tipo de herramientas.
### Es mas sencillo tener repositorios en la arquitectura monolitica ya que esta se hace en un mismo codigo. 
### La arquitectura monolitica tiene una escalabilidad menor a la de los microservicios ya que en esta no se pueden escalar componentes indivuduales.

**CASOS DE APLICABILIDAD**
### Ebay : Es una de las empresas con mayor visión de futuro, siendo pionera en la adopción de tecnologías como Docker o ésta que nos ocupa. Su aplicación principal comprende varios servicios autónomos, y cada uno ejecutará la lógica propia de cada área funcional que se ofrece a los clientes.
### Netflix : Esta plataforma tiene una arquitectura generalizada que desde hace ya un par de años esta en los microservicios para el funcionamiento de sus productos. A diario recibe una media de mil millones de llamadas a sus diferentes servicios.



FUENTES
https://www.atlassian.com/es/microservices/microservices-architecture/microservices-vs-monolith
https://es.slideshare.net/sergio.maurenzi/microservicios-48252592
