# trips-multiload

## Descripción del problema

Se tiene el perfil de un conductor y un conjunto de viajes. 

El conductor posee un Cada viaje posee:
- Hora en que comienza su jornada laboral
- Hora en que termina su jornada laboral
- Vehículo con capacidad máxima de personas a transportar

Cada viaje posee:
- Punto de recogida
- Punto de entrega
- Hora de recogida
- Hora de entrega
- Cantidad de personas que participan en el viaje

El objetivo es que el conductor pueda realizar varios viajes a la vez en un sólo recorrido maximizando la cantidad de viajes y cumpliendo con las restricciones siguientes:
- La distancia a recorrer debe ser la menor posible
- Se deben abarcar la mayor cantidad de viajes posibles
- Se deben cumplir con los horarios de entrega
- Se deben cumplir con los horarios de recojida (existe un aventana de tiempo de 15 minutos antes en los que el conductor puede realizar la recogida de los pasajeros del viaje correspondiente)
- La capacidad del vehículo nunca debe ser rebasada de su capacidad máxima
