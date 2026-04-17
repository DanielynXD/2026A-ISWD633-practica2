# Variables de Entorno
### ¿Qué son las variables de entorno?
Valores dinámicos que hablan a los procesos y programas sobre el entorno en el que se están ejecutando.

### Para crear un contenedor con variables de entorno

```
docker run -d --name <nombre contenedor> -e <nombre variable1>=<valor1> -e <nombre variable2>=<valor2>
```

### Crear un contenedor a partir de la imagen de nginx:alpine con las siguientes variables de entorno: username y role. Para la variable de entorno rol asignar el valor admin.

<img width="1260" height="89" alt="image" src="https://github.com/user-attachments/assets/a9fa1e4a-8948-4b05-944a-d040e21da71e" />


# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR
<img width="1147" height="335" alt="image" src="https://github.com/user-attachments/assets/81376e1b-8d15-4705-8615-2df7306841f1" />


### Crear un contenedor con la imagen de mysql, mapear todos los puertos
<img width="984" height="440" alt="image" src="https://github.com/user-attachments/assets/1c54b45a-0164-40c2-b5ca-dfc539bf1120" />


### ¿El contenedor se está ejecutando?
No
<img width="1467" height="163" alt="image" src="https://github.com/user-attachments/assets/fdfb874d-b8b4-443c-8972-087bb43430d3" />


### Identificar el problema
<img width="1552" height="264" alt="image" src="https://github.com/user-attachments/assets/77a7043c-8317-450e-862f-cb4e9847452b" />



### Para crear un contenedor con variables de entorno especificadas
- Portabilidad: Las aplicaciones se vuelven más portátiles y pueden ser desplegadas en diferentes entornos (desarrollo, pruebas, producción) simplemente cambiando el archivo de variables de entorno.
- Centralización: Todas las configuraciones importantes se centralizan en un solo lugar, lo que facilita la gestión y auditoría de las configuraciones.
- Consistencia: Asegura que todos los miembros del equipo de desarrollo o los entornos de despliegue utilicen las mismas configuraciones.
- Evitar Exposición en el Código: Mantener variables sensibles como contraseñas, claves API, y tokens fuera del código fuente reduce el riesgo de exposición accidental a través del control de versiones.
- Control de Acceso: Los archivos de variables de entorno pueden ser gestionados con permisos específicos, limitando quién puede ver o modificar la configuración sensible.

### ¿Qué bases de datos existen en el contenedor creado?
<img width="938" height="600" alt="image" src="https://github.com/user-attachments/assets/703add95-6ba8-4551-89ab-fb76a26ad591" />

