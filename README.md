
# Contenido del archivo Markdown
# 📍 Madrid Event Hub: Mapa Interactivo de Eventos Culturales

 Este es el repositorio principal de **Madrid Event Hub**, una plataforma interactiva diseñada para descubrir todo lo que sucede en la capital española: desde conciertos y mercadillos hasta festivales gastronómicos.

## 🚀 El Proyecto

El objetivo es centralizar la oferta cultural de Madrid utilizando datos abiertos de las APIs oficiales del Ayuntamiento y la Comunidad de Madrid. El sistema es totalmente autónomo y está construido con un enfoque de "Zero-Back-End" mediante archivos estáticos dinámicos.

### 🛠️ ¿Cómo funciona?

1.  **Automatización (Python + GitHub Actions):** Cada semana, un script de Python actúa como *scraper* y colector de datos de las APIs oficiales.
2.  **Almacenamiento:** Los datos se procesan y se guardan en un archivo `events.json` centralizado que sirve como base de datos ligera.
3.  **Frontend (Vanilla JS):** La web consume ese JSON y renderiza un mapa interactivo sin necesidad de frameworks pesados.

## ✨ Características Principales

-   **🗺️ Mapa Inteligente:** Visualización de eventos mediante pines. Implementación de **Marker Clustering** para evitar el desorden visual al alejar el zoom.
-   **🎨 Categorización Visual:** Cada categoría de evento tiene su propio color o emoji identificativo.
-   **🔍 Filtros Avanzados:**
    -   Por fecha (Hoy, este fin de semana, etc.).
    -   Por precio (Gratis vs. De pago).
    -   Por categoría.
    -   Buscador de texto integrado.
-   **📍 Geolocalización:** El sitio calcula automáticamente la distancia entre tu ubicación actual y el evento.
-   **🌗 Dark Mode:** Interfaz adaptada para una visualización cómoda en cualquier momento del día.
-   **ℹ️ Detalles en un Click:** Popups informativos con nombre, fecha, precio y enlace directo a la entrada o fuente oficial.

## 🧰 Stack Tecnológico

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E3.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

---
*Proyecto en desarrollo constante para conectar a los madrileños con su cultura.*
