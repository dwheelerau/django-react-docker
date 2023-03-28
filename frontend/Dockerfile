# Obtiene la versión de Node.js desde la variable de entorno
ARG NODE_VERSION

FROM node:${NODE_VERSION}

WORKDIR /app

COPY package*.json ./

COPY . .

EXPOSE 3000
