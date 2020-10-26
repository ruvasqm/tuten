Prueba Técnica para Tuten

## Problema 1

Descripción de proceso para crear applicacion con Java8/PostgreSQL/React

## Problema 2

Servicio Rest de conversión de hora a UTC

Link: <https://shrouded-fjord-13348.herokuapp.com>

### Decisiones de diseño

- Se escogió node/express en vez de Java8 para más velocidad de prototipado
- Uso de regex para verificación en el cliente
- Deploy en heroku

### Mejoras posibles

- Agregar interfaz en el cliente para seleccionar el _offset_ usando _timezones_ válidas
- Usar objetos estándar _Date_ de Javascript y cambiar el cliente adecuadamente
- Agregar view de la respuesta de la API

## Problema 3

React WebApp para consumir API de tuten (user/login, user/bookings)

Link: <https://ancient-dawn-52186.herokuapp.com/>

user: testapis@tuten.cl
password: 1234

### Decisiones de diseño

- Se usó parcel, bootstrap 5 y react-router, parcel es más rapido que webpack (y más sencillo de configurar), bootstrap 5 va por su segunda versión alpha y presenta más soporte para customización y react-router es estándar para manejo de navegación
- La raíz apunta al componente de Bookings, si no hay autorización (datos en localStorage) redirecciona a Login
- Uso de verificación html5 en el login
- Uso extensivo de hooks para componentes 100% funcionales
- Tabla de bookings responsive, modificación de los títulos de los campos para usar mejor el espacio y _clickable rows_ para mostrar información omitida
- Uso de fetch API para manejo de solicitudes a las APIs de tuten

### Mejoras posibles

- Modificar barra de filtro (agregar bootstrap-icons, estilizar, etc)
- Centralizar consumo de API con Hooks
- HTTPS para esconder barra de dirección en mobile

## Problema 4

React Native App para cumplir la misma función de _Problema 3_
