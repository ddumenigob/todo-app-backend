# todo-app-backend
backend de la app To Do

La BD es un Azure Postgresql Flexible server. Al momento de crearla tener en cuenta guardar en un lugar seguro la passw.
Se debe crear la BD con nombre todoapp

Para conectarse desde el backend a la BD, en "Environment variables": </br>

DATABASE_HOST: <fqdn \del host de BD> Ej: db-postgres-todoapp.postgres.database.azure.com</br>
DATABASE_NAME: todoapp</br>
DATABASE_PASSWORD: El passw q definimos al crear el Postgresql Flexible server para conectarnos</br>
DATABASE_URL: postgresql://postgres:<PASSWORD>@<\Host de BD>:5432/<\DB name>?sslmode=require Ej: postgresql://postgres:Trabajo*2025@db-postgres-todoapp.postgres.database.azure.com:5432/todoapp?sslmode=require</br>
DATABASE_USER: postgres (o el usuario q se haya definido al momento de creado el Postgresql Flexible server)</br>
