# Club Temporal · Rider técnico

Rider técnico de las dos salas de Club Temporal (Av. Juan B. Justo 1579, CABA), publicado como web.

## Estructura

```
index.html                  ← el rider (autocontenido: estilos, fuente e imágenes embebidos)
Rider_Club_Temporal.pdf     ← versión PDF que descarga el botón "Descargar PDF" (agregar)
vercel.json                 ← configuración del deploy en Vercel
```

## Cómo se publica

Cada `git push` a `main` dispara un deploy automático en Vercel.
Los pushes a otras ramas generan una URL de preview para revisar antes de publicar.

## Actualizar el rider

1. Reemplazar `index.html` por la nueva exportación (y el PDF si cambió).
2. Cambiar la fecha de "Actualizado" en la portada.
3. `git commit` + `git push`.

Contacto técnico: Pau Singla Lezcano · pausingla@gmail.com
