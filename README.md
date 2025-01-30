# Proyecto SpotifyX - Clon de Spotify

Este proyecto es un clon simple de Spotify desarrollado con React y Vite. Permite la reproducción de música y la navegación entre una lista de canciones. Actualmente es una aplicación frontend, pero planeo expandirla a una solución Full Stack en el futuro.

## Características

- Reproducción de audio.
- Navegación entre las canciones.
- Lista de 8 canciones disponibles para escuchar.
- Contexto para gestionar el estado de la música (actual canción, tiempo, estado de reproducción).

## Tecnologías

- **React**: Biblioteca de JavaScript para construir interfaces de usuario.
- **Vite**: Herramienta de construcción rápida para proyectos frontend.
- **TailwindCSS**: Framework de CSS para diseño rápido y eficiente.
- **React Router**: Para la navegación entre rutas (si se requiere agregar múltiples vistas).
- **Context API**: Para gestionar el estado global del reproductor de música.

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tuusuario/proyecto-spotifyx.git
    ```

2. Entra en el directorio del proyecto:
    ```bash
    cd proyecto-spotifyx
    ```

3. Instala las dependencias:
    ```bash
    npm install
    ```

4. Ejecuta el proyecto en modo desarrollo:
    ```bash
    npm run dev
    ```

  

## Estructura de Archivos
/src /assets /assets.js # Datos de canciones /components /PlayerContext.js # Contexto para la reproducción de música /App.js # Componente principal de la aplicación /index.js # Punto de entrada de la aplicación

## Cómo Usar

1. El reproductor comenzará con la primera canción de la lista.
2. Usa los controles para reproducir, pausar, o cambiar entre canciones.
3. La barra de búsqueda permite saltar a una canción específica al hacer clic en ella.

## Funcionalidades Futuras

- Agregar más canciones y carpetas.
- Convertir la aplicación en Full Stack con un backend para gestionar las canciones y las listas de reproducción.
- Integrar autenticación de usuario.
- Mejorar la interfaz y hacerla responsive.

## Contribución

Si deseas contribuir a este proyecto, siéntete libre de abrir un *issue* o hacer un *pull request*. ¡Cualquier ayuda será bienvenida!


