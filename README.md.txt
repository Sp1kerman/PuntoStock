# 🛒 PuntoStock v1.0

> Prototipo SPA (Single Page Application) minimalista diseñado para la gestión de costos, control de inventario y sugerencia de precios en comercios de proximidad y almacenes.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🚀 Características Principales

- **Cálculo automatizado de costos y precios:** Permite ingresar costos por presentación, ajustes de IVA personalizados y porcentajes de recargo comercial para obtener sugerencias de precios unitarios y por mayor.
- **Gestión de Catálogo y Stock:** Registro de productos activos/inactivos, códigos internos autogenerados y control de precios de la competencia.
- **Resiliencia y Manejo de Errores:** Validación de esquemas de datos en `localStorage`, manejo de excepciones ante fallos de almacenamiento local y protección contra doble envío en formularios.
- **Exportación de Datos:** Funcionalidad nativa para exportar catálogos e historiales de compras directamente a formato **CSV** o generar respaldos estructurados en **JSON**.
- **Interfaz Adaptativa (Responsive):** Diseño optimizado para dispositivos móviles y de escritorio utilizando CSS Grid y Flexbox sin dependencias de frameworks externos.

## 🛠️ Tecnologías Utilizadas

- **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3 (Variables, Grid, Flexbox).
- **Persistencia:** Almacenamiento local del navegador (`localStorage`) con validación de integridad.
- **Arquitectura:** Patrón de SPA ligera basada en un único archivo (`index.html`), priorizando la velocidad de carga y portabilidad.

## 💻 Instalación y Uso Local

No requiere instalación de dependencias ni Node.js. 

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/puntostock.git](https://github.com/TU_USUARIO/puntostock.git)