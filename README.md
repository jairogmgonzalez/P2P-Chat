# 💬 Chat P2P - Proyecto de Comunicación en Red  

Chat P2P es una aplicación de mensajería **peer-to-peer (P2P)** que permite la comunicación entre usuarios de forma directa, sin necesidad de servidores intermedios. Compatible con **interfaz gráfica (GUI) y consola (CLI)**, funciona en sistemas **Ubuntu/Linux** y **Windows**, ofreciendo una experiencia de chat fluida y eficiente.  

---

## 🚀 **Características Principales**  
✅ **Mensajería en tiempo real** entre usuarios conectados.  
✅ **Modo consola (CLI)** para control total con comandos.  
✅ **Interfaz gráfica (GUI)** intuitiva y amigable.  
✅ **Sistema de contactos** para gestionar tus conexiones.  
✅ **Transferencia de archivos** de forma rápida y segura.  
✅ **Multiplataforma**: Funciona en **Ubuntu/Linux y Windows**.  

---

## 🖥️ **Interfaz de Usuario**  

### 🌐 **Modo GUI**  
La interfaz gráfica está diseñada para facilitar la interacción, con una lista de contactos, historial de chats y opciones de conexión.  


### ⚡ **Modo CLI**  
Para usuarios avanzados, el modo consola permite ejecutar comandos rápidos y eficientes.  

```bash
/register                   # Inicia el registro: solicita nombre de usuario y puerto
/login                      # Inicia sesión introduciendo tu ID (IP:PUERTO)
/add IP PUERTO              # Agrega un nuevo contacto (establece conexión automáticamente)
/connect IP PUERTO          # Establece conexión con un contacto ya agregado
/select IP:PUERTO           # Selecciona un contacto para iniciar conversación
/file /ruta/archivo.txt     # Envía un archivo al contacto seleccionado
/id                         # Muestra tu propio ID de usuario
/help                       # Muestra la lista de comandos disponibles
/exit                       # Cierra la aplicación
