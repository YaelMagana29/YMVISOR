# YMVISOR 👁️
> **Un visor de pantalla completa minimalista, inteligente y de alto rendimiento para capturadoras de video HDMI**

---

**YMVISOR** es una aplicación ultra-ligera y optimizada diseñada específicamente para proyectar la señal de tus capturadoras de video HDMI (USB/DSHOW) directamente en tu pantalla sin retrasos (*input lag*) ni configuraciones complicadas.

Si solo quieres ver y escuchar la señal de un dispositivo externo en tu computadora de forma inmediata, fluida y limpia, este programa elimina por completo la necesidad de usar softwares de streaming pesados, lentos o llenos de menús innecesarios como OBS Studio.

---

## ✨ Características Principales y Todo lo que Incluye

* **📺 Pantalla Completa Inmersiva:** Alterna instantáneamente a pantalla completa pura, eliminando bordes de ventana, barras de tareas de Windows o menús estorbosos para dejar el 100% del espacio a tu video.
* **🎛️ Selector Inteligente y Autodetección:** Interfaz gráfica nativa avanzada que escanea en tiempo real tus dispositivos de video disponibles y componentes de hardware conectados.
* **🔊 Passthrough de Audio Integrado:** Permite mapear y escuchar el sonido directo de la capturadora en tus audífonos, bocinas o cualquier salida del sistema sin desincronización y con opción de silenciado rápido.
* **⚙️ Control de Video y Rendimiento:** Configura resoluciones exactas (desde automáticas hasta 4K) y tasas de refresco/FPS específicos (`24`, `30`, `60` FPS) para exprimir la fluidez de tu hardware.
* **🎨 Temas de Color Personalizables:** Cuenta con dos estilos visuales completos para la interfaz de inicio:
  * **Modo Oscuro (2.0):** Panel moderno y estético de alto contraste azul/gris que evita la fatiga visual de noche.
  * **Modo Pastel (2.1):** Una variante visual más suave y cálida con tonos tierra y acentos personalizados.
* **☀️ Filtros y Ajustes de Imagen en Vivo:** Modifica el **Brillo** y **Contraste** de la transmisión matemática y directamente sobre los fotogramas en tiempo real mientras estás jugando o visualizando en pantalla completa.
* **👾 Discord Rich Presence Nativo:** Integración directa con la API de Discord para mostrar en tu estado de perfil dinámicamente qué dispositivo estás visualizando (`Viendo: Mi Capturadora`, etc.) junto al logo del programa y un contador de tiempo transcurrido.
* **💾 Memoria de Configuración Persistente:** Guarda automáticamente tus últimas preferencias en un archivo `config.json` local. El programa recordará tus dispositivos elegidos, el tema visual, los niveles de brillo/contraste y si Discord estaba encendido para iniciar con un solo clic.

---

## 🎮 Casos de Uso Ideales

* **Jugar Consolas en tu Laptop/PC:** Conecta tu Nintendo Switch, PlayStation, Xbox o consolas retro a una capturadora USB barata y usa tu computadora como monitor portátil sin retraso de entrada.
* **Monitoreo de Cámaras Profesionales:** Utiliza el panel como un monitor de campo gigante para ver con precisión el encuadre y enfoque de cámaras DSLR, videocámaras o GoPro.
* **Sistemas Secundarios y TV:** Visualiza de inmediato menús de decodificadores de cable, Raspberry Pi, servidores sin monitor o computadoras secundarias de manera limpia.

---

## ⌨️ Control Total con Atajos de Teclado (En Transmisión)

| Tecla / Comando | Acción Realizada en Tiempo Real |
| :--- | :--- |
| `ESC` | Cierra la transmisión y sale del programa por completo. |
| `F` | Alterna instantáneamente entre Pantalla Completa y Ventana normal. |
| `M` | Detiene el video actual y te regresa de forma segura al Menú Principal. |
| `F1` | **Disminuye el Brillo** de la imagen (Muestra indicador flotante en pantalla). |
| `F2` | **Aumenta el Brillo** de la imagen (Muestra indicador flotante en pantalla). |
| `F11` | **Disminuye el Contraste** de la imagen en intervalos del 10%. |
| `F12` | **Aumenta el Contraste** de la imagen en intervalos del 10%. |

---

## 🛠️ Requisitos e Instalación del Entorno

Para ejecutar el código fuente en Windows sin problemas de variables de entorno o PATH de Python, usa el lanzador universal de Windows (`py`):

```bash
# 1. Clonar este repositorio
git clone [https://github.com/YaelMagana29/YMVISOR.git](https://github.com/YaelMagana29/YMVISOR.git)
cd YMVISOR

# 2. Instalar todas las dependencias necesarias de un solo golpe
py -m pip install opencv-python pygrabber pypresence sounddevice

# 3. Arrancar la aplicación
py main.py

---
Desarrollado y mantenido por [YaelMagana29](https://github.com/YaelMagana29).
