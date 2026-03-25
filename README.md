# Central Management

Task tracker personal para Latin Securities. Gestión de tareas por prioridad, secciones y seguimiento diario.

## Uso

1. Abrí `index.html` en tu navegador (Chrome / Edge recomendado).
2. No requiere servidor ni instalación.

## Funcionalidades

- **Central Management** — Listado de tareas con prioridad por color, descripción y estado/seguimiento
- **A Escribir** — Personas y temas pendientes de comunicar
- **Tiempo Libre** — Links y recursos para leer
- **Reuniones** — Notas de reuniones con carpetas y búsqueda
- **Claude** — Ideas y prompts personales

## Colores de prioridad

| Color | Significado |
|---|---|
| 🔴 Rojo | Urgente |
| 🟠 Naranja | En proceso |
| 🔵 Azul | Esperando |
| 🟣 Violeta | A revisar |
| 🟢 Verde | Listo / OK |
| ⚫ Gris | Cerrado |

## Tareas completadas

- Hacé clic en **✓** a la derecha de una tarea para completarla.
- Las completadas se mueven al panel **Completadas** (abajo del listado).
- Hacé clic en **↩** para devolver una tarea al listado activo.

## Edición inline

- **Doble clic** en cualquier celda para editar.
- **Tab** para pasar a la siguiente celda.
- **Escape** para cancelar.

## Persistencia

Los datos se guardan automáticamente en **localStorage** del navegador. Persisten al cerrar y reabrir la pestaña.

> Para backup: abrí la consola del navegador (F12) y ejecutá:
> ```js
> copy(localStorage.getItem('tt_v10'))
> ```
> Eso copia el JSON al portapapeles para guardarlo.

## Estructura del proyecto

```
/
├── index.html    # App completa (todo en un archivo)
├── README.md     # Este archivo
└── .gitignore
```

## GitHub

```bash
git init
git add index.html README.md .gitignore
git commit -m "Initial commit: Central Management task tracker"
git remote add origin https://github.com/TU_USUARIO/central-management.git
git push -u origin main
```
