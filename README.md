# OCPP Central System as Service

Central System for charging stations for electric cars.

Built on base [OCPP Central System](https://github.com/apostoldevel/apostol-cs) and [Apostol CRM](https://github.com/apostoldevel/apostol-crm).


Overview
-
Open Charge Point Protocol [OCPP](http://ocppforum.net) is a communication protocol between multiple charging stations ("charge points") and a single management software ("central system").


Central System (CS)
-

You can connect your station to a demo central system.

Connection addresses:
- WebSocket: ws://ws.ocpp-css.com/ocpp
- SOAP: http://soap.ocpp-css.com/Ocpp

Case matters.

To control the charging station, use the web shell at:
- [https://cs.ocpp-css.com](https://cs.ocpp-css.com)


Authorization:
~~~
username: demo
password: demo
~~~

RFID-card:
~~~
idTag: demo
~~~

API (Swagger):
https://cs.ocpp-css.com/docs/

Check API:
http://cs.ocpp-css.com/api/v1/ping


Central System as Service (CSS)
-

Automated system for processing data from charging stations.


Authorization:
~~~
username: demo
password: demo
~~~

API (Swagger):
https://css.ocpp-css.com/docs/


Check API:
https://css.ocpp-css.com/api/v1/ping


Contact
-

We invite enthusiasts to cooperate.

email: apostoldevel@gmail.com
