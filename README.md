# okDomesticWork

Un shooter 2D mágico y surreal hecho con HTML5 Canvas puro (sin librerías ni build step). Una hechicera doméstica se mueve de un lado a otro del cielo de su cocina, disparando chispas hacia arriba para destruir los platos sucios que caen antes de que lleguen al piso, mientras atrapa los anillos de diamante que también caen.

## Cómo jugar

- **Moverse:** flechas ← → o teclas A / D
- **Disparar:** mantené apretado ESPACIO (o ↑)
- En pantallas táctiles aparecen botones en pantalla automáticamente

### Reglas

- Arrancás con 5 vidas
- Cada plato que llega al piso sin ser destruido te resta una vida
- Destruir un plato de un disparo suma **+10 puntos**
- Atrapar un anillo suma **+50 puntos**
- Si un anillo cae al piso sin ser atrapado, restás **-20 puntos**
- Al perder las 5 vidas aparece la pantalla de game over, con opción de jugar de nuevo o volver al menú principal

## Publicarlo con GitHub Pages

Este repo ya está listo para GitHub Pages: el juego es un único archivo `index.html` autocontenido.

1. Andá a **Settings → Pages** en este repositorio
2. En "Build and deployment" elegí **Deploy from a branch**
3. Elegí la branch `main` y la carpeta `/ (root)`
4. Guardá — GitHub te va a dar un link público (algo como `https://tu-usuario.github.io/okDomesticWork/`) donde cualquiera puede jugar directo desde el navegador

> Nota: publicar con GitHub Pages en el plan gratuito requiere que el repositorio sea **público**. Si lo dejás privado, Pages no va a estar disponible salvo que tengas GitHub Pro/Team.

## Tecnología

- HTML5 Canvas + JavaScript vanilla, sin dependencias externas
- Tipografías: [Fredoka](https://fonts.google.com/specimen/Fredoka) y [Quicksand](https://fonts.google.com/specimen/Quicksand) vía Google Fonts
- Récord personal guardado en el navegador (`localStorage`)

## Licencia

MIT — ver [LICENSE](./LICENSE). Podés usar, modificar y redistribuir este código libremente, incluso con fines comerciales, siempre que mantengas el aviso de copyright.
