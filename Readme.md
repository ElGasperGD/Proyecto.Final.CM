# Proyecto Final: HTML y CSS — Catálogo de Motos

## Descripción

Sitio web estático hecho con HTML5 y CSS3 como práctica del taller. Tiene tres páginas:
`index.html` (inicio), `tablas.htm` (catálogo de motos) e `imagenes.html` (galería).
Todas comparten el mismo tema oscuro, tarjetas con sombras, bordes redondeados y
animaciones al pasar el cursor.

## Objetivos

- Practicar HTML semántico (`header`, `nav`, `main`, `section`, `footer`).
- Usar CSS moderno: variables, `flexbox`, degradados y transiciones.
- Armar una navegación responsive que siempre se vea, sin menú hamburguesa.
- Practicar Git en equipo: ramas, commits, Pull Requests y tags.

## Tecnologías

- **HTML5** — estructura de las páginas y la tabla.
- **CSS3** — estilos, variables, `flexbox`, sombras y animaciones.
- **Git / GitHub** — control de versiones, revisiones y releases.
- **VS Code** — editor y Live Server para probarlo en el navegador.

## Estructura

```
Proyecto.Final.CM/
├── index.html      # Inicio
├── tablas.htm      # Catálogo de motos (tabla)
├── imagenes.html   # Galería
├── style.css       # Estilos del inicio
├── Tablas.css      # Estilos del catálogo
├── README.md
├── historial.md
├── reflexion.md
└── .gitignore
```

## Instalación

No tiene dependencias, es solo código estático. Se clona el repositorio:

```bash
git clone https://github.com/ElGasperGD/Proyecto.Final.CM.git
cd Proyecto.Final.CM
```

## Ejecución

Con **Live Server** en VS Code: clic derecho en `index.html` → *Open with Live Server*.

O con Python:

```bash
python -m http.server 8000
```

Y abrir `http://localhost:8000`.

## Flujo de trabajo con Git

1. `master` queda protegida: solo entra código por Pull Request aprobado.
2. Cada funcionalidad se hizo en su rama `feature/...`.
3. Commits pequeños con mensajes claros: `feat:`, `style:`, `fix:`.
4. Cada rama se subió y se abrió un PR para revisión del compañero.
5. Con los cambios corregidos se aprobó y se hizo merge a `master`.

```bash
git add .
git commit -m "Mensaje"
git pull Cargar todos los cambios
git push Subir todos los cambios
```

## Autores

- **Cristian Jaramillo** — Estructura HTML y tablas.
- **Jonathan Logaña** — Estilos CSS, imágenes y apartado gráfico.