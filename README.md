# 🍽️ Sistema de Gestión de Restaurante

Sistema desarrollado en Java orientado a la administración integral de un restaurante.  
Permite gestionar productos, clientes y pedidos, aplicando descuentos y promociones, con un flujo funcional completo desde la creación hasta la finalización de la orden.

## 📌 Descripción del Proyecto

El sistema simula el funcionamiento real de un restaurante, donde un usuario (mesero o administrador) puede:

- Registrar y administrar productos del menú  
- Gestionar clientes  
- Crear pedidos con múltiples productos  
- Aplicar descuentos y promociones  
- Calcular totales de forma automática  
- Finalizar pedidos y almacenarlos en historial  
- Consultar estadísticas de ventas

El proyecto está enfocado en la lógica de negocio, buenas prácticas de programación orientada a objetos y pruebas unitarias.

---

## 🧱 Módulos Principales

### 🛒 Gestión de Productos
- Crear, modificar y eliminar productos  
- Aplicar promociones por porcentaje  
- Validación de precios y disponibilidad

### 👤 Gestión de Clientes
- Registro de clientes  
- Asociación de clientes a pedidos

### 📦 Gestión de Pedidos
- Creación de pedidos con múltiples ítems  
- Cálculo automático de totales  
- Aplicación de descuentos  
- Finalización y almacenamiento en historial

### 📊 Reportes
- Total de ventas  
- Productos más vendidos  
- Historial de pedidos finalizados

---

## 🧪 Pruebas del Sistema

Se implementó un plan de pruebas funcional utilizando:

- **JUnit 5** para pruebas unitarias  
- **JaCoCo** para medición de cobertura  
- Simulación de base de datos en memoria con listas y mapas

### Criterios validados

- Correcto cálculo de totales y descuentos  
- Integridad del historial de pedidos  
- Aplicación correcta de promociones  
- Flujo completo sin errores desde creación hasta cierre

---

## 🛠️ Tecnologías Utilizadas

- Java (OpenJDK 24)  
- Programación Orientada a Objetos  
- JUnit 5  
- JaCoCo  
- IntelliJ IDEA  
- Estructuras de datos en memoria

---

## ▶️ Ejecución del Proyecto

1. Clonar el repositorio:
```bash
git clone <url-del-repositorio>
