# Decoración élfica para fichas

Pega `ficha-plantilla.html` en tu ficha con el modo HTML activo. Sustituye `URL_AVATAR`, `URL_IMAGEN_LATERAL`, `LINK_DIARIO`, los datos, la historia y los textos de ejemplo. La ilustración central incluida es la referencia proporcionada por ti; puedes sustituir su URL.

La plantilla conserva las clases y la estructura general del foro. `zh-elfica` en el contenedor exterior limita todos los efectos a esa ficha. La fuente Underdove se utiliza para el nombre, el subtítulo y Curiosidades. El texto largo conserva la fuente del foro.

`var(--groups)` toma el color de tu grupo; si no existe, usa `#97976b`. Los efectos oscilan entre este color y el dorado `#d5b776`. El fondo de la decoración es transparente. No es necesario JavaScript. Con movimiento reducido se desactivan las animaciones.

Para añadir otro recuadro, repite un bloque `zh-curiosidad`. El icono personalizado es una corona con hojas y una gema. Dentro de la ficha se inserta con `<i class="zh-icono" aria-hidden="true"></i>`. Se puede usar fuera envolviéndolo en `<span class="zh-elfica">…</span>`.

La cabecera utiliza bloques consecutivos en el flujo: línea completa, frase, línea completa, subtítulo, imagen e icono. Las letras nunca se animan hacia negro. La imagen se desatura y recibe un tinte del grupo mezclado con dorado mediante CSS; el archivo original no se modifica.

La vista previa utiliza una representación de la estructura del foro para comprobar los elementos decorativos. La distribución original depende del CSS ya instalado en tu foro y no se sustituye aquí.
