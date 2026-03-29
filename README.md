# 🚀 LauncherScripts
### *Tu biblioteca personal de scripts, desplegada al instante.*

<p align="center">
  <a href="https://launcherscripts.vercel.app/">
    <img src="https://img.shields.io/badge/VISITAR_APP-VIVO-3fb950?style=for-the-badge&logo=vercel&logoColor=white" alt="Visitar App">
  </a>
</p>

---

**LauncherScripts** es una Single Page Application (SPA) diseñada para transformar tu perfil de GitHub en un panel interactivo de herramientas. Organiza tus repositorios como aplicaciones individuales, permitiéndote explorar su documentación y descargarlos con un solo clic.

## 🔥 Funcionalidades Estrella

### 🎨 Diseño Híbrido Profesional
* **Cabecera Dark Permanente:** La zona de búsqueda y navegación se mantiene en negro profundo para un contraste elegante.
* **Cuerpo Light Refinado:** El contenido utiliza el gris suave oficial de GitHub (`#f6f8fa`), evitando la fatiga visual.
* **Modo Dual:** Cambia entre tema claro y oscuro con un solo clic; la app recordará tu elección.

### 📥 Descarga Inteligente (Smart Fetch)
El sistema analiza el contenido del repositorio para ofrecerte la mejor opción:
* **Repositorios Completos:** Si tiene más de 3 archivos, descarga un **paquete ZIP**.
* **Scripts Ligeros:** Si tiene 3 o menos, descarga directamente el archivo `.py` y el `README.md`.

### 📱 Experiencia Móvil Optimizada
* **Interfaz Adaptable:** Los botones y tarjetas se ajustan automáticamente para ser fáciles de tocar en pantallas pequeñas.
* **Nombres Limpios:** Los nombres de los repositorios se formatean automáticamente para que se vean impecables (ej. `mi-script__` ➔ **Mi Script**).

---

## 📖 Visor de Documentación
El botón de **Detalles** abre un visor que renderiza el `README.md` original del repositorio. Gracias a la integración con `github-markdown-css`, verás las tablas, códigos y negritas tal cual aparecen en GitHub.

---

## 🛠️ Stack Tecnológico
* **Frontend:** HTML5, CSS3, JavaScript (ES6+).
* **Renderizado:** `github-markdown-css` para una estética nativa.
* **API:** GitHub REST API.
* **Hosting:** [Vercel](https://vercel.app).

---

## 🚀 Cómo usarlo
1. **Sube tus scripts** a repositorios individuales en GitHub.
2. **Añade un README.md** con las instrucciones de cada script.
3. **Entra en [LauncherScripts](https://launcherscripts.vercel.app/)**, pon tu usuario y ¡listo!

---

<p align="center">
  Hecho con ❤️ para la comunidad de desarrolladores.
</p>
