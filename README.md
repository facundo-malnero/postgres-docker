# Cómo levantar PostgresSQL?

### Para levantar PostgresSQL con Docker, se deben seguir los siguientes pasos

1. **Clonar el repositorio**
2. **Copiar el .env.example como .env**
````
cp .env.example .env
````
3. Levantar el contenedor
````
docker compose up -d
````
4. Entrar a pgAdmin
``http://localhost``
5. Loguearse en pgAdmin
``usuario: admin@admin.com | password: admin``
6. Agregar la base con los siguientes datos
``host: postgres | user: user | password: password``