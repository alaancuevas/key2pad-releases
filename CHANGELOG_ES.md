# Historial de Cambios (Changelog)

Todos los cambios notables en Key2Pad serán documentados aquí.

Formato: `[versión] — AAAA-MM-DD`

---

## [1.0.0] — 2026-06-07

### 🎉 Lanzamiento Oficial

- Emulación de control virtual de Xbox 360 mediante ViGEmBus
- Setup Wizard con detección e instalación automática de drivers
- Perfiles de juego organizados por género: FPS, Carreras, RPG, Plataformas, Pelea, General
- Sincronización Cloud de Perfiles — Guarda y restaura tus perfiles desde la nube.
- Activa o desactiva el pipeline con la tecla `F12` en cualquier momento
- Inicio de sesión con Google para guardar la licencia y perfiles en la nube
- Multi-Keyboard — Detección e inyección exclusiva para usar un segundo teclado.
- Sistema de código de activación mejorado con recuperación (Gumroad Native Keys)
- Overlay de input en vivo (Modo Píldora o Control) — mira tus pulsaciones en tiempo real en pantalla
- Parches Críticos (Under the hood):
  - Solucionado riesgo de memoria (Memory Leaks / OOM) en el puente nativo C++/JS.
  - Mayor seguridad en la navegación interna.
  - Corrección de sincronización de licencias con Gumroad.