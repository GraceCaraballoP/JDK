# Instalación JDK 11 en Ubuntu

Para instalarlo debemos ir a la terminal de nuestro sistema operativo **(CTRL+ALT+T)**  y escribir lo siguiente para poder activar la descarga de los paquetes de las fuentes configuradas:  
```
sudo apt-get update
```

<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-11-en-Ubuntu/blob/main/Captura1.png">  

Ahora con la siguiente instrucción descargará e instalará el paquete de JDK versión 11:  
```
sudo apt install openjdk-11-jdk
```

<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-11-en-Ubuntu/blob/main/Captura2.png">  
 
La instalación tardará un par de minutos.  

<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-11-en-Ubuntu/blob/main/Captura3.png">  
  
Una vez hecho esto la instalación debe de haber finalizado correctamente, para comprobarlo ejecutaremos el comando:  
```
java -version
```

Donde como veremos en la siguiente imagen nos dice que se ha realizado correctamente y la versión que tenemos es la 11.0.11.
  
<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-11-en-Ubuntu/blob/main/Captura4.png">  
 
Con esto quedaría finalizada la instalación.
