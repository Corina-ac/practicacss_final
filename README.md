
## Descripción del proyecto

Sitio web estático de varias páginas construido con **HTML5 semántico** y **CSS3**,
desarrollado como práctica final del curso de Fundamentos Web 2026.  
El proyecto presenta un perfil profesional personal con secciones de objetivos,
intereses, multimedia, formularios y un portafolio que documenta el viaje de
aprendizaje en desarrollo web, incluyendo la explicación y demostración visual
de los principales conceptos de CSS.


## Estructura de carpetas

PracticaCSS/
├── index.html                  # Página principal (Perfil Profesional)
├── README.md                   # Documentación del proyecto
│
├── pages/                      # Vistas secundarias del sitio
│   ├── portafolio.html         # Portafolio CSS y conceptos de diseño
│   ├── buscar.html             # Página de búsqueda (Procesamiento de formulario GET)
│   └── cto/
│       └── contacto.html       # Formulario de contacto
│
├── css/                        # Hojas de estilo estructuradas
│   ├── general.css             # Estilos compartidos (Navbar, Footer, Reset)
│   ├── index.css               # Estilos específicos de index.html
│   ├── portafolio.css          # Estilos específicos de portafolio.html
│   ├── buscar.css              # Estilos específicos de buscar.html
│   └── contacto.css            # Estilos específicos de contacto.html
│
├── img/                        # Recursos gráficos estáticos
│   ├── mundito.ico             # Ícono de la pestaña del navegador (Favicon)
│   └── espe/
│       └── imagenEjemploEspe.png
│
├── audio/                      # Archivos de audio locales
│   └── audioEjemploA7X.mp3
│
└── video/                      # Recursos de video locales
    └── videoEjemploDiagnostica.mp4

## Capturas de pantalla

> Las capturas se pueden agregar aquí una vez que el sitio esté desplegado.
> - Página principal (`index.html`) — perfil, intereses y multimedia
<img width="1137" height="615" alt="image" src="https://github.com/user-attachments/assets/017d80ba-6768-4513-86d3-1f62ed2e2f93" />

> - Portafolio (`portafolio.html`) — tarjetas de proyecto y grid de conceptos CSS
<img width="401" height="492" alt="image" src="https://github.com/user-attachments/assets/a6b149f4-b2fc-4cba-9ec0-7ae0ae9e2d11" />
<img width="544" height="532" alt="image" src="https://github.com/user-attachments/assets/7400a09c-4ed6-4e22-9666-83ab04928978" />

> - Búsqueda (`buscar.html`)
<img width="840" height="247" alt="image" src="https://github.com/user-attachments/assets/c4f4b2dc-77a3-4cf4-be1a-624e706b4efa" />

---

## Tecnologías utilizadas

|    **Tecnología**    |                       **Uso**                       |
|----------------------|-----------------------------------------------------|
| **HTML5**            | Estructura semántica de todas las páginas           |
| **CSS3**             | Estilos visuales, Flexbox, Grid y diseño responsivo |
| **Font Awesome 6.5** | Íconos en navegación y artículos (CDN)              |
| **Media Queries**    | Adaptación del diseño a pantallas pequeñas          |

### Conceptos de CSS aplicados

- **Colores, fuentes y fondos** — paleta verde `#1b7505`, dorado `#dba112`, oscuro `#0d1910`
- **Bordes, margen y relleno** — espaciado consistente en tarjetas y secciones
- **Modelo de caja** — `box-sizing: border-box` en todos los elementos
- **Display** — `block`, `inline-block`, `flex` y `grid` según el contexto
- **Posicionamiento** — `relative` y `float` para figuras; `sticky` disponible para nav
- **Flexbox** — menú de navegación y disposición de elementos en fila
- **CSS Grid** — sección de conceptos CSS en `portafolio.html`
- **Media Queries** — diseño responsivo para pantallas de 700 px o menos

---

## Información del autor

|       **Campo**     |               **Detalle**               |
|---------------------|-----------------------------------------|
| **Nombre**          | Corina Acosta                           |
| **Institución**     | Universidad de las Fuerzas Armadas ESPE |
| **Curso**           | Fundamentos Web                         |
| **Periodo**         | 2026                                    |
| **País**            | Ecuador                                 |
