# Actualización del juego

Este paquete mantiene la lógica de recompensas por dispositivo usando `?device=...` y las imágenes QR locales dentro de `qrs/`.

Cambios principales:

- Juego adaptativo a pantalla completa del navegador/tótem con `100dvh` y safe areas.
- Modo Easy fijo por default. Ya no se muestra selector de dificultad.
- Se eliminó la lógica de backend/API de recompensas. Las recompensas siguen saliendo desde los QR por dispositivo.
- Animación del balón mejorada con canvas, arco, perspectiva y spin.
- Portero con player/CPU visual, mejor movimiento y tiempos más cómodos para tótem.
- Mayor tiempo de tiro y defensa para que el usuario pueda jugar en pantallas táctiles.

Para publicar:

1. Sustituye el `index.html` actual por este nuevo `index.html`.
2. Mantén la carpeta `qrs/` en la raíz del repo.
3. Cada dispositivo debe seguir usando su URL:

`https://miguelgrhub.github.io/mundial_nexus/?device=ID_DEL_DISPOSITIVO`
