### Crear contenedor de Postgres sin que exponga los puertos. Usar la imagen: postgres:15-alpine3.21
<img width="1521" height="231" alt="image" src="https://github.com/user-attachments/assets/34066608-f3f0-468d-a4a1-acb6c2c56726" />


### Crear un cliente de postgres. Usar la imagen: dpage/pgadmin4
<img width="1453" height="678" alt="image" src="https://github.com/user-attachments/assets/48db72fb-45a0-4fc2-8b53-dd346ed85c73" />



# COMPLETAR

La figura presenta el esquema creado en donde los puertos son:
- a: 8080
- b: 80
- c: 5432

![Imagen](esquema-2-ejercicio.PNG)

## Desde el cliente
### Acceder desde el cliente al servidor postgres creado.

<img width="1898" height="962" alt="image" src="https://github.com/user-attachments/assets/304b49bb-772f-43ec-9043-81f9b736fe01" />
<img width="1910" height="965" alt="image" src="https://github.com/user-attachments/assets/a4ed4b06-63e6-4876-afff-6d87579dd77e" />


### Crear la base de datos info, y dentro de esa base la tabla personas, con id (serial) y nombre (varchar), agregar un par de registros en la tabla, obligatorio incluir su nombre.

## Desde el servidor postgresl
### Acceder al servidor
### Conectarse a la base de datos info
<img width="736" height="157" alt="image" src="https://github.com/user-attachments/assets/13b83b04-f8c9-449e-b7a8-3e76b2ae2f2e" />

### Realizar un select *from personas
<img width="398" height="184" alt="image" src="https://github.com/user-attachments/assets/2a0522b0-8a91-44ed-9c12-34826c6ed53d" />

