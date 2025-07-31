# Proyecto_Final_DS7
Repositorio del proyecto final de Sistema de Gestión de Inventario de un Rastro


---

## 📋 Descripción

Este proyecto consiste en un sistema web de gestión de inventario desarrollado para un rastro, que permite administrar productos cárnicos, realizar búsquedas dinámicas, gestionar categorías, controlar un carrito de compras y generar reportes.

Desarrollado como parte del Proyecto Final de la materia **Desarrollo de Software 7**, utilizando PHP, MySQL, AJAX y el framework Bulma para el diseño de interfaz.

---

## 🚀 Funcionalidades
- Registro de productos (nombre, categoría, cantidad, precio, imagen)
- Listado y búsqueda en tiempo real (AJAX)
- Carrito de compras funcional
- Gestión de categorías (añadir, editar, eliminar)
- Generación de reportes
- Validación y sanitización de datos (prevención de inyección SQL / XSS)

---

## 🖥️ Tecnologías Utilizadas
- PHP 8.x
- MySQL (phpMyAdmin)
- WampServer
- HTML5 / CSS3 (Bulma CSS)
- JavaScript (AJAX)
- Patrón de diseño: Estructura modular por carpetas (MVC básico)

---

## 📂 Estructura del Proyecto
/INVENTARIO-main/
├── clases/ # Clases PHP (BD, sanitización)
├── css/ # Estilos CSS (Bulma, personalizados)
├── DB/ # Script SQL (pdo.sql)
├── img/ # Imágenes de productos
├── inc/ # Componentes comunes (navbar, footer, etc.)
├── js/ # AJAX scripts
├── php/ # Lógica CRUD y carrito
├── index.php # Página principal
