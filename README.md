# JYNTRA

Conjunto de aplicaciones web de JYNTRA, cada una como un archivo HTML autocontenido.

## Contenido del repositorio

| Archivo | Descripción | Versión |
|---|---|---|
| `index.html` | Página de inicio con enlaces a todas las apps | - |
| `jyntra-app_v10.html` | App principal | v10 |
| `jyntra-profesor_v12.html` | Vista/app para profesores | v12 |
| `jyntra-alumno_v14.html` | Vista/app para alumnos | v14 |
| `jyntra-nutricionista_v8.html` | Vista/app para nutricionistas | v8 |

## Uso

Abre `index.html` en un navegador para acceder a todas las apps desde un solo lugar, o abre cualquiera de los archivos individuales directamente.

## Publicar con GitHub Pages

1. Ve a **Settings → Pages** en este repositorio.
2. En **Source**, selecciona la rama principal (`main`) y la carpeta `/root`.
3. Guarda. GitHub Pages publicará el sitio en unos minutos en una URL del tipo:
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Notas

- Cada archivo es HTML autocontenido (sin build ni dependencias externas de servidor).
- Verifica que no existan rutas absolutas a archivos locales (por ejemplo `file:///...` o rutas de tu computador) que puedan romperse al desplegar en Pages.
