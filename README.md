## INSTALACION
     - S01-0001-Crear Proyecto [npx create-next-app@latest --typescript] o [yarn create next-app --typescript]
     - S01-0002-Instalar dependencias
     PRODUCCION
          CONTROLES FRONTEND
          - Material UI [Controles para la Página]
               - [yarn add @mui/material]
               - [yarn add @emotion/react]
               - [yarn add @emotion/styled]
          - Iconos de Material [Icónos que se usan en los menús y en páginas]
               - [yarn add @mui/icons-material]
          - X-Data-Grid [Grid que incluye paginación]
               - [yarn add @mui/x-data-grid]
          - formidable [Subir archivos]
               - [yarn add formidable]
          - react-hook-form [Manejo de formularios, control de errores]
               - [yarn add react-hook-form]
          - react-slideshow-image [Presenta secuencias de imágenes en el frontEnd]
               - [yarn add react-slideshow-image]
          OBTENER DATA
          - Axios [Peticiones http a servicios Rest]
               - [yarn add axios]
          - swr [Biblioteca para obtener datos. En este caso se usa para obtener data del API ]
               - [yarn add swr]
          - js-cookie [Menjo de Cookies en el Navegador]
               - [yarn add js-cookie]
          SEGURIDADES
          - bcryptjs [Encriptado unidireccional]
               - [yarn add bcryptjs]
          - jsonwebtoken [Crear Tokens de Autentificación en Peticiones HTTP ]
               - [yarn add jsonwebtoken]
          - next-auth [Modulo de autentificación de usuarios usando Next]
               - [yarn add next-auth]
          BASE DE DATOS
          - mongoose [Crear y Manejar modelos para MongoDB desde BackEnd de NodeJs]
               - [yarn add mongoose]
          PAGOS
          - Paypal [Pagos mediante Paypal]
               - [yarn add @paypal/react-paypal-js]
          ALMACENAMIENTO DE IMAGENES
          - cloudinary [Repositorio de Imágenes en la nube]
               - [yarn add cloudinary]
     DESARROLLO
          - [yarn add -D @types/bcryptjs]
          - [yarn add -D @types/formidable]
          - [yarn add -D @types/js-cookie]
          - [yarn add -D @types/jsonwebtoken]
     - S01-0003-Agregar configuración ["downlevelIteration": true] en tsconfig.json. Este error se presenta al intentar cargar las imágenes con formidable
     - S01-0003-Eliminar archivos innecesarios de la aplicación
     - S01-0004-Configuraciones Globales
          - Configurar Tipografía Roboto [Requisito para usar Material-UI]
     - S01-0005-Crear Estructura de Archivos
          api                 -> Interactuar con API Rest usando axios
          components          -> Componentes JSX React Personalizados
          context             -> Contextos utilizados para el manejo del state en la aplicación
          hook                -> Hooks personalizados
          interfaces          -> Interfaces utilizadas para el manejo de TypeScript en la aplicación
          database/conn       -> Conexión a bdd
          database/crud       -> Manejo de Operaciones de BDD
          database/models     -> Modelos de BDD
          themes              -> Themes personalizados
          tools               -> Herramientas de uso general en la app
          types               -> Agregar types de TypeScript en pluggins yarn que no poseen
          .env                -> Archivo configuración variables de entorno [No se sube al repositorio]
          .env.template       -> Template Archivo configuración
          pages/admin         -> Paginas de perfil administrador
          pages/auth          -> Paginas de Autentificación
          pages/api/admin     -> API rest para administradores [Configurar Middleware]
          pages/api/auth      -> Configuraciones de Autentificación usando next-auth




