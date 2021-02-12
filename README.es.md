# Music Player React

Vamos a crear un reproductor de MP3 que funciona de manera similar a Spotify, [aqui esta la demo](https://projects.breatheco.de/json/?slug=music-player-react&preview/).

Los botones siempre deben permanecer en la parte inferior de la ventana gráfica (use la posición fijada para eso).
Solo necesita implementar los botones Reproducir, Pausa, Siguiente y anterior.


## Recomendaciones de implementación

- Listar las canciones de [esta API](http://assets.breatheco.de/apis/sound/)utilizando la función de fetch.
- Cuando el usuario hace clic en una canción, el player (reproductor) debe comenzar a reproducirla.
- Cuando el usuario hace clic en el botón "siguiente", el reproductor debe comenzar a reproducir la siguiente canción de la lista, si no hay una canción siguiente, debe comenzar nuevamente tocando la primera canción de la lista, lo mismo se aplica a la "anterior" botón.
- Use el atributo reaccionar ref para obtener la etiqueta de audio del DOM.
- No hay necesidad de volumen, sin embargo, lo puedes agregar si te sientes con confianza.
- Asegurate de que haya un solo audio tag en el project para que puedas reutilizarlo utilizando useRef.

## Recomendaciones
- Conoce sobre la funcion `useRef` para que puedas 
- Nunca llame a la función setState porque perderá el estado de la etiqueta de audio si se llama a la función de render

## 😎 Te sientes con confianza?

Los siguientes requerimientos no son necesarios para entregar la solucion pero puedes intentar realizarlos si tienes tiempo y te sientes con confianza.

+1 Implementa control de volumen": dos botones, uno para subir y otro para bajar el volumen.
+1 Modo repeticion: un checkbox que cuando esta activo, la cancion se repetira eternamente.
+2 Aleatorio:: un botón que al presionarlo reprodusca una cancion aleatoriamente.
+5 Medidor de progreso de la canción: Implementa un slider o progress bar que se complete a medida que la cancion se reproduce.
