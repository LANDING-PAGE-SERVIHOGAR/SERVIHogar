# SERVIHogar – Landing Page

Plataforma que conecta a familias con trabajadores de servicios domésticos verificados (limpieza, cocina, jardinería, gasfitería) en Lima, Perú.

## Estructura del proyecto

```
servihogar/
├── index.html        # Página principal del Landing Page
├── css/
│   └── styles.css    # Estilos del sitio (variables, componentes, responsive)
├── js/
│   └── main.js       # Interacciones: navbar, sliders, modales, buscador, etc.
└── assets/           # Imágenes y recursos multimedia
```

## Gestión del código fuente

El control de versiones se maneja en GitHub sobre una sola rama, **main**, que contiene siempre la versión estable del Landing Page. Los mensajes de commit siguen el formato de **Conventional Commits**:

- `feat:` nueva sección o funcionalidad
- `fix:` corrección de errores
- `style:` ajustes visuales sin cambios de lógica
- `docs:` cambios en documentación

## Despliegue

El sitio se publica mediante **GitHub Pages**, desplegando directamente desde la rama `main` (carpeta raíz). Cualquier cambio subido a `main` actualiza automáticamente el sitio publicado.

## Historias de usuario implementadas en el Landing Page

| ID | Descripción | Sección |
|----|-------------|---------|
| HU01 | Registrar nuevos usuarios | Modal de registro |
| HU02 | Iniciar sesión | Modal de login |
| HU06 | Buscar trabajadores por categoría | Buscador (navbar) + sección de profesionales |
| HU08 | Ver perfiles de trabajadores | Modal de perfil profesional |
| HU11 | Solicitar un servicio | Botón en modal de perfil |
