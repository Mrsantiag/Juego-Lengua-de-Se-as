# Aventura LSC – Lengua de Señas Colombiana

Dos secciones desde el menú principal:

- **Repaso:** muestra cada seña con su nombre. Tiene buscador y, al tocar una seña, se ve en grande.
- **Juego:** carrera de tablero para 1 a 4 jugadores. Cada turno se responden 1, 2 o 3 señas según la dificultad.

Las señas del juego salen como una baraja: ninguna se repite hasta que hayan salido todas.

## Estructura
```
index.html      -> el juego y el repaso
imagenes/       -> una imagen por seña (frijol.png, frio.png, ...)
```

## Agregar una seña nueva
1. Pon la imagen en `imagenes/` (ej. `arroz.png`).
2. En `index.html`, dentro de `questionsDatabase`, agrega una línea:
   `{ id: 23, word: "ARROZ", image: "imagenes/arroz.png" },`

Aparece sola en el repaso y en el juego.
