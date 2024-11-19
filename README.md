MultiChat - Chat Multicanal en Python
Este proyecto es una implementación básica de un chat multiusuario en Python, utilizando sockets y hilos (threads) para permitir la comunicación en tiempo real entre varios clientes conectados a un servidor central.

Características:
Conexión de múltiples clientes: Varios usuarios pueden unirse al chat y enviar mensajes entre ellos.
Comandos básicos:
!usuarios: Muestra la lista de usuarios conectados.
Mensajes en tiempo real: Los mensajes enviados por un usuario se propagan instantáneamente a los demás usuarios conectados.
Salida del chat: Los usuarios pueden desconectarse, y el servidor notificará a los demás usuarios.
Tecnologías utilizadas:
Python 3.x
Sockets
Hilos (Threading)
Interfaz gráfica (Tkinter)
¿Cómo ejecutar?
Cloná el repositorio.
Ejecutá el servidor con python servidor.py.
Ejecutá los clientes con python cliente.py desde diferentes terminales o ventanas.
