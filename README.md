# Rompecabezas de 12 piezas

Proyecto para GitHub Pages + Firebase Firestore.

## URLs

- `/1` a `/12` desbloquean cada pieza.
- El progreso es GLOBAL: todos comparten el mismo rompecabezas.

## Antes de publicar

1. Poné tu imagen horizontal en `assets/imagen.jpg`.
2. Creá un proyecto en Firebase.
3. Creá una aplicación web dentro del proyecto.
4. Copiá la configuración de Firebase en `index.html`.
5. Activá Firestore Database.
6. Aplicá las reglas de `firestore.rules`.
7. Cambiá `VIDEO_URL` por el enlace de tu video.
8. Subí todo a GitHub.
9. Activá GitHub Pages desde `main` / root.

`404.html` debe ser una copia de `index.html`. Esto permite que GitHub Pages cargue la aplicación cuando alguien entra directamente a `/7`, `/8`, etc.
