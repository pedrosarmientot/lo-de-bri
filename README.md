# Lo de Bri — landing

Landing page de negocio. El diseño/frontend lo genera **Stitch**; aquí va el export y luego el resto del trabajo (formularios, deploy, contenido real).

## Estructura

```
public/     # export de Stitch (index.html, css, imágenes)
brief.md    # lo que se le pasa a Stitch
```

## Ver en local

```sh
python3 -m http.server -d public 8000
# http://localhost:8000
```

Sin dependencias ni build: el export de Stitch es HTML/CSS estático y se sirve tal cual.

## Flujo

1. Rellenar `brief.md`.
2. Generar el diseño en Stitch y descargar el código.
3. Descomprimir en `public/` (sustituyendo el `index.html` placeholder).
4. Revisar responsive, enlaces y textos.
5. Lo demás (formulario de contacto, analítica, deploy) cuando toque.

## Pendiente

- Dominio y hosting.
- Datos reales del negocio (nombre, dirección, teléfono, horarios, redes).
- Destino del formulario de contacto.
