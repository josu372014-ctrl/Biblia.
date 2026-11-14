# Palabra Viva

App web cristiana: Biblia Reina-Valera 1909 (dominio público), devocional diario con racha de lectura y recordatorios, estudios, teoría, historias, profetas con fechas, bosquejos, asistente para predicar, evangelismo y asistente de aliento. Se puede instalar en el celular.

## Publicar en GitHub Pages
1. Crea un repositorio y sube todos estos archivos a la raíz (incluido `biblia.json`, que pesa unos 4 MB).
2. En Settings, Pages, elige la rama `main` y la carpeta `/ (root)`.
3. Abre el enlace. En el celular usa "Agregar a pantalla de inicio".

## Archivos
- `index.html`: la app
- `data.js`: estudios, historias, profetas, bosquejos y devocionales (puedes editarlos)
- `biblia.json`: texto de la Biblia
- `sw.js`, `manifest.webmanifest`, `icon.svg`: instalación, uso sin internet y recordatorios

## Sobre los recordatorios
Funcionan mientras la app está abierta o instalada. Un sitio estático no puede enviar notificaciones con la app totalmente cerrada; en Android con la app instalada, Chrome puede despertarla de vez en cuando.
