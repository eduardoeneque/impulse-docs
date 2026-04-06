# impulse-docs

**Impulse Artifacts & Documentation Hub**

Repositorio público con todos los diagnósticos, análisis, blueprints y documentación de la construcción del Sistema Operativo de Impulse.

## 📁 Estructura

```
impulse-docs/
├── index.html                 # Hub central (página de inicio)
├── diagnosticos/              # Análisis y diagnósticos
│   └── Diagnostico_Comercial_Impulse_Q2_2026.html
├── agentes/                   # Blueprints de agentes Conversia
├── procesos/                  # Mapas y rediseño de procesos
└── README.md
```

## 🚀 Acceso

El repositorio se publica automáticamente en GitHub Pages:

**URL:** `https://eduardoeneque.github.io/impulse-docs/`

Todos los cambios en la rama `main` se despliegan automáticamente.

## 📝 Cómo agregar nuevos artefactos

1. Crea el artefacto (HTML, documento, etc.)
2. Copia el archivo a la carpeta correspondiente:
   - `diagnosticos/` para análisis
   - `agentes/` para blueprints de Conversia
   - `procesos/` para mapas operacionales
3. Actualiza `index.html` con un link al nuevo artefacto
4. Haz commit y push:
   ```bash
   git add .
   git commit -m "Add: nombre del artefacto"
   git push origin main
   ```

## 🔐 Privacidad

Este repositorio es **público**. No agregues información sensible, credenciales o datos privados. Usa la rama `main` solo para contenido apropiado para compartir con el equipo.

---

**Última actualización:** Abril 2026
**Mantenedor:** Eduardo Eneque (Impulse)
