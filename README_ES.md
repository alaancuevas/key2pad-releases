# Key2Pad

> **Tu teclado es ahora un control de Xbox.**
> Jugá cualquier juego de Steam, Windows o lo que sea — sin comprar un gamepad.

**Key2Pad** es una app de Windows que convierte tu teclado en un gamepad virtual Xbox 360 en tiempo real. No emula a nivel del juego: instala un dispositivo de gamepad virtual real que es reconocido nativamente por Steam y cualquier juego que soporte XInput. 

---

## ⬇️ Descarga e Instalación

1. Ve a la página de [**Releases**](https://github.com/alaancuevas/key2pad-releases/releases/latest) y descarga el instalador `Key2Pad-Setup.exe`.
2. Ejecuta el instalador. En el primer inicio, el Asistente de Configuración se abrirá automáticamente.
3. Key2Pad detectará si falta **ViGEmBus** y lo instalará con un clic.
4. Selecciona un perfil inicial y haz clic en **Start Playing**.

### ⚠️ Advertencia de Windows SmartScreen
Al ser Key2Pad una app indie sin un certificado de firma de código de pago de Microsoft, Windows SmartScreen puede mostrar una advertencia. Esto es un falso positivo.
- Haz clic en **"Más información"**
- Luego haz clic en **"Ejecutar de todas formas"**

Key2Pad no contiene malware. ViGEmBus es de código abierto y está publicado por [Nefarius Software Solutions](https://github.com/nefarius/ViGEmBus).

---

## ⚡ Features

- **Ultra baja latencia** — Pipeline nativo en C++, P95 por debajo de 8ms.
- **Perfiles de juego** — FPS, Carreras, RPG, Plataformas, Pelea y más.
- **Gamepad virtual Xbox 360** — Impulsado por ViGEmBus.
- **Overlay en vivo** — Mira tus inputs en tiempo real en la pantalla.
- **Mapeo de teclas por juego** — Botones, sticks analógicos (deadzone + sensibilidad + curva), gatillos.
- **Favoritos** — Marca perfiles con estrellas para acceso rápido.
- **Login con Google** — Guarda tu licencia en la nube.
- **Alterna en cualquier momento** — Presiona `F12` para pausar/reanudar sin cerrar la app.

---

## 🎮 Remote Play Together — juega en cooperativo sin control

Steam Remote Play Together permite que un amigo se una a tu partida local de forma remota, pero requiere un control en el lado del invitado. Key2Pad soluciona esto convirtiendo el teclado del invitado en un gamepad virtual Xbox 360, sin necesidad de hardware.

**Cómo funciona:**
1. El anfitrión (Host) inicia Key2Pad y lanza el juego
2. El invitado se une a través de Steam Remote Play Together
3. Key2Pad emula un controlador virtual — el invitado juega con su teclado

Key2Pad incluye perfiles dedicados de **Co-op / Remote Play Together** optimizados para este caso de uso.

> ⚠️ Evita su uso en juegos competitivos online. Key2Pad no se hace responsable por baneos de cuentas resultantes de la detección por sistemas anti-trampas. Lee el [aviso legal](#-aviso-legal-sobre-baneos-en-juegos-online) a continuación.

---

## ⛔ Aviso legal sobre baneos en juegos online

Key2Pad emula un controlador virtual Xbox 360 a nivel de controlador (driver). Algunos juegos online con sistemas anti-trampas agresivos (Easy Anti-Cheat, BattlEye, Vanguard) pueden detectar controladores virtuales y marcar las cuentas.

**KEY2PAD NO ASUME RESPONSABILIDAD POR NINGUNA SUSPENSIÓN, BANEO O PENALIZACIÓN DE CUENTAS** resultante del uso de este software en juegos en línea. Úsalo bajo tu propio riesgo en entornos en línea.

---

## 📬 Soporte y Contacto

- **Discord:** próximamente
- **Email:** key2pad.contact@gmail.com
- **Licencia:** disponible en [Gumroad](https://key2pad.gumroad.com/l/connector)

---

## 📄 Licencia

El código fuente de Key2Pad es propietario y no está disponible públicamente.  
ViGEmBus está licenciado bajo MIT por Nefarius Software Solutions.