# 📱 Curso de Web Responsive

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Responsive Design](https://img.shields.io/badge/Design-Responsive-brightgreen?style=for-the-badge)](https://web.dev/learn/design)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

Este repositorio contiene las prácticas, maquetación y ejercicios del **Curso de Desarrollo Web Responsive**. El objetivo principal es la creación de un sitio web adaptativo que proporcione una experiencia fluida y optimizada en dispositivos móviles, tablets y ordenadores de escritorio.

---

## 🚀 Características del Proyecto

- 📱 **Enfoque Mobile-First**: Estructura diseñada inicialmente para dispositivos móviles y escalada progresivamente hacia pantallas de mayor tamaño.
- 📐 **Media Queries & Breakpoints**: Adaptación precisa del contenido según la resolución de la pantalla.
- 📦 **Maquetación Moderna**: Uso combinado de **CSS Flexbox** y **CSS Grid** para la distribución eficiente de componentes.
- 📏 **Unidades Relativas**: Implementación de `rem`, `em`, `%`, `vw` y `vh` para garantizar tipografías e imágenes fluidas.
- ⚙️ **Interactividad mediante Scripts**: Incorporación de lógica dinámicas e interacciones frontend.

---

## 📂 Estructura del Proyecto

```text
responsive-web-curso/
├── assets/
│   ├── css/
│   │   ├── styles.css        # Estilos globales y diseño base
│   │   └── responsive.css    # Reglas CSS adaptativas y Media Queries
│   ├── js/
│   │   └── main.js           # Lógica e interacciones dinámicas
│   └── img/                  # Recursos multimedia optimizados
├── index.html                # Documento principal HTML5
├── README.md                 # Documentación del proyecto
└── LICENSE                   # Licencia del proyecto
```

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Maquetación semántica y estructuración del contenido.
- **CSS3**: Estilos, transiciones y diseño responsivo (*Flexbox/Grid*).
- **JavaScript (ES6+)**: Funcionalidades interactivas y manipulaciones del DOM.
- **XAMPP / Apache**: Entorno de servidor web local para la ejecución del proyecto.

---

## 💻 Instrucciones de Instalación y Ejecución en Localhost

⚠️ **Requisito Importante:** Para asegurar el correcto funcionamiento de los scripts y la resolución adecuada de rutas, **el proyecto debe ejecutarse a través de un servidor local (Localhost)** bajo el protocolo HTTP (`http://`), evitando abrir el archivo directamente con `file://`.

### Pasos para ejecutar con XAMPP:

1. **Acceder a la carpeta del servidor:**  
   Dirígete al directorio `htdocs` de tu instalación de XAMPP:
   - **Windows:** `C:/xampp/htdocs/`
   - **macOS:** `/Applications/XAMPP/htdocs/`
   - **Linux:** `/opt/lampp/htdocs/`

2. **Clonar el repositorio:**  
   Abre una terminal o consola de comandos en la ruta anterior y ejecuta:
   ```bash
   cd C:/xampp/htdocs/
   git clone [https://github.com/Selectron8/responsive-web-curso.git](https://github.com/Selectron8/responsive-web-curso.git)
   ```

3. **Iniciar el servidor Apache:**  
   - Abre el panel de control **XAMPP Control Panel**.
   - Haz clic en **Start** junto al servicio **Apache**.

4. **Abrir en el navegador:**  
   Abre tu navegador web e ingresa la siguiente URL:
   ```text
   http://localhost/responsive-web-curso/
   ```

---

## 👤 Autor

Desarrollado por **Selectron8** como parte del proceso de formación en desarrollo frontend responsivo.

- **GitHub**: [@Selectron8](https://github.com/Selectron8)

---

## 📄 Licencia

Este proyecto está bajo la Licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más detalles.
