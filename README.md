📊 Dashboard Administrativo - DDecoHouse

Dashboard desarrollado en React que permite visualizar métricas clave del sistema, consumiendo una API REST desplegada.

Este proyecto forma parte del ecosistema de la aplicación **DDecoHouse E-commerce**.

👉 Proyecto principal (E-commerce):
https://github.com/EzequielScoffoni/ProyectoIntegrador-Ecommerce

---------------------------------------------------------------------------------------------------------

Funcionalidades:
* 📦 Cantidad de productos en stock
* 💰 Cantidad de productos vendidos
* 👥 Total de usuarios registrados
* 📋 Listado completo de usuarios
* 🏷️ Visualización de roles (usuario, admin, superadmin)

----------------------------------------------------------------------------------------------------------

Tecnologías utilizadas:
* React.js
* JavaScript (ES6+)
* Fetch API
* React Bootstrap

----------------------------------------------------------------------------------------------------------

API utilizada:

Este dashboard consume datos desde la API del proyecto DDecoHouse:

👉 https://proyectointegradorg10-pmtu.onrender.com/

Endpoints utilizados:

* `/api/products`
* `/api/products/vendidos`
* `/api/users`
* `/api/users/total`

----------------------------------------------------------------------------------------------------------

Deploy:
El dashboard consume una API en producción, por lo que no requiere levantar el backend en local.

----------------------------------------------------------------------------------------------------------

Conceptos aplicados:
* Consumo de APIs REST
* Manejo de estado con React Hooks
* Arquitectura desacoplada (frontend/backend)
* Integración con backend deployado
* Debugging full stack
