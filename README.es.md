<!--hide-->
# Reproductor de Música en React
<!--endhide-->

Vamos a crear un reproductor de MP3 que funcione de manera similar a Spotify ![Todo List](https://github.com/breatheco-de/exercise-music-player-react/blob/master/preview.gif?raw=true).

Los botones siempre deben permanecer en la parte inferior de la ventana (usa `position: fixed` para lograrlo). Solo necesitas implementar los botones de Reproducir, Pausar, Siguiente y Anterior.

<onlyfor saas="false" withBanner="false">
  
## 🌱 Cómo iniciar este proyecto

No clones este repositorio porque usaremos una plantilla diferente.  

Recomendamos abrir la plantilla `react-hello`, utilizando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternativamente, puedes [clonar el repositorio de GitHub](https://4geeks.com/how-to/github-clone-repository) en tu computadora local utilizando el comando `git clone`.  

Este es el repositorio que necesitas abrir o clonar:  

```sh
$ git clone https://github.com/4GeeksAcademy/react-hello
```

💡 Importante: Recuerda crear un nuevo repositorio, actualizar el remoto (`git remote set-url origin <tu nueva url>`), y subir el código a tu nuevo repositorio utilizando `add`, `commit` y `push`.


</onlyfor>

## 📝 Requisitos

- Lista las canciones desde [la API de Sounds](https://playground.4geeks.com/sound/docs) usando la API Fetch.
- Cuando el usuario haga clic en una canción, el reproductor debe comenzar a reproducirla.
- Cuando el usuario haga clic en el botón "siguiente", el reproductor debe empezar a reproducir la siguiente canción de la lista. Si no hay más canciones, debe comenzar de nuevo reproduciendo la primera canción de la lista. Lo mismo aplica para el botón "anterior".
- Usa el atributo `ref` de React para obtener la etiqueta `<audio>` del DOM.
- Asegúrate de tener solo una etiqueta `<audio>` en todo el proyecto. Usa `ref` para cambiar su URL `src`.

## 😎 ¿Te sientes con confianza?

Las siguientes características no son necesarias para la solución final, pero puedes desarrollarlas si te sientes lo suficientemente confiado:

- `+1` Implementa control de volumen: dos botones, uno para subir y otro para bajar el volumen.
- `+1` Botón de modo repetición: cuando esté activado, la canción actual se repetirá indefinidamente hasta ser desactivado.
- `+2` Funcionalidad de reproducción aleatoria: las canciones se reproducirán de forma aleatoria en lugar de en orden.
- `+5` Implementa una barra de progreso con slider: la barra se moverá conforme a la canción y, si se hace clic, la canción saltará a ese tiempo.
