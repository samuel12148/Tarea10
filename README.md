# Dockerización del Carro, Brazo y Bípedo (PyBullet)
En esta práctica se realizó la dockerización de tres simulaciones diferentes utilizando la librería PyBullet.
## Procedimiento
Primero creamos el directorio para trabajar:
<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/112c229e-f4e6-4a6f-a52f-7a5d9b26990b" />
Luego creamos una carpeta para cada elemento que vamos a simular y comprobamos con ls:
<img width="1600" height="144" alt="image" src="https://github.com/user-attachments/assets/da09f76f-41c8-4673-9145-c646ec0d9bce" />
Ahora, entramos a la carpeta del carro, creamos el archivo.py y el Dockerfile, luego creamos la imagen:
<img width="1600" height="591" alt="image" src="https://github.com/user-attachments/assets/e9b0342e-dfad-496e-adb5-d369bfde8f1c" />
Y corremos la imagen.\
En el archivo .zip se encuentra el código en python de cada simulación.
### Carro
Después de correr la imagen de docker que contiene el archivo carro.py se observa lo siguiente:
<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/91747e6d-c6f5-43e4-8432-83ccdec5235a" />
### Brazo
Se realiza el mismo procedimiento, ahora con el archivo de brazo.py y se obtiene lo siguiente:
<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/dfb06e8b-9d1d-4bb3-b8cb-c195e4ddeccb" />
### Bípedo
Y con la imagen de docker con el archivo bipedo.py obtenemos:
<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/6db8ea1c-ad1e-406d-8b8f-234ddd1e0a14" />





