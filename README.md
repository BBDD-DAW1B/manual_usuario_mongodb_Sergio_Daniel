# Manual de Usuario: MongoDB + Docker + VS Code

Manual de usuario mongodb - 1º DAW (2025/2026)

---

## Objetivo

La idea de este trabajo es aprender a usar MongoDB sin tener que instalar todo directamente en el ordenador.

Para eso usamos Docker, que nos permite tener la base de datos funcionando en un contenedor, y luego la conectamos con Visual Studio Code para trabajar más cómodo.

---

## Tecnologías usadas

- MongoDB (base de datos NoSQL)
- Docker Desktop (para ejecutar MongoDB en contenedores)
- Visual Studio Code (editor de código)
- Extensión MongoDB for VS Code

---

## Qué se hace en este manual

En este documento se explica paso a paso cómo montar todo desde cero.

Primero se configura Docker y se levanta el contenedor de MongoDB con usuario y contraseña.

Después se prepara Visual Studio Code para poder conectarse a la base de datos.

Una vez conectado, se trabajan las operaciones básicas:

- Crear una base de datos llamada `academia`
- Insertar datos (usuarios y cursos)
- Modificar datos
- Consultar información usando filtros
- Borrar registros

También se hacen algunas consultas un poco más avanzadas usando operadores como `$gt`.

---

## Estructura del proyecto

El repositorio está organizado así:

- `/PDF` → contiene el manual completo con capturas
- `/Scripts` → archivos `.mongodb.js` con todas las consultas usadas

---

## Reflexión personal

Al hacer este trabajo me he dado cuenta de que hoy en día no hace falta instalar todo directamente en el sistema.

Con Docker puedes levantar servicios como MongoDB en segundos y sin complicarte mucho. Además, todo queda más organizado y es más fácil repetir el proceso en otro ordenador.

---

## Autor

Sergio Daniel  
Estudiante de 1º DAW

---

Si este manual te ayuda, puedes darle una estrella al repositorio.