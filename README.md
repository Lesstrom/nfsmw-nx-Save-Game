# NFSMW-NX Save Game — Xbox 360 2005

Partida V6 FINAL de **Need for Speed: Most Wanted (2005)** para el port nativo de Nintendo Switch `nfsmw-nx`.

## Créditos

Este método nace gracias a la creación del port [StevensND/nfsmw-nx](https://github.com/StevensND/nfsmw-nx).

Agradecimientos a [XPGamesaves](https://www.xpgamesaves.com/threads/need-for-speed-most-wanted-2005-xbox-360-bonus-cops-cars-save-game.154029/) por publicar la partida de Xbox 360 utilizada como base.

## Qué incluye

- Carrera V6 FINAL de Xbox 360.
- Progreso completo de carrera.
- Coches adicionales, coches de policía y contenido modificado del save original.
- Archivo interno compatible con el formato de guardado que reconoce `nfsmw-nx`.

## Instalación genérica

1. Inicia el port en la Switch y crea primero un perfil llamado `SK`.
2. Cierra el juego y apaga la Switch antes de retirar la microSD.
3. En la microSD, busca la carpeta `nfsmw` dentro de la carpeta del port.
4. Localiza la ruta de guardado que termina en:

   ```text
   00000001/SK/SK
   ```

   La parte anterior puede variar según el perfil o la instalación.

5. Haz una copia del archivo `SK` original.
6. Copia el archivo `SK` incluido en este repositorio y reemplaza solamente el archivo final.
7. No reemplaces `Headers` ni el archivo `SK.header` generado por tu Switch.
8. Expulsa la microSD de forma segura, inicia el juego y carga el perfil `SK`.

## Ruta de ejemplo

```text
switch/nfsmw-nx/nfsmw/B13EBABEBABEBABE/454107D9/00000001/SK/SK
```

La ruta de ejemplo corresponde a una instalación concreta. Lo importante es usar la carpeta de guardado que el propio port haya generado.

## Nota

Este repositorio distribuye únicamente un archivo de guardado. Se necesita una copia legal del juego y del port correspondiente. Conserva siempre una copia de tu guardado original antes de reemplazarlo.
