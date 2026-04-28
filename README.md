# Actividades Unidad 7, Explicación diagramas - Rubén Ortiz León

## Caso de Uso - Actividad 1
Incluimos un Socio y un Administrador que desempeñaran distintas funciones.
El Socio debera identificarse y debera identificarse y elegir entre reservar una pista en el que tendra obligatoriamente que verficarse los pagos pendientes (por eso usamos include) o apuntarse a una clase en el que podra elegir si contratar un seguro (por eso usamos extends).
El Administrador podra elegir entre dar de alta nuevas clases o gestionar los pagos de los socios.

## Actividades - Actividad 1
El proceso empieza pidiento elgir la fecha y la hora, una vez elegida se comprobara la disponibilidad, de no estar disponible te pedira elegir otra fecha y hora o acabar el proceso, si eliges nuevamente la fecha y hora se volvera a comprobar la disponibilidad. Si esta disponible se verificara si tienes pagos pendientes no tenerlos se denegara la reserva y si no los tienes se confirmara la reserva y junto a ello se enviara un email de confimacion (por eso usamos el extends).