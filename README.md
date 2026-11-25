# TOTIMAT — Sitio provisional GitHub Pages

Página estática **independiente** del proyecto Astro definitivo. Se puede publicar tal como está en GitHub Pages, sin Node, npm, compilaciones ni dependencias.

## Publicación

1. Crea un repositorio nuevo, por ejemplo `totimat-provisional`, sin reemplazar el proyecto principal en desarrollo.
2. Sube **`index.html` y la carpeta `assets/` a la raíz del repositorio**, conservando sus nombres y rutas. Puedes subirlos desde el navegador de GitHub o mediante Git.
3. Abre **Settings → Pages → Build and deployment → Deploy from a branch**, selecciona `main` y `/(root)` y guarda.
4. La URL usual de proyecto es `https://USUARIO.github.io/totimat-provisional/` (reemplaza USUARIO por el usuario real). No confundir con una URL verificada o publicada.
5. Comprueba en computadora y móvil los enlaces, imágenes, filtros y botones.

## Editar contenidos

- Mensajes principales y secciones: `index.html`.
- Productos demostrativos: lista JavaScript `const creations` dentro de `index.html`.
- Fotos optimizadas: `assets/*.webp`.
- Logo: `assets/logo-totimat.webp`.
- Contactos actuales: Instagram `creandocontotimat` y Facebook `RocioBaqueroCreaciones`.

### Antes de publicar al público

- Revisar y aprobar cada foto recortada de los materiales proporcionados, especialmente las imágenes de bordados de la captura de referencia.
- Revisar derechos de uso de las fotos del catálogo.
- Confirmar textos de la marca con la creadora.
- Las piezas exhibidas no afirman stock, precio ni venta inmediata. No se muestran testimonios inventados.
- No se configuró WhatsApp porque falta confirmar número oficial; una vez aprobado, se podrá sustituir el botón de Instagram por el enlace oficial `https://wa.me/57NUMERO`.
- No hay carrito/pasarela de pagos en esta versión. El botón de encargo dirige a la sección de contacto.

## Comprobación rápida local

```bash
cd TOTIMAT_GitHub_Pages
python -m http.server 8000
```

Abre `http://localhost:8000/`. No necesita instalar nada más en GitHub Pages.
