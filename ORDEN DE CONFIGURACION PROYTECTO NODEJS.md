ORDEN DE CONFIGURACION PROYTECTO NODEJS

1. npm init -y
2. instalar dependencias

    1.  express
    2.  ejs
    3.  nodemon -D
    4.  bcryptjs
    5.  dotenv
    6.  express-mysql-session
    7.  express-session
    8. flowbite
    9. morgan
    10. mysql2


3. configurar carpetas

    src
        /public
            /css
            /img
            /js
        /routes
        /services
        /controllers
        /middleware
        /models
            /config.js
            /db.js
        /views
        /services - Este archivo maneja la lógica de negocio.
        /repositories - maneja las consultas directas a la base de datos.
        /utils - Funciones auxiliares - Función para encriptar contraseñas con bcryptjs. - Función para dar formato a fechas. - Función para crear un token JWT.


4.  configurar index.js, motor ejs, controllers y rutas        
5.  configurar tailwind css
    
    1.  npm install tailwindcss -D
    2.  npm install  @tailwindcss/cli -D


    
