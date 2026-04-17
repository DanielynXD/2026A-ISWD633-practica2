## Esquema para el ejercicio
![Imagen](esquema-4-ejercicio.PNG)

### Crear la red
<img width="793" height="61" alt="image" src="https://github.com/user-attachments/assets/1631c842-4f81-42d4-822b-120b00b6bb60" />


### Crear el contenedor mysql a partir de la imagen mysql:8, configurar las variables de entorno necesarias
<img width="1308" height="419" alt="image" src="https://github.com/user-attachments/assets/020b0ebb-16d6-4faf-b6bf-436135a5b4e7" />


### Crear el contenedor wordpress a partir de la imagen: wordpress, configurar las variables de entorno necesarias


De acuerdo con el trabajo realizado, en el esquema del ejercicio el puerto a es **8080**

Ingresar desde el navegador al wordpress y finalizar la configuración de instalación.
# COLOCAR UNA CAPTURA DE LA CONFIGURACIÓN
<img width="1456" height="98" alt="image" src="https://github.com/user-attachments/assets/821bdf77-c724-4feb-9e3f-3a1d3f96c2d8" />
<img width="784" height="462" alt="image" src="https://github.com/user-attachments/assets/ea083c54-c86c-44f2-8f52-154fdca08627" />




Desde el panel de admin: cambiar el tema y crear una nueva publicación.
Ingresar a: http://localhost:9300/ 
recordar que a es el puerto que usó para el mapeo con wordpress
# COLOCAR UNA CAPTURA DEL SITO EN DONDE SEA VISIBLE LA PUBLICACIÓN.
<img width="1885" height="1012" alt="image" src="https://github.com/user-attachments/assets/d5ad5372-6bdc-4573-9e0d-65fecb9163e0" />



### Eliminar el contenedor wordpress
<img width="1346" height="180" alt="image" src="https://github.com/user-attachments/assets/340a9885-c03e-479f-912b-14f421fff6f9" />


### Crear nuevamente el contenedor wordpress
Ingresar a: http://localhost:9300/
recordar que a es el puerto que usó para el mapeo con wordpress



### ¿Qué ha sucedido, qué puede observar?
<img width="1468" height="259" alt="image" src="https://github.com/user-attachments/assets/6f606d23-d261-46dc-ae20-d3f9a0e98869" />
<img width="1886" height="1011" alt="image" src="https://github.com/user-attachments/assets/784aa31a-0a6c-442a-b84a-9fff771c9cff" />
No se elimino la nueva publicación debido a que la creamos en la bdd y esta no se toco.



