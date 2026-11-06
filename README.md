# José Adolfo Mayhua Palomino

### Desarrollador Backend y Full Stack Junior

Bachiller en Ingeniería de Sistemas (Universidad Nacional de Huancavelica), desde Lima, Perú.
Construyo aplicaciones web y APIs REST, con foco en backend, integración de servicios, bases de datos y seguridad. Me interesa resolver problemas reales: tengo un bot de cobranzas en producción para un cliente real y dos sistemas más en desarrollo.

---

## Sobre mí

- Diseño de APIs REST, microservicios y sistemas multi-negocio.
- Seguridad: autenticación JWT con refresh tokens, roles y permisos, RLS en PostgreSQL, CSRF y CSP.
- Bases de datos: PostgreSQL, MySQL y SQLite.
- Pruebas automatizadas y pruebas de API con Insomnia.
- Docker, Git y GitHub; despliegue y administración de servidores Linux (Ubuntu) por SSH con PM2.
- Uso agentes de IA (Claude Code, GitHub Copilot) como parte de mi flujo de trabajo: defino especificaciones y reglas, exijo pruebas y reviso cada cambio.
- Aprendiendo ahora: **Python** y **Power BI**.

---

## Tecnologías

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)

**Frontend**
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Bases de datos**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**Herramientas e infraestructura**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![Insomnia](https://img.shields.io/badge/Insomnia-4000BF?style=for-the-badge&logo=insomnia&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## Proyectos destacados

### FutRed: red social de fútbol amateur
*En desarrollo. El código es privado; este enlace lleva a la documentación.*

Plataforma de arquitectura de microservicios para jugadores y equipos de fútbol amateur.

- 5 microservicios (identidad, contenido, noticias, retos y notificaciones), cada uno con su propia base de datos PostgreSQL, y un BFF en Laravel y Vue 3.
- El servicio de identidad declara 85 rutas de API REST.
- Autenticación JWT con refresh tokens rotativos (hash SHA-256) y aislamiento de datos con RLS en 15 tablas de 4 servicios.
- Verificación por API de la confirmación cruzada de resultados.

**Tecnologías:** Laravel, Vue 3, Inertia, PostgreSQL, PostgREST, Docker, MinIO.
[Ver documentación](https://github.com/J-Mayhua/R-S_de_Futbol_Amateur)

### Asistente de ventas por WhatsApp (SaaS multi-negocio)
*En desarrollo. El código es privado; este enlace lleva a la documentación.*

SaaS que atiende por WhatsApp a los clientes de tiendas pequeñas, con un panel web para cada dueño.

- Cada negocio tiene su propia sesión de WhatsApp, su panel y sus datos aislados, con catálogo y pedidos guiados.
- Principio de diseño: la IA (en desarrollo) solo redacta; el código decide precios, totales y pedidos.
- Seguridad con bcrypt, Helmet con CSP estricto, CSRF y límite de intentos de acceso.
- Pruebas automatizadas que verifican el aislamiento entre negocios.

**Tecnologías:** Node.js, Express, EJS, SQLite, WPPConnect.
[Ver documentación](https://github.com/J-Mayhua/SaaS_Multi-negocio_de_Bots_de_WhatsApp)

### Bot de cobranzas por WhatsApp (en producción)
Automatización de cobranzas para un proveedor de internet, integrada con la API REST de UCRM. Reemplazó un proceso manual de búsqueda de deudores, descarga de facturas y envío por WhatsApp: envía recordatorios antes y después del vencimiento a unos 70 clientes y procesa comprobantes de pago con OCR. Trabajo freelance, desplegado en un servidor Ubuntu con PM2 y administrado por SSH.

**Tecnologías:** Node.js, Express, Axios, WPPConnect, Tesseract.js, PM2.
[Integración con la API de UCRM](https://github.com/J-Mayhua/bot-cobros-api-whatsapp-web) · [WPPConnect y OCR](https://github.com/J-Mayhua/bot-cobros-whatsapp-wppconnect)

### Sistema Policial de Gestión de Incidencias
Registro y seguimiento de incidencias: asignación de casos, geolocalización, carga de evidencias, roles de usuario y reportes en PDF.

**Tecnologías:** PHP, MySQL, JavaScript, PDO, FPDF, Google Maps API.
[Ver proyecto](https://github.com/J-Mayhua/gestios-de-incidencias-delictivas)

### Sistema de Gestión Clínica
Gestión de pacientes, citas médicas, personal e historial clínico.

**Tecnologías:** PHP, MySQL, JavaScript, HTML5, CSS3.
[Ver proyecto](https://github.com/J-Mayhua/sistema-gestion-clinica) · [Demo en vivo](https://sistema-gestion-clinica-henna.vercel.app/)

### Sistema de Gestión de Tienda de Ropa
Catálogo de productos, ventas, comprobantes e inventario.

**Tecnologías:** PHP, MySQL, JavaScript, Bootstrap.
[Ver proyecto](https://github.com/J-Mayhua/tienda_ropa) · [Demo en vivo](https://tienda-ropa-three-topaz.vercel.app/)

### Plan de Gobierno Distrital de Paucará 2027-2030
Sitio web con los ejes de trabajo, programas, metas, cronograma y documentos de un plan de gobierno distrital, con navegación por secciones y fichas por programa.

**Tecnologías:** React 19, TypeScript, Vite, Tailwind CSS, React Router.
[Ver proyecto](https://github.com/J-Mayhua/Plan_de_gobierno_distrital) · [Demo en vivo](https://plan-de-gobierno-nine.vercel.app/)

---

## Proyectos de práctica

- **API REST de gestión de tareas con JWT:** registro e inicio de sesión, CRUD de tareas por usuario, contraseñas con bcrypt y validación con Zod. *Node.js, Express, PostgreSQL.* [Ver proyecto](https://github.com/J-Mayhua/auth-api-jwt)
- **Landing page responsive:** formulario de contacto conectado a una API externa, diseño mobile-first y componentes reutilizables. *React, Vite, Tailwind CSS.* [Ver proyecto](https://github.com/J-Mayhua/pagina-landing-vite)

---

## Actualmente

Busco mi primera oportunidad profesional, remota o presencial en Lima, en:

- Desarrollo backend
- Desarrollo full stack
- APIs e integraciones

---

## Contacto

- Correo: [joseadolfomayhua01@gmail.com](mailto:joseadolfomayhua01@gmail.com)
- LinkedIn: [José Adolfo Mayhua Palomino](https://www.linkedin.com/in/jose-adolfo-mayhua-palomino-184a79237/)
- GitHub: [J-Mayhua](https://github.com/J-Mayhua)
