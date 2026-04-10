 <p https://mail.google.com/mail/u/1/popout?ver=1hqlrwwz6hrsu#attid%253Datt_19d6f22e534db975_0.1_f_mnqlm8aw0/p>

## 📍 Madrid Event Hub
Actualmente estoy desarrollando **Eventos Madrid**, una plataforma interactiva diseñada para que nadie se pierda lo que pasa en la capital.

### 🌟 El Proyecto
Mi objetivo es crear una herramienta sencilla pero potente que centralice la agenda cultural de Madrid. No más saltar entre 20 webs diferentes; todo lo que necesitas saber sobre conciertos, mercados y festivales está aquí.

---

### 🛠️ ¿Cómo está construido?

Este proyecto utiliza un enfoque híbrido entre automatización y simplicidad en el frontend:

* **🤖 Automatización (Backend "Serverless"):** Utilizo **Python** para scrapear semanalmente las APIs oficiales del Ayuntamiento y la Comunidad de Madrid. Gracias a **GitHub Actions**, el script se ejecuta solo, procesa los datos y actualiza un archivo `events.json`.
* **🗺️ Mapa Interactivo:** Construido con **Vanilla JS**. El mapa muestra los eventos con pines de colores o emojis según la categoría.
* **🧩 Experiencia de Usuario:**
    * **Clustering:** Los pines se agrupan al alejar el zoom para mantener la claridad.
    * **Popups Detallados:** Información completa (fecha, precio, link) a un solo click.
    * **Geolocalización:** El sistema calcula la distancia exacta desde tu ubicación al evento.
    * **Filtros Inteligentes:** Por fecha (hoy, finde), precio o categorías.
    * **Modo Oscuro:** Porque los mejores eventos se planean de noche. 🌙

### 🚀 Stack Tecnológico

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
</p>

---
*Transformando datos públicos en experiencias ciudadanas.* 🏛️✨
"""
