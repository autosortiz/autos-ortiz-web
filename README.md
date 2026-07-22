# Ortiz Automotriz

Página web de exhibición y venta de vehículos seminuevos verificados.

🌐 **Demo live:** https://autosortiz.github.io/autos-ortiz-web/
🌍 **Dominio personalizado:** https://ortizautomotriz.com/

## Características

- 🎨 Diseño dark theme premium, responsive
- 🚗 Inventario con fotos, precio antes/después y descuento
- 💬 Botón WhatsApp por vehículo con mensaje prellenado
- 🔍 Filtros por marca, año, precio, combustible y transmisión
- 📱 100% responsive — celular, tablet y desktop

## Tech Stack

- HTML5 + CSS3 + JavaScript vanilla
- Sin dependencias ni frameworks
- Google Fonts (Montserrat + Inter)
- **Backend:** Google Apps Script + GitHub API
- **Admin:** Panel de gestión con upload de fotos y CRUD completo

## Admin Panel

🔗 **https://autosortiz.github.io/autos-ortiz-web/admin/**

Funciones del admin:
- ➕ Agregar / Editar / Eliminar autos
- 📷 Upload de fotos directo al repo (arrastrar o clic)
- 📥 Importar varios autos desde archivo JSON
- 🔍 Buscador en tiempo real
- 📊 Estadísticas del inventario

## Backend

- **Apps Script:** Gestiona el archivo `autos.json` en el repo via GitHub API
- **Token:** GitHub PAT (classic) con acceso `repo`
- **Acciones:** `read`, `write`, `uploadImage`, `importJson`

## Publicar cambios

Los cambios se publican automáticamente via **GitHub Pages** desde la branch `main`.

> URL GitHub Pages: https://autosortiz.github.io/autos-ortiz-web/
> Dominio personalizado: https://ortizautomotriz.com/

## Estructura

```
autos-ortiz-web/
├── index.html          # Sitio público
├── autos.json          # Datos de inventario
├── admin/
│   └── index.html      # Panel de administración
├── img/autos/          # Fotos de los vehículos
└── README.md
```

---

© 2026 Ortiz Automotriz — Todos los derechos reservados
Desarrollado por CeluCenter MX
