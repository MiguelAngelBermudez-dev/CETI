![[apuntes.jpg]]
* Modelo de capas 
* *modelo PDU
* Dispositivos de redes 
* Protocolos 
* Dirección lógica y física
* Tipos de ataques 

  

| TCP/IP      | OSI                | PDU      | DISPOSITIVOS              | PROTOCOLOS                               | DIRECCIONES      | ATAQUES |
| ----------- | ------------------ | -------- | ------------------------- | ---------------------------------------- | ---------------- | ------- |
| 4Apliacion  | 7-aplicacion       | datos    | gateway, servidores, NGFW | dns, http, ftp, imap, dhcp,ssh,smtp,pop3 |                  |         |
|             | 6presentacion      | datos    |                           |                                          |                  |         |
|             | 5- sesion          | datos    |                           |                                          |                  |         |
| 3transporte | 4 transporte       | segmento |                           | tcp/udp                                  | puertos          |         |
| 2 internet  | 3- red             | paquetes | Router                    | ipv4,ipv6,icmp                           | dirección logica |         |
| 1 subred    | 2- enlace de datos | trama    | switch/AP                 |                                          | dirección fisica |         |
|             | 1- fisica          | bits     | hub/cables                |                                          |                  |         |
