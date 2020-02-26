
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
      
      
## Configuración de tecnologías de pila MERN

Las tecnologías de stack MERN se están desarrollando y actualizando a medida que se escribe este libro, por lo que para el trabajo demostrado a lo largo de este libro, utilizamos las últimas versiones estables en el momento de la redacción. Las pautas de instalación para la mayoría de estas tecnologías dependen del entorno del sistema de sus espacios de trabajo, por lo que esta sección apunta a todos los recursos de instalación relevantes, y también actúa como una guía para configurar una stack MERN completamente funcional.

### MongoDB

MongoDB debe configurarse y ejecutarse en el entorno de desarrollo antes de agregar características de la base de datos a las aplicaciones MERN. Al momento de escribir, la versión estable actual de MongoDB es 3.6.3, y esta versión de MongoDB Community Edition se usa para desarrollar las aplicaciones en este libro. El resto de esta sección proporciona recursos sobre cómo instalar y ejecutar MongoDB.

#### Instalación

Debe instalar e iniciar MongoDB en su espacio de trabajo para poder usarlo para el desarrollo. El proceso de instalación y arranque de MongoDB depende de las especificaciones del espacio de trabajo:

* Los servicios de desarrollo en la nube tendrán sus propias instrucciones para instalar y configurar MongoDB. Por ejemplo, los pasos prácticos para Cloud9 se pueden encontrar en: https://community.c9.io/t/setting-up-mongodb/1717.

* Las guías para la instalación en su máquina local se detallan en: https://docs.mongodb.com/manual/installation/.

#### Ejecutar el shell mongo

El *shell mongo* es una herramienta interactiva para MongoDB y un buen lugar para familiarizarse con las operaciones de MongoDB. Una vez que MongoDB está instalado y en ejecución, puede ejecutar el shell mongo en la línea de comando. En el shell mongo, puede probar comandos para consultar y actualizar datos, así como realizar operaciones administrativas.

### Nodo

La implementación del servidor back-end para las aplicaciones MERN se basa en Node y también en npm. Al momento de escribir, 8.11.1 es la última versión estable de Nodo disponible, y viene incluida con la versión 5.6.0 de npm. Sin embargo, la última versión disponible para npm es 5.8.0, por lo que después de instalar Node, npm deberá actualizarse como se describe en la siguiente sección.

#### Instalación

Node se puede instalar mediante descarga directa, instaladores o el administrador de versiones de Node:

* Puede instalar Node descargando directamente el código fuente o un instalador predefinido específico para su plataforma de espacio de trabajo. Las descargas están disponibles en nodejs.org/en/download.

* Los servicios de desarrollo en la nube pueden venir con Node preinstalado, como en Cloud9, o tendrán instrucciones específicas para agregar y actualizar Node.

* Los servicios de desarrollo en la nube pueden venir con Node preinstalado, como en Cloud9, o tendrán instrucciones específicas para agregar y actualizar Node.

Para probar si la instalación fue exitosa, puede abrir la línea de comando y ejecutar el `nodo -v` para ver si devuelve correctamente el número de versión.

```sh
mini-de-adolfo:~ adolfodelarosa$ node -v
v12.14.0
```

##### Actualización de versiones npm

Para instalar npm versión 5.8.0, ejecute el siguiente comando de instalación desde la línea de comando y verifique la versión con `npm -v`:

```sh
npm install -g npm@5.8.0 
npm -v
```

```sh
mini-de-adolfo:~ adolfodelarosa$ npm -v
6.13.4
```

#### Gestión de versiones de nodo con nvm

Si necesita mantener varias versiones de Node y npm para diferentes proyectos, nvm es una herramienta útil de línea de comandos para instalar y administrar diferentes versiones en el mismo espacio de trabajo. Tienes que instalar nvm por separado. Las instrucciones para la configuración se pueden encontrar en: github.com/creationix/nvm.

### Módulos npm para MERN

Las tecnologías de stack MERN restantes están disponibles como módulos npm y se pueden agregar a cada proyecto mediante la `npm install`. Estos incluyen módulos clave, como React y Express, que se requieren para ejecutar cada aplicación MERN, y también módulos que serán necesarios durante el desarrollo. En esta sección, enumeramos y discutimos los módulos, luego vemos cómo usar los módulos en un proyecto de trabajo en la siguiente sección.

#### Módulos clave

Para integrar las tecnologías de stack MERN y ejecutar sus aplicaciones, necesitaremos los siguientes módulos npm:

* **React**: Para comenzar a usar React, necesitaremos dos módulos:

   * `react`

   * `react-dom`
   
* **Express**: para usar Express en su código, necesitará el módulo `express`

* **MongoDB**: para usar MongoDB con aplicaciones Node, también debe agregar el controlador, que está disponible como un módulo npm llamado `mongodb``

#### Módulos devDependency

Para mantener la coherencia durante el desarrollo de las aplicaciones MERN, utilizaremos JavaScript ES6 en todo el stack. Como consecuencia, y también para ayudar al proceso de desarrollo, utilizaremos los siguientes módulos npm adicionales para compilar y agrupar el código y para volver a cargar automáticamente el servidor y la aplicación del navegador a medida que el código se actualiza durante el desarrollo:

* Se necesitan módulos de **Babel** para convertir ES6 y JSX a JavaScript adecuado para todos los navegadores. Los módulos necesarios para que Babel funcione son:
   * `babel-core`
   
   * `babel-loader` para transpilar archivos JavaScript con Webpack
   
   * `babel-preset-env`, `babel-preset-react` y `babel-preset-stage-2` para proporcionar soporte para React, las últimas funciones de JS y algunas características de stage-x como declarar campos de clase que actualmente no están cubiertos por `babel-preset-env`
   
* Los módulos Webpack ayudarán a agrupar el JavaScript compilado, tanto para el código del lado del cliente como del lado del servidor. Los módulos necesarios para que Webpack funcione son:

   * `webpack`
   
   * `webpack-cli` para ejecutar comandos de Webpack
   
   * `webpack-node-externals` para ignorar los archivos externos del módulo Node cuando se agrupa en Webpack
   
   * `webpack-dev-middleware` para servir los archivos emitidos por Webpack a través de un servidor conectado durante el desarrollo del código
   
   * `webpack-hot-middleware` para agregar la recarga de módulos calientes en un servidor existente conectando un cliente de navegador a un servidor Webpack y recibiendo actualizaciones a medida que el código cambia durante el desarrollo
   
* `nodemon` para observar los cambios del lado del servidor durante el desarrollo, por lo que el servidor se puede volver a cargar para que los cambios surtan efecto.

* `react-hot-loader` para un desarrollo más rápido en el lado del cliente. Cada vez que un archivo cambia en la interfaz React, `react-hot-loader` permite que la aplicación del navegador se actualice sin volver a agrupar todo el código de la interfaz.

*Aunque `react-hot-loader` está destinado a ayudar al flujo de desarrollo, es seguro instalar este módulo como una dependencia regular en lugar de una dependencia de desarrollo. Asegura automáticamente que la recarga en caliente esté desactivada en la producción y que la huella sea mínima.*

## Verificando su configuración de desarrollo

En esta sección, revisaremos el flujo de trabajo de desarrollo y escribiremos el código paso a paso para garantizar que el entorno esté configurado correctamente para comenzar a desarrollar y ejecutar aplicaciones MERN.

Generaremos estos archivos de proyecto en la siguiente estructura de carpetas para ejecutar un proyecto de instalación simple:

<pre>
| mern-simplesetup/
  | -- client/
    | --- HelloWorld.js
    | --- main.js
  | -- server/
    | --- devBundle.js
    | --- server.js
  | -- .babelrc
  | -- nodemon.json
  | -- package.json
  | -- template.js
  | -- webpack.config.client.js
  | -- webpack.config.client.production.js
  | -- webpack.config.server.js
</pre>

El código discutido en esta sección está disponible en GitHub en el repositorio en: https://github.com/shamahoque/mern-simplesetup. Puede clonar este código y ejecutarlo a medida que avanza por las explicaciones del código en el resto de este capítulo.

### Inicializando package.json e Instalando Módulos npm

Comenzaremos usando **npm** para instalar todos los módulos requeridos. Se recomienda agregar un archivo **`package.json`** en cada carpeta de proyecto para mantener, documentar y compartir los módulos **npm** que se utilizan en la aplicación MERN. El archivo **`package.json`** contendrá metainformación sobre la aplicación, así como también una lista de las dependencias del módulo.

Realice los pasos descritos a continuación para generar un archivo **`package.json`**, modificarlo y usarlo para instalar los módulos **npm**:

* **`npm init`**: Desde la línea de comando, ingrese a su carpeta de proyecto y ejecute **`npm init`**. Se le harán una serie de preguntas y luego se generará automáticamente un archivo **`package.json`** con sus respuestas.

* **`dependencies`**: Abra el **`package.json`** en su editor y modifique el objeto JSON para agregar los módulos clave y `react-hot-loader` como `dependencies` regulares.

   *La ruta del archivo mencionada antes de un bloque de código indica la ubicación del código en el directorio del proyecto. Esta convención se ha mantenido a lo largo del libro para proporcionar un mejor contexto y orientación a medida que sigue el código.*
   
   `mern-simplesetup/package.json`:
   
```sh
"dependencies": {
   "express": "^4.16.3",
    "mongodb": "^3.0.7",
    "react": "^16.3.2",
    "react-dom": "^16.3.2",
    "react-hot-loader": "^4.1.2"
}
```

* `devDependencies`: Modifica `package.json` para agregar los siguientes módulos npm necesarios durante el desarrollo como `devDependencies`.

* `npm install`: Salve `package.json` y desde la terminal, ejecute `npm install` para buscar y agregar todos estos módulos a su proyecto.


### Configuración de Babel, Webpack y Nodemon

#### Babel

#### Webpack

##### Configuración del paquete web del lado del cliente para el desarrollo

##### Configuración del paquete web del lado del servidor

##### Configuración del paquete web del lado del cliente para producción

#### Nodemon

### Vistas frontend con React

### Servidor con Express y Node

#### Aplicación Express

#### Aplicación Bundle React durante el desarrollo

#### Sirviendo archivos estáticos desde la carpeta dist

#### Representación de plantillas en la raíz

### Conexión del servidor a MongoDB

### npm ejecutar scripts

### Desarrollo y depuración en tiempo real.

## Resumen









