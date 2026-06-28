# Desafío: Calculadora de Total de Producto
*Este proyecto consiste en la implementación de una interfaz interactiva para una tienda en línea. El objetivo principal es manipular el DOM (Document Object Model) mediante JavaScript para gestionar la cantidad de productos seleccionados y calcular dinámicamente el costo total a pagar.*

---
## Desafío: Calculadora de Total de Producto

[![Demo en Vivo](https://img.shields.io/badge/Ver-Proyecto-brightgreen?style=for-the-badge&logo=github)](https://jleival.github.io/desafio1-javascript-calculando-el-total/)

Este proyecto consiste en la implementación de una interfaz interactiva para una tienda en línea...
---
## 🚀 Descripción del Proyecto
La aplicación permite al usuario interactuar con una tarjeta de producto "Laptop Gamer AMD". A través de botones de incremento (+) y decremento (-), el usuario puede ajustar la cantidad deseada, viendo en tiempo real cómo se actualiza el subtotal en la interfaz.

**Funcionalidades clave:**
* **Manipulación del DOM:** Actualización dinámica de elementos HTML mediante querySelector e innerHTML.

* **Gestión de Eventos:** Uso del atributo onclick para disparar la lógica de cálculo ante la interacción del usuario.

* **Cálculo Dinámico:** Lógica matemática integrada para reflejar el costo total basado en el precio base y la cantidad actual.

---
## 🛠️ Tecnologías Utilizadas
* HTML5: Estructura semántica del contenido.

* CSS3: Estilizado de la tarjeta de producto, disposición (Flexbox) y diseño responsivo.

* JavaScript: Manipulación del DOM.

---
## ⚙️ Implementación Técnica
Para lograr la interactividad, se implementaron las siguientes funciones dentro del archivo script.js (refactorizando el código para mayor legibilidad) o directamente en los eventos onclick del HTML:

1. Variables de Estado: Se definieron *precio* (constante) y cantidad (variable de estado).

2. Lógica de Incremento: Al presionar el botón *+*, la variable *cantidad* aumenta, actualizando el nodo del DOM correspondiente a la cantidad y multiplicando por el precio para actualizar el *total*.

3. Lógica de Decremento: Similar al incremento, con una validación básica para evitar valores negativos si es necesario.

---
## 📂 Estructura del Proyecto

```text
├── assets/
│   ├── css/
│   │   └── style.css      # Hojas de estilo
│   ├── js/
│   │   └── script.js      # Lógica de JavaScript
│   └── img/
│       └── laptop-gaming.png
├── index.html             # Estructura principal
└── README.md              # Documentación del proyecto
```

---
## 📝 Instrucciones de Uso
1. Clona este repositorio en tu máquina local.

2. Abre el archivo index.html en tu navegador web de preferencia.

3. Utiliza los botones + y - para modificar la cantidad de laptops y observa cómo cambia el "Total a pagar" automáticamente.

---
## 👤 Autor
Jorge Leiva

---
## ⚖️ Licencia y Propósito
Este proyecto ha sido desarrollado exclusivamente con fines educativos para el programa de formación de Desafío Latam.