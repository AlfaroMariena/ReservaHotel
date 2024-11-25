DETALLE DE EJECUCION 

1- Descarga el proyecto en la rama master
2-Abrelo en tu IDE de desarrollo
3-Busca la clase MAIN  ,es la clase que nos ayudara a ejecutar el proyecto
4-Al ejecutar se  te presentara un menu con los siguientes items:
+-----------------------------------------+
| Sistema de ReservaBasicas de Hotel SRH7 |
| 1. Hacer una Reserva                    |
| 2. Eliminar una Reserva                 |
| 3. Agregar servicio a una Reserva       |
| 4. Quitar servicio de una Reserva       |
| 5. Mostrar Reservas                     |
| 6. Mostrar Habitaciones Disponibles     |
| 7. Salir                                |
| Seleccione una opcion:                  |
+-----------------------------------------+

5-Para hacer uso del menu  necesitas dirigirte con los numeros que ves en el menu.
1.HACER UNA RESERVA :Al solicitar una reserva el programa nos solicitara datos ,tales como : Nombre,telefono,tipo de habitacion a solicitar,
fecha de entrada y fecha  de salida.Con los datos completos el programa procedera a mostrar  la notificacion de la reserva exitosa.

6-Para mostrar la reserva que acabamos de realizar precionamos el numero 5 y nos mostrara lo siguiente:
-------------------------------------------------------------
Reserva para habitación DO01       cuesta 200.00    
a nombre de: Rafael Alfaro                 
Teléfono: 70894142                      
No hay servicios relacionados con esta reserva.
-------------------------------------------------------------

7.Si deseamos agregar un servicio adicional debemos digitar el número 3, y procederemos a  realizar el proceso de añadir
un servicio especial a nuestra reserva.
------------------------------------------------
Ingrese el id de la su habitacion: DO01
Ingrese el tipo de servicio adicional (Desayuno $50, Spa $35, Transporte $50): Desayuno
Notificación para Rafael Alfaro: La reserva ha sido actualizada.
Servicio adicional agregado exitosamente.
-----------------------------------------------
8-Luego podemos digitar nuevamente el número 5 que nos mostrara la reserva con el servicio añadido 
-------------------------------------------------------------
Reserva para habitación DO01       cuesta 250.00    
a nombre de: Rafael Alfaro                 
Teléfono: 70894142                      
Servicios relacionados:
- Desayuno                                               
-------------------------------------------------------------

9-Si queremos retirar un servicio digitamos en 4  para que nos de la opcion de pedir nuestro ID  de habitación,
al ingresar el ID nos mostrara los servicios adicionales que se tienen,debemos ingresar el número del servicio a eliminar.
------------------------------------------------------------
Ingrese el id de su habitación: Do01
Servicios adicionales:
1. Desayuno
Ingrese el número del servicio que desea eliminar: 1
Notificación para Rafael Alfaro: La reserva ha sido actualizada.
Servicio adicional eliminado exitosamente
----------------------------------------------------------
10-Tambien tenemos un  item que nos muestra habitaciones para reservar,al digitar el 6 nos mostrara  las habitaciones disponibles.
6
---------------------------------
Habitaciones disponibles:
id: SE01Tipo: Sencilla - Precio: 100.0
id: SE02Tipo: Sencilla - Precio: 100.0
id: SU01Tipo: Suite - Precio: 500.0
------------------------------------
11-Por ultimo tenemos la eliminacion de la reserva en su totalidad que la podemos hacer  ingresando el número 2 :
+-----------------------------------------+
| Sistema de ReservaBasicas de Hotel SRH7 |
| 1. Hacer una Reserva                    |
| 2. Eliminar una Reserva                 |
| 3. Agregar servicio a una Reserva       |
| 4. Quitar servicio de una Reserva       |
| 5. Mostrar Reservas                     |
| 6. Mostrar Habitaciones Disponibles     |
| 7. Salir                                |
| Seleccione una opcion:                  |
+-----------------------------------------+
2
Ingrese el número de su habitación para eliminar su reserva: DO01
Reserva eliminada exitosamente.


12- Para poder salir del programa precionamos el numero 7

    7
  ---------------------
Saliendo del sistema...
--------------------------
Process finished with exit code 0
