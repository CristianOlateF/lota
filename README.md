# 🎰 Lota Tradicional Chilena (1-90) — TV & Remote

Aplicación web interactiva desarrollada para jugar a la **Lota Tradicional Chilena** de 90 números. Diseñada con una arquitectura de doble pantalla: un tablero principal optimizado para proyectar en Smart TVs o computadores, y un **control remoto web** para operar el juego desde el celular de forma inalámbrica.

---

## 🚀 ¡Juega Directamente!

No necesitas instalar nada ni configurar servidores. Puedes usar la aplicación pública directamente ingresando al siguiente enlace desde el navegador de tu TV o Mac:

👉 **[https://cristianolatef.github.io/lota/](https://cristianolatef.github.io/lota/)**

---

## ✨ Características Principales

* **Tablero Tradicional (1-90):** Interfaz limpia dividida por columnas de decenas, perfecta para visualizar los números cantados a gran distancia.
* **Efectos y Animaciones:** Simulación de sorteo con animación de giro en madera y resaltado visual automático de las casillas sorteadas.
* **Cantado de Números por Voz (TTS):** Integración con la API de síntesis de voz del navegador (`SpeechSynthesis`) con selector de voces y control de silenciado.
* **Conexión P2P en Tiempo Real (WebRTC):** Vinculación directa entre el teléfono y la pantalla principal mediante [PeerJS](https://peerjs.com/), sin bases de datos ni intermediarios.
* **Emparejamiento por QR:** Generación dinámica de un código QR único en la pantalla principal para conectar el celular al instante.
* **100% Serverless:** Estructura puramente estática alojada y ejecutada en **GitHub Pages**.

---

## 🎮 Instrucciones de Uso

1. **Abrir en la Pantalla (TV / Mac):** Ingresa a [https://cristianolatef.github.io/lota/](https://cristianolatef.github.io/lota/) en el dispositivo donde proyectarás el juego.
2. **Activar Audio:** Presiona el botón verde inicial para conceder permisos de reproducción de audio al navegador.
3. **Vincular el Celular:** Escanea con la cámara de tu smartphone el código QR que aparece en la esquina inferior derecha de la pantalla.
4. **¡A Jugar!:** Utiliza los botones del control remoto en tu celular para **Girar Ficha 🎲**, activar/silenciar la voz o reiniciar la partida cuando lo necesites.

---

## 🔒 Privacidad y Seguridad

* **Sesiones Privadas y Dinámicas:** Cada vez que la pantalla principal se recarga, se genera un identificador de sesión aleatorio mediante WebRTC. Ningún usuario externo podrá conectarse ni interferir en tu partida a menos que tenga acceso visual directo al código QR proyectado en la pantalla.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 / CSS3:** Estructuras modernas con CSS Grid, Flexbox y animaciones keyframes.
* **JavaScript (ES6+):** Lógica del juego, manejo de estados asíncronos y síntesis de voz nativa.
* **PeerJS:** Abstracción para conexiones WebRTC seguras y de baja latencia.
* **QRCode.js:** Librería ligera para renderizar códigos QR directamente en el cliente.

---

## 💻 Para Desarrolladores (Clonar o Desplegar tu propia versión)

Si deseas clonar este proyecto o hacer tu propia versión:

1. Clona el repositorio o descarga el archivo `index.html`.
2. Súbelo a tu propio repositorio de GitHub.
3. Dirígete a **Settings > Pages** en tu repositorio.
4. Selecciona la rama `main` en la carpeta `/ (root)` y guarda los cambios.

---

## 📄 Licencia

Este proyecto es de código abierto bajo los términos de la licencia [MIT](LICENSE).
