# 🎮 SK Mando - Emulador de Mando Xbox para PC (Warzone Edition)

**SK Mando** es una herramienta avanzada desarrollada en Python que emula un controlador oficial de Xbox 360 en Windows utilizando **ViGEmBus**. Está diseñada específicamente para jugadores de PC en títulos competitivos como *Call of Duty: Warzone*, permitiendo mapear el teclado y el mouse con una precisión y fluidez excepcionales.

---

## ✨ Características Principales

* **Interfaz Gráfica Moderna (GUI):** Panel oscuro interactivo con diseño visual de mando de Xbox.
* **Mapeo Personalizable con 1 Clic:** Haz clic en cualquier botón del esquema para reasignarlo instantáneamente a cualquier tecla de tu teclado.
* **Movimiento Fluido de Cámara (Mouse):** Motor de alta frecuencia (200 Hz) con interpolación lineal (**LERP**) para evitar tirones o retardos en los giros de cámara.
* **Palanca Izquierda por WASD:** Movimiento direccional preciso en 8 direcciones.
* **Persistencia de Configuración:** Guarda automáticamente tus asignaciones de teclas en un archivo `config_mando_warzone.json`.
* **Control de Sensibilidad Deslizante:** Ajusta la velocidad del mouse en tiempo real directamente desde la interfaz.

---

## 🛠️ Requisitos del Sistema

1. **Driver ViGEmBus:** Es obligatorio tener instalado el controlador oficial de Nefarius ViGEmBus para que Windows reconozca el mando virtual.
   * Puedes instalarlo mediante PowerShell con:
     ```bash
     winget install nefarius.ViGEmBus
     ```
2. **Python 3.x** instalado en tu sistema.

---

## 📦 Instalación y Dependencias

Abre tu terminal (CMD o PowerShell) e instala las librerías necesarias ejecutando:

```bash
pip install vgamepad pynput pyinstaller
