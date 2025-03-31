# Proyecto APPSC y FAPPSC

Este proyecto se divide en dos partes principales: **APPSC** (backend) y **FAPPSC** (frontend). A continuación, encontrarás detalles sobre la estructura, tecnologías utilizadas e instrucciones para ejecutar el proyecto.

---

## Estructura del Proyecto

### APPSC (Backend)
El backend contiene la lógica de negocio y la conexión con la base de datos. Está diseñado como una API REST utilizando **Node.js** y **Express.js**.

#### Estructura de carpetas:
- **src/controllers**: Contiene los controladores para manejar las solicitudes y procesar la lógica del negocio.
- **src/models**: Define los esquemas y modelos de la base de datos MongoDB.
- **src/routes**: Define las rutas para cada recurso de la API.
- **src/middlewares**: Middlewares personalizados para validar solicitudes.
- **src/db.js**: Configuración de la conexión con MongoDB.
- **src/app.js**: Archivo principal donde se configura el servidor Express.

---

### FAPPSC (Frontend)
El frontend es una aplicación construida en **React.js**, diseñada para la interacción con la API y una experiencia de usuario fluida.

#### Estructura de carpetas:
- **src/components**: Componentes reutilizables como formularios, botones, y otros elementos.
- **src/pages**: Contiene las vistas principales de la aplicación, como registro, inicio de sesión y gestión de notas.
- **src/context**: Gestión del estado global mediante React Context.
- **src/api**: Funciones para realizar solicitudes a la API del backend.
- **public**: Archivos estáticos accesibles al navegador.

---

## Tecnologías Utilizadas

### Backend
- **Node.js**: Entorno de ejecución para el backend.
- **Express.js**: Framework web minimalista para construir la API.
- **MongoDB**: Base de datos NoSQL para almacenamiento de datos.
- **Mongoose**: ODM para modelar los datos de MongoDB.

### Frontend
- **React.js**: Biblioteca para construir interfaces de usuario.
- **Tailwind CSS**: Framework CSS para estilos rápidos y consistentes.
- **Vite**: Herramienta de desarrollo para empaquetar y ejecutar React.

---

## Requisitos Previos

1. **Node.js**: [Descargar aquí](https://nodejs.org/).
2. **Vagrant y VirtualBox**: Instalados en tu máquina para la configuración de la VM (opcional para MongoDB local).

---

## Instalación y Ejecución

### Backend (APPSC)
1. Abre una terminal y navega a la carpeta `APPSC`.
2. Instala las dependencias: <npm install>
3. Inicia el servidor en modo desarrollo: <npm run dev>

### Frontend (FAPPSC)
1. Abre otra terminal y navega a la carpeta.
2. Instala las dependencias:  <npm install>
3. Inicia el servidor en modo desarrollo: <npm run dev>