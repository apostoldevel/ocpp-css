# OCPP Central System Service

Central System for charging stations for electric cars.

Built on base [OCPP Central System](https://github.com/apostoldevel/apostol-cs) and [Апостол CRM](https://github.com/apostoldevel/apostol-crm).


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
- [http://cs.ocpp-css.com](http://cs.ocpp-css.com)


Authorize:
~~~
username: demo
password: demo
~~~

RFID-card:
~~~
idTag: demo
~~~

API (Swagger):
http://cs.ocpp-css.com/docs

Check API:
http://cs.ocpp-css.com/api/v1/ping


Central System Service (CSS)
-

Automated system for processing data from charging stations.


Authorization:
~~~
username: demo
password: demo
~~~

API (Swagger):
https://ocpp-css.ru/docs


Check API:
https://ocpp-css.ru/api/v1/ping


Contact
-

We invite enthusiasts to cooperate.

email: apostoldevel@gmail.com
