# MolinaAutos

Bienvenido a **MolinaAutos**, un proyecto dedicado a la venta de vehículos.

## Descripción

[MolinaAutos](https://molinaautos.vercel.app/) es una plataforma que permite a los usuarios explorar una amplia gama de vehículos disponibles para la venta, ofreciendo detalles completos de cada automóvil, opciones de filtrado avanzadas y una interfaz amigable.

## Características

- **Exploración de vehículos**: Navega por una extensa colección de autos con imágenes y descripciones detalladas.
- **Filtrado avanzado**: Encuentra el vehículo perfecto utilizando filtros por marca, modelo, año, precio y más.
- **Interfaz intuitiva**: Diseño responsivo y fácil de usar para una mejor experiencia del usuario.

## Tecnologías Utilizadas

Este proyecto fue desarrollado utilizando las siguientes tecnologías:

- **Frontend**: React, Bootstrap, HTML, CSS3
- **Backend**: Node.js, Express
- **Base de Datos**: MongoDB

## Instalación

Sigue estos pasos para configurar el proyecto localmente:

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/KaiserJagger/molinaautos.git
   ```

2. **Navega al directorio del proyecto**:
   ```bash
   cd molinaautos
   ```

3. **Instala las dependencias**:
   ```bash
   npm install
   ```

4. **Configura las variables de entorno**:
   Crea un archivo `.env` en la raíz del proyecto y añade las siguientes variables:
   ```env
   DATABASE_URL=tu_url_de_base_de_datos
   TOKEN_SECRET=clave_secreta_para_firmar_JWT
   SESSION_SECRET=secreto_de_la_sesion_de_express
   ```

5. **Inicia el servidor de desarrollo**:
   ```bash
   npm run dev
   ```
