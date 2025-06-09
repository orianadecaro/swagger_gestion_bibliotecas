# 📘 Documentación Swagger – Gestión de Biblioteca

Este proyecto contiene la documentación interactiva de la API REST del sistema de **Gestión de Biblioteca**, generada con **Swagger** y desplegada en Vercel.

🌐 **Accedé directamente aquí**:  
👉 [https://swagger-gestion-bibliotecas.vercel.app](https://swagger-gestion-bibliotecas.vercel.app)



---

👩‍💻 Contribuyentes
Sandra Galiano,
Oriana De Caro

---


## 🚀 ¿Qué es Swagger?

[Swagger](https://swagger.io/) es una herramienta que permite describir, consumir y visualizar APIs REST de forma interactiva. Es muy útil para desarrolladores y equipos técnicos ya que facilita:

- La comprensión de los endpoints disponibles
- La prueba directa de cada ruta con parámetros, headers y body
- La generación automática de clientes o SDKs

---

## 🧾 Contenido documentado

Esta documentación Swagger incluye los siguientes módulos del backend:

- 🔐 Autenticación (`authRoutes.js`)
- 📖 Libros (`librosRoutes.js`)
- 👥 Socios (`sociosRoutes.js`)
- 📆 Préstamos (`prestamosRoutes.js`)
- 🧑‍💼 Usuarios (`usuariosRoutes.js`)
- 📁 Perfiles (`perfilesRoutes.js`)

Cada módulo describe sus rutas, métodos HTTP (GET, POST, PUT, DELETE), parámetros, respuestas esperadas y posibles errores.

---

## 🛠️ Cómo se generó

1. La definición Swagger se escribió usando el formato **OpenAPI 3.0** en los archivos `swagger/*.js`.
2. Se utilizó la librería `swagger-jsdoc` para generar el esquema desde comentarios JSDoc.
3. Se sirvió mediante `swagger-ui-express` en el backend (`swagger.js`).
4. Se desplegó en **Vercel** como una app estática.

---


