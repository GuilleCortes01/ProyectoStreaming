# 🎬 Rolling Movies

Rolling Movies es una plataforma de streaming de películas y series. Es un proyecto grupal hecho con **HTML, CSS y Bootstrap**. El sitio tiene un catálogo organizado por géneros, la página de detalle de una película con su tráiler, inicio de sesión, registro y un formulario de pago para la suscripción.

---

## 👥 Integrantes

- Cesar Nahum Saravia
- Guillermo Augusto Cortes
- Santino Michaelsen Carmona
- Bautista Garcia Moreno
- Fernanda Villacis Barrionuevo

---

## 🛠️ Tecnologías

- **HTML5**
- **CSS3** (con variables CSS para colores y tipografías)
- **Bootstrap 6** (por CDN)
- **Google Fonts** (DM Sans)
- **Git y GitHub** para trabajar en equipo

---

## 📄 Páginas

| Página | Descripción |
|---|---|
| `index.html` | Inicio, con un carrusel de títulos destacados y secciones de películas y series |
| `peliculas.html` | Catálogo de películas por género: Terror, Acción y aventura, Fantasía, Romance y drama |
| `serie.html` | Catálogo de series por género: Acción y aventura, Drama y comedia, Anime |
| `terror.html` | Detalle de la película *It (2017)* |
| `reproductor.html` | Reproductor con el tráiler de *It* |
| `login.html` | Inicio de sesión |
| `registro.html` | Formulario de registro de usuario |
| `suscripcion.html` | Planes y formulario de pago |
| `404.html` | Página de error para las secciones que todavía no existen |

---

## ✨ Funcionalidades

- **Diseño responsive**: se adapta a celulares, tablets y computadoras.
- **Barra de navegación** con menú hamburguesa en pantallas chicas.
- **Carrusel** de títulos destacados en la página de inicio.
- **Tarjetas** de películas y series con póster, edad mínima, tipo y año.
- **Validación de formularios** en el registro, el inicio de sesión y el pago:
  - Campos obligatorios y con largo mínimo y máximo.
  - Nombre y apellido solo con letras.
  - Formato de email válido.
  - Contraseña de 8 a 20 caracteres, con al menos una mayúscula, una minúscula y un número.
  - Número de tarjeta de 16 dígitos, vencimiento con formato `MM/AA` y CVV de 3 o 4 dígitos.
- **Reproductor de video** con el tráiler de una película.
- **Página 404** para los enlaces que todavía no tienen contenido.
- **Footer** e **ícono de pestaña (favicon)** en todas las páginas.

---

## 📁 Estructura del proyecto

```
ProyectoStreaming/
├── index.html
├── peliculas.html
├── serie.html
├── terror.html
├── reproductor.html
├── login.html
├── registro.html
├── suscripcion.html
├── 404.html
├── estilos/
│   ├── style.css           # Variables y estilos base
│   ├── nav.css
│   ├── carrusel.css
│   ├── PaginaPrincipal.css
│   ├── peliculas.css
│   ├── serie.css
│   ├── terror.css
│   ├── reproductor.css
│   ├── login.css
│   ├── suscripcion.css
│   └── 404.css
├── img/                    # Pósters, imágenes del carrusel y favicon
└── videos/                 # Tráiler
```

---

## 🚀 Cómo ver el proyecto

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/GuilleCortes01/ProyectoStreaming.git
   ```
2. Entrá a la carpeta del proyecto:
   ```bash
   cd ProyectoStreaming
   ```
3. Abrí `index.html` en el navegador. También podés usar la extensión **Live Server** de VS Code.

No hace falta instalar nada: Bootstrap y las fuentes se cargan desde internet.

---

## 🌿 Cómo trabajamos

- `main`: versión estable del proyecto.
- `dev`: rama de desarrollo, donde se unen las funcionalidades nuevas.
- Para cada tarea se crea una rama a partir de `dev`, con estos prefijos:
  - `feat/` para funcionalidades nuevas (ej: `feat/peliculas-series`)
  - `fix/` para correcciones (ej: `fix/carrusel`)
  - `refactor/` para reorganizar código
- Los cambios se suben a `dev` con **Pull Requests** en GitHub, para que el equipo pueda revisarlos.

