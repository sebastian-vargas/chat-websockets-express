# chat-websockets-express

APP CHAT CON WEBSOCKETS
Chat Implemented with socket.io (vercel), node.js, vanilla.js, tursoBD, broadcast

Notes:
websockets  stateful, no cacheable
usa TCP como protocolo de transporte, pueden intercambiar mensajes en cualquier momento
casos de uso: realtime, info ida y vuelta, poca latencia
Event Driven  (basado en eventos) bidireccional
	Inicia una petición, el server responde a la primer petición, luego queda una conexión persistente con websockets, la conexión es bidireccional

MORGAN: es una dependencia, es un logger que guarda una traza, dice la petición que se ha hecho, status, etc
WS : es una dependencia para uso de websockets como socket.io (no la estoy usando para este proyecto)
Socket.io: se usa en este proyecto webSockets in, out
Cliente con vanilla.js
BroadCast envio global de un mensaje
Wsl para tener un subsistema de Linux en Windows y poder instalar TURSO que va ser la BD con SQLite
