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

```text
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── foodlab/
│   │           └── foodlab/
│   │               ├── controllers/      → Controladores REST (manejo de endpoints)
│   │               ├── models/           → Entidades principales (Cliente, Orden, Factura, Producto, etc.)
│   │               ├── repositories/     → Repositorios (HashMap o JPA)
│   │               ├── services/         → Lógica de negocio (implementaciones de servicios)
│   │               ├── dto/              → Data Transfer Objects (DTOs)
│   │               └── config/           → Configuración (Swagger, seguridad, etc.)
│   └── resources/
│       ├── application.properties        → Configuración general de Spring Boot
│       ├── static/                       → Archivos estáticos (imágenes, PDFs, etc.)
│       ├── templates/                    → Plantillas HTML (si se usa Thymeleaf)
│       └── docs/                         → Documentación o ejemplos de API
└── test/
    └── java/
        └── com/
            └── foodlab/
                └── foodlab/
                    └── tests/            → Tests unitarios e integrados


