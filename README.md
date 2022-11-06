<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar `npm install` para instalar las dependencias
3. Tener Nest CLI instalado

```
npm i -g @nestjs/cli
```

4. Levantar la base de datos

```
docker-compose up -d
```

5. Clonar el archivo **_.env.template_** y renombrarlo a **_.env_**

6. Llenar las variables de entorno definidas en el archivo **_.env_**

7. Ejecutar `npm run start:dev` para levantar el servidor en modo desarrollo

8. Recargar la base de datos con la semilla

```
http://localhost:3000/api/v2/seed
```

## Stack usado

- mongodb
- nestjs
- typescript
- docker
- docker-compose
