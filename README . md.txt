# 🍬 Arma tu Alfajor Personalizado (Proyecto Final de Tecnología)

Este proyecto es una aplicación web interactiva que simula una experiencia de personalización y compra de un alfajor. Fue desarrollado como parte del currículo de Tecnología para demostrar el manejo de interfaces de usuario dinámicas, gestión de estado y lógica de negocio (cálculo de precios).

El proyecto está diseñado para un despliegue sencillo y rápido utilizando servicios de hosting estático como **Netlify**.

## 🌟 Características Principales

* **Personalización Interactiva:** El usuario puede seleccionar un relleno, un baño de chocolate y una decoración.
* **Visualización Dinámica:** La imagen del alfajor (simulada con placeholders) cambia para reflejar la selección principal del usuario.
* **Cálculo de Precios en Tiempo Real:** Utiliza React Hooks (`useMemo`) para calcular el precio total de forma eficiente, sumando el precio base y el costo de cada componente.
* **Flujo de Pedido con Validación:** Alterna entre una vista de **Selección** y una vista de **Resumen/Pago**, implementando:
    * Validación para asegurar que todos los componentes sean seleccionados antes de avanzar.
    * Validación de formato (solo números) para el campo de tarjeta de débito.
* **Diseño UX:** Interfaz limpia, basada en una paleta de colores pastel, con botones que se resaltan al ser seleccionados para un excelente *feedback* visual.

## 🛠️ Tecnología

El proyecto está construido usando tecnología web moderna:

* **HTML5:** Estructura base del documento.
* **CSS3:** Estilos de diseño, *layout* y paleta de colores.
* **JavaScript (React):** La lógica de la aplicación y la gestión del estado se manejan con React, utilizando **CDN y Babel** para facilitar el despliegue sin necesidad de herramientas de construcción complejas (como Webpack o Vite).

## 🚀 Despliegue en Netlify (Instantáneo)

El proyecto está configurado en un único archivo `index.html`, lo que permite un despliegue sin comandos de construcción.

### Pasos para Desplegar:

1.  **Guardar el Código:** Asegúrate de que todo el código del proyecto (HTML, CSS y JS/React) esté contenido en un solo archivo llamado **`index.html`**.
2.  **Subir a Netlify:**
    * Visita la página de arrastrar y soltar de Netlify: [https://app.netlify.com/drop](https://app.netlify.com/drop).
    * Simplemente **arrastra el archivo `index.html`** al área de despliegue.
3.  **Resultado:** Netlify detectará el archivo estático y generará automáticamente una URL pública (ej: `delightful-alfajor.netlify.app`), haciendo que tu aplicación esté disponible en Internet.

---

## 📚 Información Académica

Este proyecto fue desarrollado bajo los siguientes parámetros:

| Detalle | Valor |
| :--- | :--- |
| **Asignatura** | Tecnología |
| **Profesor/a** | Victoria Silva |
| **Curso** | IIdo Medio |
| **Institución** | CNSC 2025 |