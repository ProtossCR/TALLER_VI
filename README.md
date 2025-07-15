# TALLER_VI

TALLER VI


---

## 🧠 Descripción

- **Servidor UDP** (`UDPServer.java`):  
  - Escucha en el puerto `1234`.  
  - Recibe mensajes de clientes y muestra en consola la hora, IP:puerto y contenido.  
  - Permite responder manualmente a cada mensaje vía `Scanner`.  
  - Cierra al recibir o enviar el comando especial `FIN`.

- **Cliente UDP 1 Y 2** (`UDPClient.java`):  
  - Se conecta al servidor en `localhost:1234`.  
  - Envía y recibe mensajes de forma interactiva usando `Scanner`.  
  - Permite terminar la sesión local con `salir` o cerrar todo enviando `FIN`.


---

## 🔧 Requisitos

- Java 8 o superior  
- NetBeans (u otro IDE compatible)  
- Conexión local en `localhost`  

---



## 🔧 Ejecución del servidor

Abre el proyecto UDPServerChat en NetBeans.

Ejecuta la clase udp.server.UDPServer.

Ejecución del cliente

Abre el proyecto UDPClientChat en NetBeans.

Ejecuta la clase cliente 1 y 2

## 🔧 Interacción

En cada consola, escribe tu mensaje y presiona Enter.

Para cerrar sólo el cliente, escribe salir.

Para cerrar todo (cliente y servidor), envía FIN desde el cliente y responde FIN en el servidor.
