
Sistema de Reserva Básica de Hotel (SRH7)

Detalle de Ejecución

1. Descarga del Proyecto
- Descarga el proyecto desde la rama `master`.

2. Apertura en el IDE
Abre el proyecto en tu IDE de desarrollo preferido.

3. Ubicación de la Clase `Main`
- Busca la clase `Main`, que es la encargada de ejecutar el proyecto.

4. Ejecución del Menú
- Al ejecutar el programa, se presentará un menú con las siguientes opciones:

```
+-----------------------------------------+
| Sistema de Reserva Básica de Hotel SRH7 |
| 1. Hacer una Reserva                    |
| 2. Eliminar una Reserva                 |
| 3. Agregar servicio a una Reserva       |
| 4. Quitar servicio de una Reserva       |
| 5. Mostrar Reservas                     |
| 6. Mostrar Habitaciones Disponibles     |
| 7. Salir                                |
| Seleccione una opción:                  |
+-----------------------------------------+
```

5. Navegación en el Menú
- Selecciona las opciones del menú ingresando el número correspondiente.

---

Guía de Opciones

1. Hacer una Reserva
- Selecciona la opción `1`.
- El programa te solicitará datos como:
  - Nombre
  - Teléfono
  - Tipo de habitación
  - Fecha de entrada
  - Fecha de salida
- Una vez ingresados los datos, el sistema confirmará la reserva con un mensaje de éxito.

---

2. Mostrar Reservas
- Selecciona la opción `5`.
- Verás un detalle de las reservas realizadas. Por ejemplo:
```
-------------------------------------------------------------
Reserva para habitación DO01       cuesta 200.00    
A nombre de: Rafael Alfaro                 
Teléfono: 70894142                      
No hay servicios relacionados con esta reserva.
-------------------------------------------------------------
```

---

3. Agregar Servicios Adicionales
- Selecciona la opción `3`.
- Ingresa el ID de tu habitación y selecciona el servicio adicional:
  - Desayuno ($50)
  - Spa ($35)
  - Transporte ($50)
- El sistema confirmará la actualización. Por ejemplo:
```
------------------------------------------------
Ingrese el id de su habitación: DO01
Ingrese el tipo de servicio adicional (Desayuno $50, Spa $35, Transporte $50): Desayuno
Notificación para Rafael Alfaro: La reserva ha sido actualizada.
Servicio adicional agregado exitosamente.
------------------------------------------------
```
- Selecciona `5` nuevamente para ver la reserva actualizada:
```
-------------------------------------------------------------
Reserva para habitación DO01       cuesta 250.00    
A nombre de: Rafael Alfaro                 
Teléfono: 70894142                      
Servicios relacionados:
- Desayuno                                               
-------------------------------------------------------------
```

---

4. Quitar Servicios Adicionales
- Selecciona la opción `4`.
- Ingresa el ID de tu habitación y el número del servicio que deseas eliminar:
```
------------------------------------------------------------
Ingrese el id de su habitación: DO01
Servicios adicionales:
1. Desayuno
Ingrese el número del servicio que desea eliminar: 1
Notificación para Rafael Alfaro: La reserva ha sido actualizada.
Servicio adicional eliminado exitosamente.
------------------------------------------------------------
```

---

5. Mostrar Habitaciones Disponibles
- Selecciona la opción `6` para ver las habitaciones disponibles:
```
---------------------------------
Habitaciones disponibles:
ID: SE01 Tipo: Sencilla - Precio: 100.0
ID: SE02 Tipo: Sencilla - Precio: 100.0
ID: SU01 Tipo: Suite - Precio: 500.0
---------------------------------
```

---

6. Eliminar una Reserva
- Selecciona la opción `2`.
- Ingresa el ID de tu habitación para eliminar la reserva:
```
Ingrese el número de su habitación para eliminar su reserva: DO01
Reserva eliminada exitosamente.
```

---

7. Salir del Sistema
- Selecciona la opción `7` para salir del programa:
```
Saliendo del sistema...
Process finished with exit code 0
```

---
