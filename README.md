# TDD-Micros-React
Realizado por Raúl Vázquez y Daniel Ibáñez.
Los microservicios deberían registrarse con Eureka Server y pensábamos en utilizar el puerto de Eureka Server como un proxy para las peticiones REST de los microservicios, pero no teníamos suficiente tiempo.
Los microservicios priceservice y flightservice tienen un controlador para añadir información y otro para recibirla en formato JSON. El microservicio fullinfoservice hace una petición GET a cada uno de los otros dos microservicios para recoger la información una vez añadida y la devuelve en formato JSON.
