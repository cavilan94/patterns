Este repositorio contiene el diseño de una aplicación de chat simple, donde cada vez que se corre la aplicación, se genera una nueva ventana de chat que puede participar en la conversación, la conversación entre los usuarios es compartida, es decir que lo que escribe cualquier ventana de chat, se ve reflejado en las otras ventanas, cuando se genera un nuevo chat se cargan inmediatamente el historico de los mensajes generados previamente.

A continuación se docuemntan las aprtes del codigo:

1) Importación de librerias requeridas para poder establecer el chat entre los usuarios:

 ![image](https://github.com/user-attachments/assets/4d3e6d48-93a6-43a8-9a9a-b2fa27bd9374)

2) unción principal, SimpleChat

 ![image](https://github.com/user-attachments/assets/26b11bdd-2a0b-4d21-a7ca-465f22aed1f4)


3) el hsitorial y escritura de los eventos para su replicación en los chats,se realiza por medio de un event loop.

 ![image](https://github.com/user-attachments/assets/84ae37bb-4689-4c30-aa74-b8bda4a33d64)

En caso de que se ingrese un mensaje que inicie con exit o quit se rompe el loop, indicando la salida del usuario del chat.

4) Función para escribir el historial del chat registardo, en el chat del neuvo usuario que se acaba de conectar.

 ![image](https://github.com/user-attachments/assets/54e8a4a0-7b1c-4bb0-8ea2-2c295178b841)

5) Archivo pom, donde estan las dependencias requeridas y las especificaciones, el codigo esta diseñado para la version 23 de netsbeans, si se compila en otra version es importante cambiar este valor a la versión correcta.

   ![image](https://github.com/user-attachments/assets/5ae6f2fc-3c9a-4aeb-9bea-35f34ea6fcd7)
