# Instalación JDK 8 en Ubuntu

Para instalarlo debemos ir a la terminal de nuestro sistema operativo **(CTRL+ALT+T)**  y escribir lo siguiente para poder activar la descarga de los paquetes de las fuentes configuradas:  
```
sudo apt-get update
```

<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-8-en-Ubuntu/blob/main/Captura1.png">  

Ahora con la siguiente instrucción descargará e instalará el paquete de JDK versión 8:  
```
sudo apt install openjdk-8-jdk
```

<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-8-en-Ubuntu/blob/main/Captura2.png">  
 
La instalación tardará un par de minutos.  

<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-8-en-Ubuntu/blob/main/Captura3.png">  
  
Una vez hecho esto la instalación debe de haber finalizado correctamente, para comprobarlo ejecutaremos el comando:  
```
java --version
```

Donde como veremos en la siguiente imagen nos dice que la versión que tenemos es la 11.0.11 que no es la que queríamos instalar pero la teníamos previamente instalada.  
  
<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-8-en-Ubuntu/blob/main/Captura4.png">  
 
Para saber si además de la versión 11.0.11 esta la versión 1.8.0 debemos hacer lo siguiente para ver las versiones de JDK instaladas en el sistema operativo.  
  
<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-8-en-Ubuntu/blob/main/Captura5.png">  
 
Como vemos en la imagen aparecen varias versiones, pero la que nos interesa es la 8 para ponerla por defecto debemos seleccionarla opción **2** en este caso ya que es la que hace referencia a la versión 1.8.0.  
   
<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-8-en-Ubuntu/blob/main/Captura6.png">  
 
Una vez hecho esto ya deberíamos de tener por defecto esta versión, para comprobarlo ejecutaremos el comando:  
```
java --version
```

Donde como veremos en la siguiente imagen nos dice que se ha realizado correctamente y la versión que tenemos es la 1.8.0. 
  
<img src="https://github.com/GraceCaraballoP/Instalaci-n-JDK-8-en-Ubuntu/blob/main/Captura7.png">  

Con esto quedaría finalizada la instalación.
