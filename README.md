# 🎮 ECUREGIONES 3D

> Proyecto de realidad virtual 3D desarrollado con Unity y C#, enfocado en la enseñanza y conocimiento de las regiones ecuatorianas para instituciones y público escolar mediante una interacción inmersiva y mecánicas de juego en VR.

![Gameplay](Screenshots/gameplay.png) 

---

## 📌 Descripción

Este proyecto consiste en el desarrollo de una experiencia interactiva y educativa de realidad virtual 3D utilizando Unity. Su objetivo principal es enseñar sobre las distintas regiones de Ecuador de manera inmersiva, permitiendo al usuario interactuar con diferentes elementos del entorno, explorar los escenarios y realizar acciones a través de los controladores VR.

El desarrollo se llevó a cabo utilizando C# y Unity XR Interaction Toolkit, implementando la lógica de interacción, gestión de escenas y las mecánicas principales de la experiencia educativa, buscando resolver la falta de herramientas inmersivas e innovadoras para el aprendizaje de la geografía ecuatoriana en las escuelas.

## 🎥 Demo

[▶️ Ver demostración del proyecto](#) 

## 🛠️ Tecnologías

- Unity
- C#
- Unity XR Interaction Toolkit
- XR / Virtual Reality
- Git / GitHub
- Visual Studio

## 🎮 Características

- 🥽 Experiencia educativa e inmersiva de realidad virtual 3D sobre las regiones del Ecuador.
- 🎯 Interacción con objetos educativos mediante controladores VR.
- 🖐️ Sistema de interacción y manipulación de elementos del entorno.
- 🎬 Gestión fluida de escenas para representar diferentes regiones.
- ⚙️ Mecánicas desarrolladas integralmente en C#.
- 🧠 Lógica de comportamiento de objetos y retroalimentación para el aprendizaje.

## 🧩 Arquitectura / estructura

El proyecto sigue una estructura organizada para facilitar su mantenimiento y escalabilidad:

```text
Assets/
├── EspeWall.cs                # Script principal actual en C# de lógica del entorno
├── HotelRoom-Mavi3D/          # Assets y modelo del entorno de la habitación 3D
├── Samples/                   # Scripts y recursos base del XR Interaction Toolkit
├── Scenes/                    # Escenas del proyecto (LobbyScene, SampleScene)
├── XR/ y XRI/                 # Configuraciones del rig y sistema de Realidad Virtual
└── ...
```

Los scripts y recursos están organizados por responsabilidad para permitir la reutilización de código y facilitar la integración continua del proyecto.

## 💻 Scripts principales

A continuación se destacan algunos de los scripts principales de la lógica de interacción y comportamiento:

| Script | Responsabilidad |
| ------ | --------------- |
| [`EspeWall.cs`](Assets/EspeWall.cs) | Lógica específica del comportamiento de muros interactivos y entorno |

*(Nota: La aplicación del lenguaje C# en el proyecto actualmente se encuentra centralizada en `EspeWall.cs`. Los demás scripts en C# presentes en el repositorio corresponden a las lógicas predeterminadas de interacción y movimiento provistas por los paquetes de **XR Interaction Toolkit** y **XR Hands** en la carpeta `Assets/Samples/`).*

## 📸 Capturas

### Entorno VR
![Entorno VR](Screenshots/entorno.png)

### Interacción y Aprendizaje
![Interacción](Screenshots/interaccion.png)

### Gameplay General
![Gameplay](Screenshots/gameplay.png)

*(Nota: Agrega tus propias capturas en la carpeta `Screenshots` y actualiza las rutas).*

## 🚀 Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/Ale8Daniel8Armas/ECUREGIONES_VR.git
```
2. Abrir el proyecto utilizando **Unity Hub**.
3. Utilizar la versión de Unity **6000.4.9f1**.
4. Configurar el dispositivo VR compatible (Oculus/Meta Quest, etc.).
5. Abrir la escena principal desde: `Assets/Scenes/LobbyScene.unity` o `SampleScene.unity`.

### ⚠️ Importante
> El proyecto fue desarrollado utilizando la versión exacta de Unity: **`6000.4.9f1`**

## 🥽 Requisitos

- Unity 6000.4.9f1
- SO: Windows 10 / 11
- Dispositivo VR compatible (Meta Quest 2/3, SteamVR, etc.)
- Controladores VR
- PC con capacidad para ejecutar aplicaciones de Realidad Virtual (GPU dedicada recomendada)

## 📚 Aprendizajes

Durante el desarrollo de **ECUREGIONES 3D** trabajé y mejoré mis habilidades en:

- Desarrollo de aplicaciones interactivas e inmersivas con Unity.
- Programación orientada a objetos con C#.
- Implementación de interacciones en realidad virtual usando el XR Interaction Toolkit.
- Diseño de experiencias educativas y gestión de escenas y objetos 3D.
- Organización, estructuración y mantenimiento de proyectos de Unity.
- Control de versiones utilizando Git y GitHub.

## 👨‍💻 Autor

**Daniel Armas**

Desarrollador de Software

- 💼 LinkedIn: [Mi LinkedIn](https://www.linkedin.com/in/alejo88/)
- 🌐 Portfolio: [Mi Portfolio](https://portfolio-web-alejo.vercel.app/) 
- 💻 GitHub: [Mi GitHub](https://github.com/Ale8Daniel8Armas)
