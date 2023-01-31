# U4_A1.-Trigger inserción, actualización y borrado - Christian Moreno #

Creamos La tabla e insertamos unos valores en ella.

![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/1.png)

![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/2.png)


## Ejercicio 1 ##

  · Se pide crear un disparador de nombre calc_valorventa asociado a la tabla productos para que antes de insertar un nuevo producto calcule el valor de venta con la fórmula siguiente
  
  Fórmula: valorventa=costo + costo*porgana

  (Creo el trigger)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/3.png)

  (borramos los datos anteriores y los volvemos a insertar)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/4.png)

  (Comprobamos los cambios)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/5.png)

## Ejercicio 2 ##

  · La “idea” es crear un trigger que antes de actualizar un producto vuelva a calcular el valor de venta. 

  (Creo el trigger)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/6.png)

  (Insertamos los valores)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/7.png)

  (Comprobamos la tabla)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/8.png)

  (Actualizamos los valores)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/9.png)

  (Comprobamos de nuevo la tabla)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/10.png)

## Ejercicio 3 ##

  · Preparar un disparador, para controlar que si  no se introduce porcentaje  de venta en una inserción, es decir es NULL ó 0, se aplique por defecto un  20%.
  
  (creo el trigger)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/11.png)

  (inserto los valores)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/12.png)

  (Comprobamos la tabla)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/13.png)

  (añadimos con un valor nulo)
![image](https://github.com/christianjmx/ADE_christian/blob/main/Trigger/IMG/14.png)



















































