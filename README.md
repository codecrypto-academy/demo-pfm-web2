# Demo PFM Web2

Este es un proyecto de demostración de una aplicación web construida con **Next.js**. El objetivo principal de este proyecto es mostrar cómo construir una aplicación moderna utilizando tecnologías actuales.

## Tabla de Contenidos

- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación y Ejecución](#instalación-y-ejecución)
- [Modelo-Vista-Controlador (MVC)](#modelo-vista-controlador-mvc)
- [Modelo-Entidad-Relación](#modelo-entidad-relación)
- [Casos de Uso](#casos-de-uso)


## Características

- Aplicación web reactiva.
- Interfaz de usuario optimizada.
- Integración con API para el manejo de datos.
- Optimización automática de fuentes.

## Tecnologías Utilizadas

- [Next.js](https://nextjs.org) - Framework de React para aplicaciones web.
- [TypeScript](https://www.typescriptlang.org) - Lenguaje de programación que mejora JavaScript.
- [Tailwind CSS](https://tailwindcss.com) - Framework CSS para estilos rápidos y responsivos.
- [Vercel](https://vercel.com) - Plataforma de despliegue para aplicaciones Next.js.

## Estructura del Proyecto

![image](https://github.com/user-attachments/assets/0f608c48-c82b-4854-b099-4a8b9acb50fb)

demo-pfm-web2/
├── prisma/
├── src/
│ ├── app/
│ ├── components/
│ └── styles/
├── .env
├── package.json
├── README.md
└── tiendaweb2.db



## Instalación y Ejecución

1. Clona el repositorio:
   ```bash
   git clone https://github.com/codecrypto-academy/demo-pfm-web2.git

2. Navega al directorio del proyecto:
   ```bash
   cd demo-pfm-web2

3. Instala las dependencias:
   ```bash
   npm install
   
4. Ejecuta el servidor de desarrollo:
   ```bash
   npm run dev
   
5. Abre tu navegador en http://localhost:3000 para ver la aplicación en acción.


## Modelo-Vista-Controlador (MVC)
Este proyecto sigue el patrón de diseño MVC:

Modelo: Define la estructura de los datos y la lógica de negocio. En este caso, se utilizan bases de datos para almacenar información en tiendaweb2.db.

Vista: La interfaz de usuario que interactúa con el usuario final. Las vistas están construidas en la carpeta src/app/.

Controlador: Maneja la lógica de la aplicación, interactuando con el modelo y actualizando la vista según sea necesario.


## Modelo Entidad Relación

![image](https://github.com/user-attachments/assets/d9eedf29-42c9-40be-a999-9463cb55b5dd)



## Casos de Uso
Registro de Usuarios: Permitir a los usuarios registrarse y almacenar sus datos en la base de datos.

Inicio de Sesión: Autenticación de usuarios existentes para acceder a sus perfiles.

Gestión de Productos: Los usuarios pueden agregar, editar y eliminar productos en la tienda.

Visualización de Productos: Los usuarios pueden navegar y ver productos disponibles en la tienda.

Carrito de Compras: Los usuarios pueden agregar productos a un carrito y proceder con la compra.


