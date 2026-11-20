# Hi, I'm Francois 👋

I'm from Chile, and I build software that connects to the real world: **building and industrial automation, embedded control, geospatial tools and AI apps that run on your own computer.** I like code that is simple to read, well tested, and honest about what it can't do.

🇪🇸 [Leer en español](#-hola-soy-francois)

## Building automation in a public hospital

Read-only dashboards I built for the BMS of a public hospital, where they are in use. They talk to Sauter controllers over BACnet/IP with no external dependencies, run on a locked-down PC with no internet, and produce printable reports and Excel files. The public versions are anonymized and include a `--demo` mode.

| Project | What it does |
|---|---|
| [**bms-datacenter-climate-monitor**](https://github.com/wizardkillah/bms-datacenter-climate-monitor) | Temperature and humidity in the datacenter, cross-checked against precision AC units through a FieldServer gateway. Includes a documented security audit |
| [**bms-surgical-suite-monitor**](https://github.com/wizardkillah/bms-surgical-suite-monitor) | Operating rooms and delivery rooms: about 970 points from 8 controllers, air handlers, room pressure, medical gases and UPS |
| [**bms-medical-gas-alarms**](https://github.com/wizardkillah/bms-medical-gas-alarms) | Oxygen, medical air, vacuum and nitrogen alarms: 53 points on 16 panels, with discovery tools |
| [**bms-fuel-tank-monitor**](https://github.com/wizardkillah/bms-fuel-tank-monitor) | Diesel tanks for the backup generators: levels, consumption, autonomy and refill detection |
| [**bms-substation-monitor**](https://github.com/wizardkillah/bms-substation-monitor) | Electrical substation: power, voltage, frequency, power factor, harmonics and breakers |
| [**industrial-connectors**](https://github.com/wizardkillah/industrial-connectors) | The building blocks: small Python clients for BACnet/IP, Sauter moduWeb and Mitsubishi MC 1E, tested against simulated devices |

## Embedded and control

| Project | What it does | Built with |
|---|---|---|
| [**fog-collector-controller**](https://github.com/wizardkillah/fog-collector-controller) | Control for motorized fog-collector meshes: a PLC that protects the mesh from wind on its own, and a Raspberry Pi logger. I rebuilt it after auditing my own first prototype | Arduino Opta (C++), Python, Modbus TCP |
| [**lidar-radar-android**](https://github.com/wizardkillah/lidar-radar-android) | Turns a phone without LiDAR into an indoor 3D scanner, combining ARCore depth with an acoustic sonar | Kotlin, ARCore, OpenGL ES |

## Maps, science and apps

| Project | What it does | Built with |
|---|---|---|
| [**cielos-de-ovalle**](https://github.com/wizardkillah/cielos-de-ovalle) | Real-time sky map for observatory visitors in northern Chile. One HTML file, works offline, with its own astronomy engine checked against PyEphem | JavaScript, Canvas |
| [**flood-risk-simulator**](https://github.com/wizardkillah/flood-risk-simulator) | 3D map of the Coquimbo Region that estimates where floods could happen, using real terrain, rain forecasts and an AI advisor. It is a prototype, and it says so | FastAPI, CesiumJS |
| [**merlin-desktop-cat**](https://github.com/wizardkillah/merlin-desktop-cat) | A desktop assistant (a little witch cat) with local or cloud AI and offline voice, that keeps your documents on your PC by default | Electron |
| [**herbal-grimoire**](https://github.com/wizardkillah/herbal-grimoire) | A learning game about medicinal plants, with sourced content and credits for every image | React, Vite |

## What I care about

- **Safety first:** monitoring tools are read-only, no secrets in code, and inputs are validated.
- **Code you can audit:** few dependencies, and tests that run without the real hardware.
- **Honest software:** prototypes say they are prototypes, and simulated data is never shown as real.
- **AI with privacy:** local models first, and AI never drives a relay directly.

## Tools I use

`Python` · `JavaScript` · `Kotlin` · `C++` · `BACnet/IP` · `Modbus` · `MELSEC MC` · `SQLite` · `FastAPI` · `Electron` · `React` · `CesiumJS` · `ARCore` · `Arduino Opta` · `Raspberry Pi` · `GitHub Actions`

I'm a native Spanish speaker and I'm adding English documentation to my projects.

---

## 🇪🇸 Hola, soy Francois

Soy de Chile y hago software que se conecta con el mundo real: **automatización de edificios e industrial, control embebido, herramientas geoespaciales y aplicaciones de IA que funcionan en tu propio computador.** Me gusta el código simple de leer, bien probado y honesto sobre lo que no puede hacer.

🇬🇧 [Read in English](#hi-im-francois-)

### Automatización de edificios en un hospital público

Dashboards de solo lectura que hice para el BMS de un hospital público, donde están en uso. Se comunican con controladores Sauter por BACnet/IP sin dependencias externas, funcionan en un PC restringido y sin internet, y generan informes imprimibles y Excel. Las versiones públicas están anonimizadas y traen un modo `--demo`.

| Proyecto | Qué hace |
|---|---|
| [**bms-datacenter-climate-monitor**](https://github.com/wizardkillah/bms-datacenter-climate-monitor) | Temperatura y humedad del datacenter, cruzadas con los equipos de precisión mediante un gateway FieldServer. Incluye una auditoría de seguridad documentada |
| [**bms-surgical-suite-monitor**](https://github.com/wizardkillah/bms-surgical-suite-monitor) | Pabellones y salas de parto: unos 970 puntos de 8 controladores, UMA, presión de sala, gases clínicos y UPS |
| [**bms-medical-gas-alarms**](https://github.com/wizardkillah/bms-medical-gas-alarms) | Alarmas de oxígeno, aire medicinal, vacío y nitrógeno: 53 puntos en 16 tableros, con herramientas de descubrimiento |
| [**bms-fuel-tank-monitor**](https://github.com/wizardkillah/bms-fuel-tank-monitor) | Estanques de petróleo de los generadores de respaldo: nivel, consumo, autonomía y detección de recargas |
| [**bms-substation-monitor**](https://github.com/wizardkillah/bms-substation-monitor) | Subestación eléctrica: potencia, tensión, frecuencia, factor de potencia, armónicos e interruptores |
| [**industrial-connectors**](https://github.com/wizardkillah/industrial-connectors) | Las piezas base: clientes pequeños en Python para BACnet/IP, Sauter moduWeb y Mitsubishi MC 1E, probados con dispositivos simulados |

### Control embebido

| Proyecto | Qué hace | Hecho con |
|---|---|---|
| [**fog-collector-controller**](https://github.com/wizardkillah/fog-collector-controller) | Control de mallas atrapanieblas motorizadas: un PLC que protege la malla del viento por sí solo y un registrador en Raspberry Pi. Lo reconstruí después de auditar mi propio primer prototipo | Arduino Opta (C++), Python, Modbus TCP |
| [**lidar-radar-android**](https://github.com/wizardkillah/lidar-radar-android) | Convierte un teléfono sin LiDAR en un escáner 3D de interiores, combinando la profundidad de ARCore con un sonar acústico | Kotlin, ARCore, OpenGL ES |

### Mapas, ciencia y aplicaciones

| Proyecto | Qué hace | Hecho con |
|---|---|---|
| [**cielos-de-ovalle**](https://github.com/wizardkillah/cielos-de-ovalle) | Mapa del cielo en tiempo real para quienes visitan observatorios del norte de Chile. Un solo HTML, funciona sin conexión y tiene su propio motor astronómico, contrastado con PyEphem | JavaScript, Canvas |
| [**flood-risk-simulator**](https://github.com/wizardkillah/flood-risk-simulator) | Mapa 3D de la Región de Coquimbo que estima dónde podrían ocurrir inundaciones, con terreno real, pronóstico de lluvia y un asesor con IA. Es un prototipo y lo dice | FastAPI, CesiumJS |
| [**merlin-desktop-cat**](https://github.com/wizardkillah/merlin-desktop-cat) | Un asistente de escritorio (un gatito brujo) con IA local o en la nube y voz sin conexión, que por defecto mantiene tus documentos en tu PC | Electron |
| [**herbal-grimoire**](https://github.com/wizardkillah/herbal-grimoire) | Un juego para aprender sobre plantas medicinales, con contenido con fuentes y créditos de cada imagen | React, Vite |

### Lo que me importa

- **Seguridad primero:** las herramientas de monitoreo son de solo lectura, sin secretos en el código y con entradas validadas.
- **Código que se puede auditar:** pocas dependencias y pruebas que corren sin el hardware real.
- **Software honesto:** los prototipos dicen que son prototipos, y un dato simulado nunca se muestra como real.
- **IA con privacidad:** modelos locales primero, y la IA nunca maneja un relé directamente.

### Herramientas

`Python` · `JavaScript` · `Kotlin` · `C++` · `BACnet/IP` · `Modbus` · `MELSEC MC` · `SQLite` · `FastAPI` · `Electron` · `React` · `CesiumJS` · `ARCore` · `Arduino Opta` · `Raspberry Pi` · `GitHub Actions`

Mi lengua materna es el español y estoy agregando documentación en inglés a mis proyectos.
