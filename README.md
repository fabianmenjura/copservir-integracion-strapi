### 🚀 Getting Started with Strapi
# Proyecto Strapi - Landing Establecimiento de Comercio Copservir

¡Saludos! Este es el proyecto de landing para el establecimiento de comercio Copservir. A continuación, te proporcionamos la información y los enlaces necesarios:

## Roles de Acceso

- Rol Super Admin: **IMPORTANTE: EL USO DE ESTE ROL PUEDE CAUSAR DAÑOS GRAVES EN EL ADMINISTRADOR, SE RECOMIENDA PRECAUCIÓN.**
- Rol Editor:
  - Usuario: admin@admin.com
  - Contraseña: Admin123

## Versiones de los Componentes

- Strapi: v4.13.1
- Node: v16.20.2
- MySQL: v5.7.40

## Plugins Utilizados

- Tiptap Editor v0.9.12 (utilizado para el editor WYSIWYG)
- Awesome Help v1.0.8 (utilizado para los textos de ayuda)

## Instrucciones de Instalación

Sigue los siguientes pasos para instalar el proyecto en tu entorno local:

### 1. Importar la Base de Datos:

- Copia el archivo `copservir-integracion-strapi.sql.example` y renómbralo:
```bash
cp copservir-integracion-strapi.sql.example copservir-integracion-strapi.sql
```
- Desde phpMyAdmin, crea una base de datos con el mismo nombre del archivo SQL e importa el archivo SQL.

### 2. Clonar el Repositorio:

```bash
git clone https://github.com/fabianmenjura/copservir-integracion-strapi.git
```

### 3. Navegar al Directorio del Proyecto:
```bash
cd tu-proyecto
```

### 4. Instalar Dependencias del Proyecto:
```bash
npm install
```

### 5. Configuración:
Copia el archivo de configuración de ejemplo y renómbralo:
```bash
cp .env.example .env
```
Edita el archivo .env y configura las variables de entorno necesarias.

#### Compilar la Aplicación:
```bash
npm run build
```

#### Iniciar la Aplicación:
```bash
npm start
```

Acceder a la Aplicación en tu Navegador Web:
http://localhost:3000



# 🚀 Getting Started with Strapi
Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment

Strapi gives you many possible deployment options for your project including [Strapi Cloud](https://cloud.strapi.io). Browse the [deployment section of the documentation](https://docs.strapi.io/dev-docs/deployment) to find the best solution for your use case.

## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://strapi.io/blog) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>
