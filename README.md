# File Transfer Application - SuperDrop

## Descripción

La aplicación de transferencia de archivos es una solución simple y eficiente para enviar y recibir archivos entre dispositivos conectados a la misma red local. Inspirada en Snapdrop, esta aplicación utiliza tecnologías modernas como React para el frontend, Node.js con Express para el backend y WebSockets para la comunicación en tiempo real.

## Características

- **Transferencia de archivos en tiempo real:** Envía y recibe archivos de manera rápida y eficiente.
- **Interfaz amigable:** Interfaz de usuario sencilla y fácil de usar.
- **Soporte para múltiples tipos de archivos:** Compatible con diversos formatos de archivos.
- **Seguridad:** Transferencia de archivos segura dentro de la red local.


## Tecnologías Utilizadas

### Backend
- Node.js
- Express
- WebSockets (Socket.io)

### Frontend
- React
- Vite
- WebSockets (Socket.io-client)

## Instalación y Configuración

### Prerrequisitos

- Node.js
- npm (Node Package Manager)

### Instalación

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/Ezzz-Lui/SuperDrop.git


## Estructura general de lado backend
1. **Backend:**
- **controllers/fileController:** Contiene la lógica para manejar las solicitudes de carga y descarga de archivos.

- **models/fileModel:** Define el modelo de datos para los archivos (si es necesario).

- **routes/fileRoutes:** Define las rutas de la API para las operaciones de archivos.

- **services/fileService:** Contiene la lógica de negocio para la transferencia de archivos.

- **utils/websocket:** Configura y maneja las conexiones WebSocket.

- **config/db:** Configuración de la base de datos (si es necesario).

- **app:** Configura la aplicación Express.

- **server:** Punto de entrada del servidor.

## Contribuir

Las contribuciones son bienvenidas. Siéntete libre de abrir un issue o un pull request en GitHub.
