# 3. Construyendo un Backend con MongoDB, Express y Node

## Descripción General de la Aplicación Esqueleto

### Desglose de Funciones

### Enfoque de este Capítulo: el Backend

#### Modelo de Usuario

#### Puntos Finales API para el Usuario CRUD

#### Autenticación con Tokens Web JSON

##### Cómo Funciona JWT

## Implementación del Backend Esqueleto

### Carpeta y Estructura de Archivos

### Configuración del Proyecto

#### Inicializando `package.json`

#### Dependencias de Desarrollo

##### Babel

##### Webpack

##### Nodemon

#### Variables de Configuración

#### Ejecución de Scripts

### Preparando el Servidor

#### Configuración de Express

#### Iniciando el Servidor

#### Configuración de Mongoose y Conexión a MongoDB

#### Sirviendo una Plantilla HTML en una URL Raíz

### Modelo de Usuario

#### Definición de Esquema de Usuario

##### Nombre

##### Email

##### Marcas de Tiempo Creadas y Actualizadas

##### Contraseña hash y sal

#### Contraseña para Autenticación

##### Como Campo Virtual

##### Cifrado y Autenticación

##### Validación de Campo de Contraseña

#### Manejo de Errores de Mangosta

### API de Usuario CRUD

#### Rutas de Usuario

#### Controlador de Usuario

##### Crear un Nuevo Usuario

##### Listado de Todos los Usuarios

##### Carga de un Usuario por ID para Leer, Actualizar o Eliminar

###### Cargando

###### Leyendo

###### Actualización

###### Eliminar

##### Autenticación de Usuario y Rutas Protegidas

###### Rutas de Autenticación

###### Controlador de Autenticación

###### Registrarse

###### Desconectar

###### Protección de Rutas con express-jwt

####### Requerir Inicio de Sesión

####### Autorización de Usuarios Registrados

####### Protección de Rutas de Usuario

####### Manejo de Errores de Autenticación para express-jwt

### Comprobación del backend independiente

#### Crear un nuevo usuario

#### Obteniendo la lista de usuarios

#### Intentando buscar un solo usuario

#### Iniciando sesión

#### Obteniendo un solo usuario con éxito

### Resumen

