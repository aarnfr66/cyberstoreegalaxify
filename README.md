CyberStore (eGalaxify)

Aplicación e-commerce fullstack desarrollada como proyecto de práctica profesional, implementando autenticación, roles y gestión completa de productos y órdenes.

 Funcionalidades
Autenticación con JWT
Registro y login de usuarios
Roles: USER / ADMIN
Catálogo de productos
Carrito de compras (contador reactivo)
Checkout y generación de órdenes
Panel de administrador
CRUD de productos
Visualización de órdenes
Relación de órdenes con usuario
Extras
Validaciones en formularios
Mensajes UI (éxito / error)
 Tecnologías
Frontend: Angular
Backend: ASP.NET Core Web API
Base de datos: SQL Server
ORM: Entity Framework Core (Code First + Migrations)
 Ejecución del proyecto
Backend
dotnet run
Frontend
npm install
ng serve
 Roles de prueba
USER: puede navegar y comprar productos
ADMIN: gestiona productos y órdenes
 Base de datos

La base de datos se gestiona mediante Code First, permitiendo reconstruirla automáticamente con:

dotnet ef database update

Las migraciones versionan la estructura y garantizan consistencia entre entornos.

 Notas

Proyecto enfocado en práctica fullstack y preparación para entrevistas junior.
Se planean mejoras futuras en UI, validaciones y experiencia de usuario
