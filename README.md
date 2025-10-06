# 🍽️ foodLab-backend

## 📖 Descripción

**FoodLab** Backend desarrollado en **Java con Spring Boot** que gestiona el flujo completo de pedidos, facturación, clientes y métodos de pago para un restaurante.  
El sistema ofrece una arquitectura limpia basada en servicios y repositorios, con documentación interactiva a través de **Swagger UI**.

---

## ⚙️ Tecnologías Utilizadas

- ☕ **Java 17+**
- 🌱 **Spring Boot 3**
- 🧩 **Spring Web**
- 💾 **Spring Data JPA (MySQL)**
- 🧰 **Lombok**
- 📘 **Swagger / OpenAPI 3**
- 📄 **OpenPDF** (para generación de facturas en PDF)
- 🧠 **Maven** como gestor de dependencias

---

## 🧱 Estructura del Proyecto

src/
├── main/
│ ├── java/com/foodlab/foodlab/
│ │ ├── controllers/ → Controladores REST
│ │ ├── models/ → Entidades principales (Cliente, Orden, Factura, Producto, etc.)
│ │ ├── repositories/ → Repositorios en memoria o con JPA
│ │ ├── services/ → Lógica de negocio
│ │ └── dto/ → Objetos de transferencia de datos (DTOs)
│ └── resources/
│ ├── application.properties
│ └── static/ & templates/ (si se usan vistas)
└── test/ → Tests unitarios y de integración

