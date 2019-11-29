# Project 2

Web Programming with Python and JavaScript

## Welcome to KuraKani

este servicio de mensajeria usa flask, es similar a Slack aka Flack
Aqui es posible iniciar sesion con un nombre de usuario, crear canales(chatrooms) para comunicarse
Tambien unirse a chats que ya se han creado por otros usuarios y unirse en su converssacion
Al conectarse a un chat es posible enviar y recibir mensajes entre usuarios en tiempo real.
los chays pueden cargarse si usted tuvo un problema de coneccion y ver los mensajes que se emitieron en su ausencia.

`application.py` is the Flask application.

`templates/` folder contains HTML5 jinja2 templates.

`static` contiene los codigos de  transmision de tiempo real entre cliente y servidor usando websocket

***
para correr esta aplicaccion se tiene que correr el siguiente comando 

`pip install -r requirements.txt`

**estando en el directorio `application.py`.**

Bases de datos no son usadas, se usa localstorage 
