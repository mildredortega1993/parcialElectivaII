# EP_2
Parcial Electiva 2

Insomnia
--Crear base de datos--
1. Crear Post en el puerto 3000/db
2. Contenido: {"namedb": "shop"}

curl --request POST
--url http://localhost:3000/db
--header 'Content-Type: application/json'
--data '{ "namedb": "Shop" }'
