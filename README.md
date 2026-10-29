# Vacaciones recreativas · Jardín Infantil Pasitos de Amor

Página informativa estática (un solo `index.html` + `logo.png`), publicada en Vercel:
https://vacaciones-xi.vercel.app/

## Cómo actualizar

Todo lo editable está al inicio del `<script>` de `index.html`:

- `CONFIG`: WhatsApp, precios, dirección, redes, avisos extra. Lo que quede vacío (`""`) no se muestra.
- `SEMANAS`: actividades por día. Las fechas van como `AAAA-MM-DD`; el día de la semana se calcula solo.

## Publicar

Subir los cambios a `main` en GitHub; Vercel despliega automáticamente.

## Pendiente

- Llenar precios, dirección, edades y cupos en `CONFIG`.
- Crear una imagen `og.png` de 1200×630 y apuntar `og:image` a ella (mejor vista previa al compartir).
- `src/original-vivo-referencia.html` es la versión anterior publicada; se puede borrar.
