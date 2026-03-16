# 🛠️ Sistema de Gestión para Ferretería (Backend)

Este proyecto constituye el **Proyecto de Grado** desarrollado para la obtención del título de **Técnico Profesional en Soporte de Sistemas Informáticos y Redes** en la Fundación Escuela Tecnológica (FET). Se trata de un ecosistema digital robusto diseñado para optimizar el control de inventarios, ventas y administración de una ferretería.

## 🏗️ Arquitectura y Diseño
El proyecto destaca por la implementación de **Arquitectura Hexagonal (Puertos y Adaptadores)**, lo que garantiza un código altamente mantenible, testeable y desacoplado:

* **Domain (Dominio):** Contiene las entidades de negocio (`ProductoEntity`, `VentasEntity`) y la lógica central.
* **Application (Aplicación):** Define los puertos de entrada y salida (`port.interactor`, `port.out`) y los DTOs para el flujo de datos.
* **Infrastructure (Infraestructura):** Implementa los adaptadores, incluyendo controladores REST y la persistencia de datos.

## 🚀 Tecnologías Principales
* **Lenguaje:** Java 17+
* **Framework:** Spring Boot (Spring Web, Spring Data JPA)
* **Gestión de Dependencias:** Gradle
* **Base de Datos:** MySQL
* **Herramientas:** IntelliJ IDEA, Postman para pruebas de API.

## 🤝 Créditos y Colaboración
Este proyecto fue realizado como requisito de grado mediante un trabajo en equipo con roles definidos:

* **Luis Angel Poveda Puentes:** Desarrollo Backend e implementación de Arquitectura Hexagonal.
* **Linda Paola Carreño Meneses:** Desarrollo Backend y lógica de negocio.
* **Alejandra Vargas Baquero:** Desarrollo principal del Frontend y experiencia de usuario.

---
*Este repositorio es parte de mi portafolio profesional y demuestra mis capacidades técnicas en el desarrollo de software empresarial.*
