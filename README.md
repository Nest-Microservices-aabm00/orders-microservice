# Orders MicroService

```
docker compose up -d
```

## Development pasos

1. Clonar el proyecto
2. Instalar dependencias
3. Crear un archivo `.env` basado en el archivo `.env.template`
4. Levantar la base de datos con `docker compose up -d`
5. Ejecutar migración de prisma `npx prisma migrate dev`
6. Levantar el proyecto con `npm run start:dev`
