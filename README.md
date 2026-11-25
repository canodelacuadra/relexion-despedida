# Lo que me llevo · Cierre IFCD0210

Pequeña actividad web interactiva para despedir al grupo del certificado **IFCD0210** y facilitar una reflexión final en voz alta.

## Qué incluye

- Una portada con la dinámica de la actividad.
- 5 preguntas de reflexión, mostradas una a una.
- Una pauta breve en cada pregunta para ayudar a verbalizar.
- Una pantalla final con el repaso de todas las preguntas y un mensaje de cierre.
- Diseño simple, responsive y listo para proyectar en clase.

## Preguntas

1. Cuando empecé el curso, ¿qué pensaba que era desarrollar una aplicación web?
2. ¿Qué cosas puedo hacer ahora que antes no sabía?
3. ¿Qué ha sido lo que más me ha costado aprender?
4. ¿De qué ejercicio, proyecto o logro estoy más orgulloso?
5. ¿Qué me gustaría aprender a partir de ahora?

## Uso en clase

1. Abre la web en el proyector o pantalla compartida.
2. Pulsa **Empezar la actividad**.
3. Lee cada pregunta con calma.
4. Deja unos segundos para pensar y abre el turno de palabra.
5. Usa **Siguiente pregunta** para avanzar y, al final, cierra con la pantalla de despedida.

> La actividad está pensada para dinamizar la conversación en grupo. No recoge ni guarda respuestas.

## Probar en local

No necesita instalación ni dependencias. Puedes abrir `index.html` directamente en el navegador.

Si prefieres usar un servidor local:

```bash
# Con Python 3
python -m http.server 8000
```

Después abre [http://localhost:8000](http://localhost:8000).

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub (por ejemplo, `reflexion-cierre-ifcd0210`).
2. Sube los archivos del proyecto (`index.html` y `README.md`).
3. En GitHub, entra en **Settings** > **Pages**.
4. En **Build and deployment**, selecciona:
   - **Source**: *Deploy from a branch*
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Guarda los cambios y espera a que GitHub publique la web.
6. La URL tendrá un formato similar a:

   `https://tu-usuario.github.io/reflexion-cierre-ifcd0210/`

## Personalización rápida

Si quieres adaptar el contenido, edita `index.html`:

- **Título y subtítulo**: en la sección `<header>`.
- **Preguntas y pautas**: en el array `questions` dentro del `<script>`.
- **Mensaje final**: en la sección `#closing`.
- **Colores**: en las variables CSS dentro de `:root`.
