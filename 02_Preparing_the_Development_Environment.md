
# 2. Preparando el entorno de desarrollo

* Selecting development tools

   * Workspace options

      * Local and cloud development

   * IDE or text editors

   * Chrome Developer Tools

   * Git

      * Installation

      * Remote Git hosting services

* Setting up MERN stack technologies

   * MongoDB

      * Installation

      * Running the mongo shell

   * Node

      * Installation

         * Upgrading npm versions

      * Node version management with nvm

   * npm modules for MERN

      * Key modules

      * devDependency modules

* Checking your development setup

   * Initializing package.json and installing npm modules

   * Configuring Babel, Webpack, and Nodemon

      * Babel

      * Webpack

         * Client-side Webpack configuration for development

         * Server-side Webpack configuration

         * Client-side Webpack configuration for production 

      * Nodemon

   * Frontend views with React

   * Server with Express and Node

      * Express app

      * Bundle React app during development

      * Serving static files from the dist folder

      * Rendering templates at the root 

   * Connecting the server to MongoDB

   * npm run scripts

   * Developing and debugging in real time

* Summary


Antes de crear aplicaciones con la stack MERN, primero debemos preparar el entorno de desarrollo con cada tecnología, y también con herramientas para ayudar al desarrollo y la depuración. Este capítulo lo guía a través de la comprensión de las opciones del espacio de trabajo, las herramientas de desarrollo esenciales, cómo configurar las tecnologías MERN en su espacio de trabajo y los pasos para verificar esta configuración con el código real.

Vamos a cubrir los siguientes temas:

* Opciones del Workspace (espacio de trabajo)

* Editores de código

* Chrome Developer Tools (Herramientas para desarrolladores de Chrome)

* Configuración de Git

* Configuración de MongoDB

* Configuración de Node

* Módulos npm para completar MERN stack

* Código para verificar la configuración de MERN


## Seleccionar herramientas de desarrollo

Hay muchas opciones disponibles cuando se trata de seleccionar herramientas de desarrollo básicas como editores de texto o IDE, software de control de versiones e incluso el propio espacio de trabajo de desarrollo. En esta sección, repasamos las opciones y recomendaciones relevantes para el desarrollo web con MERN para que pueda tomar decisiones informadas al seleccionar estas herramientas basadas en preferencias individuales.

### Opciones del Workspace (espacio de trabajo)

Desarrollar en una máquina local es la práctica más común entre los programadores, pero con la llegada de buenos servicios de desarrollo en la nube, como Cloud9 (https://aws.amazon.com/cloud9/?origin=c9io), ahora es posible usar cualquiera o los dos. Puede configurar su espacio de trabajo local con tecnologías MERN, y se supondrá que este es el caso en el resto del libro, pero también puede elegir ejecutar y desarrollar el código en los servicios en la nube que vienen equipados para el desarrollo de Node.

#### Desarrollo local y en la nube (cloud)

Puede optar por utilizar ambos tipos de espacios de trabajo para disfrutar de los beneficios de trabajar localmente sin preocuparse por los problemas de ancho de banda / Internet y trabajar de forma remota cuando físicamente no tiene su máquina local favorita. Para hacer esto, puede usar Git para controlar el código de su versión, almacenar su último código en servicios de alojamiento Git remotos como GitHub o BitBucket, y luego compartir el mismo código en todos sus espacios de trabajo.

### IDE o editores de texto

La mayoría de los entornos de desarrollo en la nube vendrán integrados con editores de código fuente. Pero para su espacio de trabajo local, puede elegir cualquiera según su preferencia como programador y luego personalizarlo para el desarrollo de MERN. Por ejemplo, las siguientes opciones populares se pueden personalizar según sea necesario:

* Atom (https://atom.io/): un editor de texto gratuito y de código abierto para GitHub que tiene muchos paquetes relevantes para la stack MERN disponibles de otros desarrolladores

* SublimeText (https://www.sublimetext.com/): un editor de texto multiplataforma patentado que también tiene muchos paquetes relevantes para la stack MERN disponibles, junto con soporte para el desarrollo de JavaScript

* Visual Studio Code (https://code.visualstudio.com/): un editor de código fuente rico en funciones de Microsoft con amplio soporte para el flujo de trabajo moderno de desarrollo de aplicaciones web, incluido el soporte para tecnologías de stack MERN

* WebStorm (https://www.jetbrains.com/webstorm/): un IDE de JavaScript completo de JetBrains, con soporte para el desarrollo basado en la stack MERN

### Chrome Developer Tools (Herramientas para desarrolladores de Chrome)

Cargar, ver y depurar la interfaz es una parte crucial del proceso de desarrollo web. Las Herramientas para desarrolladores de Chrome, que forman parte del navegador Chrome, tienen muchas características excelentes que permiten depurar, probar y experimentar con el código de la interfaz y la apariencia, sensación, capacidad de respuesta y rendimiento de la interfaz de usuario. Además, la extensión React Developer Tools está disponible como un complemento de Chrome y agrega herramientas de depuración React a las Herramientas de desarrollador de Chrome.

### Git

Cualquier flujo de trabajo de desarrollo está incompleto sin un sistema de control de versiones que permita rastrear cambios de código, compartir código y colaborar. Con los años, Git se ha convertido en el sistema de control de versiones de facto para muchos desarrolladores y es la herramienta de administración de código fuente distribuido más utilizada. Para el desarrollo de código en este libro, Git ayudará principalmente a rastrear el progreso a medida que avanzamos por los pasos para desarrollar cada aplicación.

#### Instalación

Para comenzar a usar Git, primero instálelo en su máquina local o entorno de desarrollo en la nube según las especificaciones de su sistema. Las instrucciones relevantes para descargar e instalar el último Git, junto con la documentación sobre el uso de los comandos de Git se pueden encontrar en: https://git-scm.com/downloads.

#### Servicios de alojamiento remoto Git

Los servicios de alojamiento de repositorios Git basados en la nube, como GitHub y BitBucket, ayudan a compartir su último código en espacios de trabajo y entornos de implementación, y también para hacer una copia de seguridad de su código. Estos servicios incluyen muchas funciones útiles para ayudar con la gestión de código y el flujo de trabajo de desarrollo. Para comenzar, puede crear una cuenta y configurar repositorios remotos para sus bases de código.

Todas estas herramientas esenciales enriquecerán su flujo de trabajo de desarrollo web y aumentarán la productividad una vez que complete la configuración necesaria en su espacio de trabajo y comience a construir aplicaciones MERN.


