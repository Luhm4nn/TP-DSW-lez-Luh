# Propuesta TP DSW

## Grupo
### Integrantes
* 53215 - Lezcano, Diego
* 53224 - Luhmann, Emiliano

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
Sistema de Reservas de Funciones para Cine (ButacaLibre)
### Descripción
Plataforma web que permite a los usuarios consultar la cartelera de películas en exhibición, seleccionar funciones específicas, visualizar la disponibilidad de asientos y realizar reservas para asistir a proyecciones cinematográficas.

### Modelo
![imagen del modelo]()


## Alcance Funcional 

### Alcance Mínimo

Alcance Mínimo para Regularidad:
|Req|Detalle|
|:-|:-|
|CRUDsimple|1. CRUD Sala (Integrante 1)<br>2. CRUD Película (Integrante 2)|
|CRUD dependiente|1. CRUD Función {depende de} CRUD Sala y CRUD Película|
|Listado + detalle|1. Listado de funciones filtrado por película y/o fecha, muestra título, sala, fecha y hora => detalle CRUD Función|
|CUU/Epic|1. Selección y reserva de asientos para una función específica|

Adicionales para Aprobación:
|Req|Detalle|
|:-|:-|
|CRUD|1. CRUD Sala<br>2. CRUD Película<br>3. CRUD Cliente<br>4. CRUD Función<br>5. CRUD Asiento<br>6. CRUD Reserva<br>7. CRUD Asiento_Reserva|
|CUU/Epic|1. Gestión de cartelera y programación de funciones: Sistema para crear y administrar las proyecciones de películas en diferentes salas y horarios<br>2. Proceso de reserva y pago de entradas: Flujo completo donde el cliente selecciona función, asientos y realiza el pago|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Reporte de ventas filtrado por película y rango de fechas<br>3. Listado de películas más populares basado en reservas|
|CUU/Epic|1. Envío de tickets por email<br>2. Generación de código QR para validación de entrada|
|Otros|1. Envío de tickets por email<br>2. Generación de código QR para validación de entrada|

