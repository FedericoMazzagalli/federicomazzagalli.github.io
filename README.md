# RIO54 — Archivo de lo inexplicado

Este repositorio prepara la publicación web de RIO54 como videojuego Unity WebGL.

## Publicación

La compilación se ejecuta manualmente desde **Actions → RIO54 Unity WebGL → Run workflow**.
El flujo descarga y verifica las fuentes oficiales Noto CJK, compila el proyecto con Unity 6.3 LTS,
valida los archivos WebAssembly y publica el resultado mediante GitHub Pages.

Antes de ejecutar:

1. En **Settings → Secrets and variables → Actions**, crear el secreto `UNITY_LICENSE`
   con el contenido completo del archivo de licencia Unity `.ulf`. No compartir esa licencia en chats.
2. En **Settings → Pages**, seleccionar **Build and deployment → Source: GitHub Actions**.
3. Ejecutar el workflow manualmente desde Actions.

La URL pública prevista es https://federicomazzagalli.github.io/

## Código fuente

El proyecto Unity se almacena en este repositorio como un archivo ZIP codificado en partes
para permitir su reconstrucción durante el workflow. El código fuente del proyecto queda público
porque este repositorio de GitHub Pages es público.

## Contenido del juego

- Cuatro expedientes de investigación y 16 pistas.
- Ocho idiomas: español, inglés, portugués brasileño, francés, alemán, italiano, japonés y chino simplificado.
- Guardado local de progreso.
- Escena 3D nocturna procedural.
- Fuentes Noto CJK y avisos de licencia incorporados al proceso de compilación.

La adaptación es independiente y no implica aval del Café Ufológico RIO54 ni de los autores de sus publicaciones.
