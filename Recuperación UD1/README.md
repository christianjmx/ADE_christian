# Instalación de MySQL Server en Ubuntu Server - Christian Moreno #

## Instalamos Ubuntu Server ##

· Empezamos la instalación de ubuntu server sin entorno gráfico.

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/1.png)

  (Seleccionamos el idioma español)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/2.png)

  (Configuramos la tarjeta de red, en mi caso la dejo en dinámica, la captura fue sacada en mi casa.)
  
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/3.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/4.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/5.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/6.png)

    (Escribimos nuestro nombre de usuario y las contraseñas)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/7.png)
  
    (Marcamos para instalar el SSH)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/8.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/9.png)

    (Esperamos a que termine la instalación) 
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/10.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/11.png)

    
    (Iniciamos sesión con el usuario y contraseña)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/12.png)


## Instalamos el entorno gráfico ##

    (Instalamos el tasksel)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/13.png)

    (Ejecutamos tasksel seleccionano el escritorio que queremos en mi caso KDA)    
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/14.png)
 
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/15.png)

    (Reiniciamos e iniciamos sesión)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/16.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/17.png)

## Instalamos mysql ##

    (Instalamos mysql)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/18.png)

    (Visualizamos la versión)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/19.png)

    (Comprobamos que esté funcionado, lo paramos y volvemos a comprobar, lo hice con 'systemctl' ya que con init.d no se volvía a iniciar el servicio de ninguna manera.)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/20.png)

    (Intentamos entrar como root y no nos dejará ya que hay que asignarle una contraseña)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/21.png)

    (Iniciamos sesión en mysql y le otorgamos una contraseña al root e iniciamos sesión con el.)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/22.png)

## Instalamos Workbench ##

    (Descargamos el 'mysql-apt-config')
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/23.png)

    (Ejecutamos dpkg con el archivo descargado)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/24.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/25.png)

    (Actualizamos e instalamos workbench, yo lo hice con snap)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/26.png)

    (Al instalarlo con snap hay que ingresar el siguiente comando para que acceda al servicio)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/27.png)

    (Desde modo gráfico abrimos el workbench y iniciamos sesión con usuario root)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/28.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/29.png)

    (Agregamos la base da datos jardineria)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/30.png)

## Instalamos el adminer ##

    (Instalamos adminer por consola)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/31.png)

    (Ejecutamos el siguiente comando para compilarlo)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/32.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/33.png)

    (Editamos el siguiente archivo de configuración de la siguiente manera, es para el alias.)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/34.png)

    (Ejecutamos el adminer y recargamos)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/35.png)

    (Entramos desde localhost/adminer.php y nos logueamos con las credenciales de root y jardineria.)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/36.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/37.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/38.png)

## Instalando phpMyAdmin ##

    (Descargamos e instalamos el php con el siguiente comando)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/39.png)

    (Se nos abre este seleccionador, elegimos 'apache2')
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/40.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/41.png)

    (Escribimos una contraseña para el phpmyadmin)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/42.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/43.png)

    (Para Aplicar un nivel de seguridad superior al acceso al phpMyAdmin aplicando .htaccess, escribimos esta línea en el siguiente fichero de configuración.)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/44.png)

    (Reiniciamos y comprobamos el estado del apache)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/45.png)

    (Entramos desde el navegador en localhost/phpmyadmin y nos logueamos con usuario root)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/46.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/47.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/48.png)

## Preguntas finales ##

### 1. Directorio de instalación base. Investigarlo, hacer comprobaciones y demostrarlo con capturas. Ejecutar este comando: sudo mysqladmin -u root -p shutdown. Explicar lo que sucede. ###

    (directorio de instalación base)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/preguntas%20del%20final/1.png)

    (Al ejecutar este comando lo que hace es parar el servicio.)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/preguntas%20del%20final/1.2.png)

### 2. Directorio del servicio o proceso demonio, directorio de registros de mysql (0,5 ptos). ###

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/preguntas%20del%20final/2.png)

### 3. Directorio de datos. ###

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/preguntas%20del%20final/3.png)

### 4.Fichero de configuración del servidor y su ubicación ##

  (Fichero de configuración del servidor)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/preguntas%20del%20final/4.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/preguntas%20del%20final/4.2.png)

### 5. ¿Quién es el usuario propietario de las Base de Datos ? ##

    (Aquí se encuentra)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Recuperaci%C3%B3n%20UD1/IMG/preguntas%20del%20final/5.png)
