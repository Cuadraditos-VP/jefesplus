# Programación Jefes — Septiembre 2026

App web (un solo HTML + un JSON) para ver y solicitar cambios de turnos.

## Archivos para GitHub

Subí **estos dos archivos** a la raíz del repositorio:

| Archivo | Para qué sirve |
|---------|----------------|
| `index.html` | La aplicación |
| `septiembre-2026.json` | Programación oficial que ven todos |

Opcional: este `README.md`.

## Publicar con GitHub Pages

1. Creá un repositorio nuevo en GitHub (puede ser privado o público).
2. Subí `index.html` y `septiembre-2026.json` a la **raíz**.
3. En el repo: **Settings → Pages**.
4. Source: **Deploy from a branch**.
5. Branch: `main` (o `master`), carpeta `/ (root)`.
6. Guardá. En uno o dos minutos la URL queda así:

   `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`

Esa es la dirección que usan los jefes (pueden agregarla a la pantalla de inicio del celular).

## Cómo se actualiza la programación para todos

1. Un jefe pide un cambio y lo **envía por WhatsApp** (con código de solicitud).
2. El admin entra con usuario `ADMIN` y ve **Solicitudes**.
3. **Aprobar** → la app ofrece descargar `septiembre-2026.json`.
4. En GitHub, **reemplazá** el archivo `septiembre-2026.json` por el que descargaste (puedes arrastrarlo en la web de GitHub → Commit).
5. En unos minutos los celulares toman el cambio solos (la app consulta el JSON cada ~3 minutos).

Si **rechazás**, la app ofrece copiar un mensaje para avisarle al jefe por WhatsApp.

## Ingreso

| Rol | Usuario | Clave |
|-----|---------|-------|
| Administrador | `ADMIN` | `1318` |
| Jefe | Su **legajo** (ej. `60219`) | El **mismo legajo** |

- Cada jefe solo puede pedir cambios en **su** fila.
- El admin puede editar todo, ver solicitudes, exportar/importar JSON.

## Notas

- Los cambios locales (pendientes) se guardan en el navegador de cada celular hasta que el admin actualiza el JSON en GitHub.
- No hace falta instalar nada: es una página web.
- Si cambiás solo el HTML, los que ya tenían la app abierta la recargan solos cada ~20 minutos, o pueden refrescar a mano.
