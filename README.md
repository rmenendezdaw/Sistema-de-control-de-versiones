
# Sistema de control de versiones

Se llama control de versiones a la gestión de los diversos cambios que se realizan sobre los elementos de algún producto o una configuración del mismo. Una versión, revisión o edición de un producto, es el estado en el que se encuentra el mismo en un momento dado de su desarrollo o modificación.

Aunque un sistema de control de versiones puede realizarse de forma manual, es muy aconsejable disponer de herramientas que faciliten esta gestión dando lugar a los llamados sistemas de control de versiones o VCS. 

Estos sistemas facilitan la administración de las distintas versiones de cada producto desarrollado.

## GIT

Es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente. 

Su propósito es llevar registro de los cambios en archivos de computadora y coordinar el trabajo que varias personas realizan sobre archivos compartidos.

Algunas de las características más importantes de Git son:

- Rapidez en la gestión de ramas, debido a que Git nos dice que un cambio será fusionado mucho más frecuentemente de lo que se escribe originalmente.
- Gestión distribuida; Los cambios se importan como ramas adicionales y pueden ser fusionados de la misma manera como se hace en la rama local.
- Gestión eficiente de proyectos grandes.
- Realmacenamiento periódico en paquetes.

## GIT FLOW

Es un modelo de branching o de ramificación, un flujo, una metodología  que ha ido evolucionando.

Actualmente se ha convertido también en una herramienta soportada por comandos y que sirve de gran ayuda en la gestión de repositorios de tipo Git, y que incluso aporta buenas prácticas que ayudan a gestionar todo de forma correcta y de forma eficiente.

### Ventajas

GitFlow tiene una gran aceptación y es bastante interesante porque básicamente tiene lo mejor de los dos mundos. Está centralizado como SVN y también está descentralizado, lo que permite que muchos equipos trabajen de forma independiente entre ellos, siempre pasando por el repositorio central.


Vamos a configurar que el repositorio sea público y que además añada el archivo README.md.
Creación del archivo html

El usuario 1 se encarga de crear el archivo html que lo llamaremos “index.html”.

Esto ayuda a no tener el riesgo de mergear o hacer commit sobre un trunk o repositorio que está utilizado por muchas personas.

Aparte de eliminar ese factor de riesgo, siempre integra código en fases muy tempranas, de forma que los equipos puedan trabajar de forma independiente, y al final mergean su código hasta llegar a la rama principal o master.


## Simulación de usuarios

Para esta práctica voy a simular los usuarios con diferentes directorios:


![GitHub Logo](/images/creardirectorios.png)



### Usuario1

Empezamos creando el repositorio en Github:

![GitHub Logo](/images/new.png)

Cuando hagamos click en “New” accederemos a la siguiente página, en la cual podemos configurar algunas opciones.

![GitHub Logo](/images/creating.png)

Vamos a configurar que el repositorio sea público y que además añada el archivo README.md.

#### Creación del archivo html

El usuario 1 se encarga de crear el archivo html que lo llamaremos “index.html”.

**raul@Portatil:~/Escritorio/Despliegue_Web/GitFlow/usuario1$ touch index.html**

Una vez creado implementará las funciones que se le han requerido:

![GitHub Logo](/images/htmlfirst.png)


Inicialización del repositorio y primer “push”:

Para el desarrollo de este proyecto se utilizará GitFlow. Lo primero que vamos a hacer es inicializar el directorio y crear las ramas. GitFlow crea las ramas Master y Develop por defecto:

![GitHub Logo](/images/gitflowinit.png)

Este proyecto se va a poner en producción, para ello tenemos que cambiar de rama:
![GitHub Logo](/images/cambiorama.png)



