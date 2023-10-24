# Gestion De Pedidos en Bootstrap
# README para JSON Server en Visual Studio Code

## Requisitos Previos

- **Node.js:** Asegúrate de tener Node.js instalado en tu computadora. Puedes descargarlo desde el sitio web oficial de [Node.js](https://nodejs.org/).
- **Visual Studio Code:** Este es el editor de código que vamos a utilizar. Puedes descargarlo desde el sitio web oficial de [Visual Studio Code](https://code.visualstudio.com/).

## Pasos para Ejecutar un Servidor JSON

### 1. Instalación de JSON Server

Abre la terminal en Visual Studio Code y ejecuta el siguiente comando para instalar JSON Server globalmente en tu computadora:

```bash
npm install -g json-server
```
### 2. Iniciar el servidor JSON: Ahora puedes iniciar el servidor JSON utilizando el siguiente comando en la terminal:

```bash
json-server --watch db.json
```
Esto iniciará el servidor JSON y observará los cambios en el archivo db.json. Por defecto, el servidor se inicia en http://localhost:3000.
