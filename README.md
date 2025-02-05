# 📌 YAPE API Testing

Este repositorio contiene una colección de pruebas automatizadas para la API de **restful-booker**, desarrolladas con **Postman**
## 📌 Tabla de Contenidos
- [Requisitos Previos](#requisitos-previos)
- [Estructura de la Colección](#estructura-de-la-colección)

---

## ✅ Requisitos Previos

Antes de comenzar, asegúrate de tener instalados los siguientes componentes:

- [Postman](https://www.postman.com/)


## 📌 Estructura de la Colección

La colección de pruebas incluye los siguientes endpoints:

1. **Ping - HealthCheck**
   - `GET /ping` → Verifica si el servicio está activo.

2. **Autenticación**
   - `POST /auth` → Genera un token de autenticación.

3. **Bookings**
   - `GET /booking` → Obtiene todas las reservas.
   - `GET /booking/{id}` → Obtiene una reserva específica.
   - `POST /booking` → Crea una nueva reserva.
   - `PUT /booking/{id}` → Actualiza una reserva.
   - `PATCH /booking/{id}` → Actualiza parcialmente una reserva.
   - `DELETE /booking/{id}` → Elimina una reserva.

Cada prueba incluye validaciones automáticas en la pestaña `Tests` de Postman.

![image](https://github.com/user-attachments/assets/488bc715-20f9-4550-83b6-4f982edc9695)





