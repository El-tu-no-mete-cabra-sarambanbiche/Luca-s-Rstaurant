# Colegio Valle Central

Portal institucional responsive para estudiantes, docentes y familias, preparado para publicarse en GitHub Pages.

## Incluye

- Inicio de sesión visual con perfiles de estudiante y docente.
- Enlace al sitio oficial del Ministerio de Educación Pública (MEP).
- Directorio de docentes con filtros por departamento.
- Horarios de atención institucional.
- Calendario de feriados, celebraciones, vacaciones y días libres.
- Comunicados y avisos escolares.
- Diseño adaptable para teléfono, tablet y escritorio.

## Ejecutar localmente

Abre `index.html` en el navegador o sirve la carpeta con:

```powershell
python -m http.server 8000
```

Visita `http://localhost:8000`.

## Archivos

```text
.
├── index.html
├── Restaurante.html
└── README.md
```

`Restaurante.html` conserva la URL anterior y redirige a `index.html`.

## Importante sobre el inicio de sesión

El formulario de acceso es un prototipo front-end: no guarda ni valida credenciales. Antes de usarlo con estudiantes o docentes, debe conectarse a un sistema real de autenticación con HTTPS, almacenamiento seguro y control de permisos. El botón del MEP dirige al sitio oficial para trámites y consultas institucionales.

## Publicar en GitHub Pages

1. Sube los archivos a la rama `main` del repositorio.
2. Ve a **Settings > Pages**.
3. Selecciona `Deploy from a branch`, rama `main` y carpeta `/root`.
4. Guarda y abre la URL generada por GitHub Pages.
