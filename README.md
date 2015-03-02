# ejercicio 8 - 

Comunicaciones en red. UDP no concurrente.
Implementar el cliente y el servidor del protocolo “¿Qué hora es?” utilizando UDP en modo no- concurrente. El protocolo funciona de la siguiente manera: el cliente envía un datagrama vacío contra el servidor y este le responde con la fecha y hora actual según su reloj en formato “[dia del mes]/[mes]/[año] [hora:minutos:segundo” todos en formato numérico (por ejemplo, 21/09/2013 17:07:34). Para la realización de este ejercicio utilizar la clase java.text.SimpleDateFormat.
El ejecutable del servidor debe admitir como parámetros el puerto del servicio, y si no se pasa ninguno este debe ser el puerto 12345. El ejecutable del cliente debe admitir como parámetros obligatorios la dirección y el puerto del servidor.


## Installation
Ejecutar simplemente.