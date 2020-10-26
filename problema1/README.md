## Descripción

Detallar el desarrollo de una app usando Java8, PostgreSQL y React

## Backend

Para el backend se usaría Spring, JPA/Hibernate y PostgreSQL(propia del servidor o ElephantSQL).

### Pasos:

- Inicializar proyecto Spring
- Configurar dependencias en pom.xml
- Escribir el server (modelos, peticiones, auth, excepciones, controladores, etc)
- Configurar Postgres a través de _application.properties_
- Configurar ENV file o similar
- Testing/Deploy

## Frontend

### Pasos

- Inicializar package.json (Yarn)
- Instalar dependencias cruciales (react, react-dom, react-router-dom, parcel-bundler, sass)
- Instalar dependencias especificas
- Escribir index.html, incluir index.js
- Escribir esqueleto de la app y service worker en index.js
- Escribir App.js, componentes e integración con la(s) API(s)
- Escribir scripts de build

## Final

### Pasos

- Escribir scripts de build/deploy (dist folder de react debe estar ligada a una ruta del backend)
- Configurar ENV
- Build y Deploy
