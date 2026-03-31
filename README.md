# 🏘️ Vecinity
**La red de tu comunidad en Pilar.**

Vecinity es una plataforma web diseñada para conectar a vecinos de barrios cerrados y comunidades de Pilar. Permite el registro de "vecinos" y la visualización de servicios locales, utilizando una arquitectura ligera basada en HTML5, Tailwind CSS y Google Sheets como base de datos.

## 🚀 Características
- **Registro de Vecinos:** Formulario integrado que envía datos en tiempo real.
- **Base de Datos Serverless:** Conexión directa con Google Sheets mediante Google Apps Script.
- **Diseño Responsivo:** Optimizado para móviles y escritorio con Tailwind CSS.
- **Hosting Gratuito:** Desplegado mediante GitHub Pages.

## 🛠️ Tecnologías
- **Frontend:** HTML5, JavaScript (ES6+), Tailwind CSS.
- **Backend/DB:** Google Apps Script (GAS) + Google Sheets.
- **Iconos:** Lucide Icons.

## ⚙️ Configuración del SDK de Datos
Para que el formulario funcione, el archivo `index.html` debe contener la URL de tu implementación de Google Apps Script:

```javascript
const url = "TU_URL_DE_APPS_SCRIPT_AQUI";
