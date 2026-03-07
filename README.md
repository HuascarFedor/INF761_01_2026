# Plan de Asignatura
## INF761 — Desarrollo de Videojuegos

> **Marco referencial:** El programa docente del proceso enseñanza-aprendizaje está estructurado en correspondencia a los lineamientos del modelo académico, orientado al desarrollo de competencias en las siguientes áreas:
>
> - Dominio de la arquitectura y pipeline de desarrollo en el motor Unity: Comprensión del patrón Entity-Component, ciclo de vida de MonoBehaviour, gestión de assets y sistemas fundamentales del engine.
> - Aplicación de patrones de diseño de software en contextos interactivos: Uso de Singleton, Observer, State Machine, Command y Object Pooling para estructurar sistemas de juego escalables.
> - Programación de mecánicas y sistemas de gameplay: Implementación de game loops, sistemas de inventario, interfaces de usuario, persistencia de datos y gestión de escenas.
> - Integración de físicas, animación, efectos visuales y audio: Manejo del sistema de físicas (Rigidbody, Colliders, Raycasting), Animator Controller, sistemas de partículas y audio espacial.
> - Programación de inteligencia artificial para agentes de juego: Diseño e implementación de NPCs con capacidad de navegación (NavMesh), percepción del entorno y toma de decisiones autónoma.
> - Desarrollo de funcionalidad multijugador y networking: Implementación de arquitecturas cliente-servidor utilizando Netcode for GameObjects, sincronización de estado y servicios de lobby/matchmaking.
> - Optimización, profiling y publicación multiplataforma: Uso del Profiler de Unity, técnicas de batching, LOD y compresión de assets para preparar builds de producción.

---

## I. Identificación de la Asignatura

| Campo | Detalle |
|---|---|
| **Facultad** | Ciencias Puras |
| **Carrera** | Ingeniería Informática |
| **Asignatura** | Desarrollo de Videojuegos |
| **Sigla y código** | INF 761 |
| **Pre-Requisito** | INF 661 |
| **Total horas** | 5 horas |
| **Trabajo independiente/semana** | 5 horas |
| **Número de créditos** | 5 |
| **Horas teóricas** | 0 |
| **Horas prácticas** | 0 |
| **Horas laboratorio** | 5 |
| **Semestre** | Séptimo Semestre (Mención Ingeniería de Software) |
| **Docente** | M. Sc. Huáscar Fedor Gonzales Guzmán |
| **Email** | huascar.fedor@gmail.com |

---

## II. Fundamentación y Justificación

La industria del videojuego constituye uno de los sectores tecnológicos de mayor crecimiento a nivel mundial. El mercado global fue valorado en aproximadamente 184.000 millones de dólares en 2023 y se proyecta que alcance los 665.77 mil millones para 2030, impulsado por el auge del gaming móvil, la realidad virtual y los modelos de monetización en línea.

El desarrollo de videojuegos no es simplemente una actividad de entretenimiento; es una disciplina de ingeniería de alta complejidad que integra programación orientada a objetos, patrones de diseño, simulación física, inteligencia artificial, redes de computadoras y optimización de rendimiento en tiempo real.

La inclusión de esta asignatura en el séptimo semestre se justifica por las siguientes razones:

- **Integración de competencias de ingeniería de software.** El desarrollo de juegos exige la aplicación rigurosa de patrones de diseño, arquitecturas escalables y buenas prácticas de código, consolidando conocimientos previos del plan de estudios.
- **Aplicaciones más allá del entretenimiento.** Unity ha sido adoptado por industrias fuera de los videojuegos, incluyendo cine, automotriz, arquitectura, simulación militar y entrenamiento médico.
- **Relevancia del motor Unity.** Unity y Unreal Engine controlan conjuntamente el 51% del mercado de motores de juego, y Unity domina en el segmento móvil y en proyectos indie.
- **Competencias diferenciadoras.** La programación de IA para agentes inteligentes (FSM, Behavior Trees, NavMesh) y la implementación de networking multijugador son habilidades de alta demanda y baja oferta en el mercado laboral regional.
- **Demanda laboral.** Se proyecta que el empleo para programadores se expandirá un 15% entre 2024 y 2034, y las barreras de entrada para la publicación independiente de juegos se han reducido significativamente.

En síntesis, la asignatura constituye un laboratorio integral donde convergen las disciplinas fundamentales de la ingeniería informática en un contexto motivador, creativo y con alta transferibilidad al mercado laboral.

---

## III. Propósito

Desarrollar en el estudiante la capacidad de diseñar, programar e integrar sistemas interactivos de videojuegos mediante el motor Unity y el lenguaje C#, aplicando patrones de diseño de software, inteligencia artificial, físicas, animación, networking y técnicas de optimización para la publicación de prototipos funcionales en múltiples plataformas.

---

## IV. Competencias de la Asignatura

### 4.1. Competencia Global

Diseñar, programar y publicar prototipos de videojuegos funcionales utilizando el motor Unity y el lenguaje C#, aplicando patrones de diseño de software, inteligencia artificial, sistemas de red y técnicas de optimización para crear experiencias interactivas de calidad.

### 4.2. Competencias Específicas

Al finalizar la asignatura, el estudiante será capaz de:

1. Configurar el entorno de desarrollo Unity, comprender la arquitectura Entity-Component y programar comportamientos básicos de juego utilizando C# y el ciclo de vida de MonoBehaviour.
2. Implementar mecánicas de juego robustas utilizando patrones de diseño de software, sistemas de interfaz de usuario y gestión de escenas para crear experiencias de gameplay completas.
3. Integrar sistemas de físicas, animación, efectos visuales y audio para crear prototipos de videojuegos con retroalimentación sensorial completa y pulido visual.
4. Programar agentes inteligentes con capacidad de navegación, percepción y toma de decisiones utilizando FSM, Behavior Trees, NavMesh y técnicas avanzadas de IA para juegos.
5. Implementar funcionalidad multijugador utilizando Netcode for GameObjects, gestionar sincronización de estado, lobby/matchmaking, y preparar builds optimizados para publicación multiplataforma.

---

## V. Desarrollo de Saberes de la Asignatura

| Saber Conocer | Saber Hacer | Saber Ser |
|---|---|---|
| Conoce la arquitectura del motor Unity, el patrón Entity-Component, el ciclo de vida de MonoBehaviour y los sistemas fundamentales del engine | Configura el entorno de desarrollo, crea escenas, programa comportamientos en C# y organiza proyectos mediante Prefabs y ScriptableObjects | Demuestra curiosidad, iniciativa y autonomía en la exploración de herramientas y tecnologías de desarrollo |
| Comprende los patrones de diseño de software aplicados a videojuegos (Singleton, Observer, State Machine, Command, Object Pooling) y los principios de diseño de mecánicas de gameplay | Implementa mecánicas de juego robustas, sistemas de inventario, interfaces de usuario, gestión de escenas y persistencia de datos | Valora la organización, la escritura de código limpio y la aplicación de buenas prácticas de ingeniería de software |
| Entiende los principios de simulación física, animación por estados, sistemas de partículas, audio espacial e iluminación en tiempo real | Integra físicas (Rigidbody, Colliders, Raycasting), animaciones (Animator, Blend Trees), efectos visuales, audio y post-procesado en prototipos funcionales | Muestra atención al detalle y sensibilidad estética en el pulido visual y sonoro de sus prototipos |
| Conoce los fundamentos de inteligencia artificial para juegos: agentes, percepción, navegación (NavMesh), máquinas de estados finitos, árboles de comportamiento y técnicas avanzadas (Utility AI, GOAP) | Programa NPCs con capacidad de patrullaje, detección, persecución y toma de decisiones autónoma en entornos de juego | Desarrolla pensamiento analítico y capacidad de abstracción para modelar comportamientos complejos |
| Comprende las arquitecturas de red cliente-servidor y peer-to-peer, los conceptos de sincronización, latencia, autoridad y los servicios de Unity para multijugador (Netcode, Relay, Lobby) | Implementa funcionalidad multijugador con sincronización de estado, RPCs, lobby/matchmaking y prepara builds optimizados para publicación multiplataforma | Fomenta el trabajo colaborativo, la responsabilidad en entregas incrementales y la capacidad de comunicar resultados técnicos de forma clara |

---

## VI. Contenidos Temáticos de la Asignatura

### Unidad 1 — Fundamentos de Unity y Programación en C#

- 1.1 Introducción al desarrollo de videojuegos: historia, géneros, pipeline de producción y roles en un equipo de desarrollo
- 1.2 Instalación y configuración de Unity: interfaz del editor, escenas, GameObjects, componentes y el patrón Entity-Component
- 1.3 Programación en C# para Unity: MonoBehaviour, ciclo de vida (Awake, Start, Update, FixedUpdate), Coroutines y eventos
- 1.4 Sistema de entrada (Input System): captura de teclado, mouse y gamepad; Input Actions y mapeos
- 1.5 Transformaciones, cámaras y sistemas de coordenadas: movimiento, rotación, escala; Cinemachine para cámaras dinámicas
- 1.6 Prefabs, ScriptableObjects y gestión de assets: organización del proyecto, Asset Store y paquetes

### Unidad 2 — Mecánicas de Juego y Sistemas de Gameplay

- 2.1 Diseño de mecánicas: game loops, estado de juego, condiciones de victoria/derrota y feedback al jugador
- 2.2 Patrones de diseño para juegos: Singleton, Observer, State Machine, Command y Object Pooling
- 2.3 Sistemas de inventario y economía: estructuras de datos, persistencia con JSON/PlayerPrefs y serialización
- 2.4 Interfaces de usuario (UI Toolkit / uGUI): menús, HUD, barras de vida, diálogos y localización básica
- 2.5 Gestión de escenas y flujo de juego: carga aditiva, pantallas de carga, transiciones y persistencia entre escenas
- 2.6 Prototipo 1: Juego 2D Top-Down (tipo RPG o Shooter) — integración de mecánicas, UI y gestión de escenas

### Unidad 3 — Físicas, Animación y Audio

- 3.1 Sistema de físicas de Unity: Rigidbody, Colliders, triggers, capas de colisión, joints y Raycasting
- 3.2 Animación: Animator Controller, estados, transiciones, Blend Trees, Animation Events e IK básico
- 3.3 Sistema de partículas (VFX Graph / Particle System): efectos visuales para impactos, explosiones, clima
- 3.4 Audio: AudioSource, AudioMixer, música adaptativa, efectos de sonido espacial (3D sound) y diseño sonoro básico
- 3.5 Iluminación y post-procesado: lightmapping, URP/HDRP básico, Volume profiles y shaders introductorios
- 3.6 Prototipo 2: Plataformero 2D/3D — físicas, animaciones, VFX, audio y polish visual

### Unidad 4 — Inteligencia Artificial para Videojuegos

- 4.1 Fundamentos de IA para juegos: agentes, percepción del entorno, toma de decisiones y arquitecturas comunes
- 4.2 Máquinas de estados finitos (FSM) y árboles de comportamiento (Behavior Trees) para NPCs
- 4.3 Navegación y pathfinding: NavMesh, NavMeshAgent, obstáculos dinámicos y A* conceptual
- 4.4 Sistemas de detección: línea de visión, conos de detección, FOV, estados de alerta y patrullaje
- 4.5 IA avanzada: Utility AI, GOAP (Goal-Oriented Action Planning) y steering behaviors para movimiento autónomo
- 4.6 Prototipo 3: Juego Stealth/Acción con NPCs inteligentes — patrullaje, detección, persecución y combate

### Unidad 5 — Networking, Multijugador y Publicación

- 5.1 Fundamentos de networking: arquitecturas cliente-servidor y peer-to-peer, conceptos de latencia, sincronización y autoridad
- 5.2 Unity Netcode for GameObjects: NetworkManager, NetworkObject, NetworkVariable, RPCs (ServerRpc/ClientRpc)
- 5.3 Sincronización de estado: NetworkTransform, interpolación, predicción del lado del cliente y reconciliación
- 5.4 Lobby, matchmaking y servicios de Unity (Relay, Lobby): conexión de jugadores sin servidor dedicado
- 5.5 Optimización, profiling y build: Profiler, batching, LOD, compresión de assets y configuración de builds multiplataforma
- 5.6 Prototipo 4: Juego Multijugador (Co-op o Competitivo) — networking, lobby, sincronización y deploy

---

## VII. Métodos y Estrategias de Enseñanza-Aprendizaje

Se utilizan métodos y estrategias de enseñanza y aprendizaje de acuerdo con el avance de la ciencia y la tecnología educativa:

- Explicativo ilustrativo
- Aprendizaje participativo
- Método problémico
- Método expositivo
- Simulación de casos
- Método investigativo
- Lluvia de ideas
- Aprendizaje por Proyectos

### Recursos

**Aula:**
- Computadora
- Data display
- Pizarra
- Guías de laboratorio
- Internet
- Plataforma de aprendizaje en línea, oficial de la UATF
- Herramienta de comunicación virtual sincrónica (Zoom, Meet, Webex u otro)

**Laboratorio:**
- Motor de desarrollo de videojuegos Unity

---

## VIII. Sistema de Evaluación

Las asignaturas de laboratorio se evalúan de la siguiente manera:

| Componente | Porcentaje |
|---|---|
| Exámenes Parciales | 30% |
| Prácticas | 10% |
| Laboratorio | 30% |
| Examen Final | 30% |
| **Total** | **100%** |

### Tipos de Evaluación

| Tipo | Técnica | Instrumento | Evidencia | Entorno |
|---|---|---|---|---|
| Diagnóstica | Interrogatorio (presencial y/o virtual) | Guía de observación | Cuestionario resuelto | Aula (presencial y/o virtual) |
| Formativa | Desempeño (presencial y/o virtual) | Prueba de laboratorio | Presentación, exposición | Aula (presencial y/o virtual) |
| Sumativa / Producto | Enunciado, ejercicios (presencial y/o virtual) | Prueba de laboratorio | Presentación de trabajo final | Aula (presencial y/o virtual) |

---

## IX. Bibliografía

- Hocking, J. (2022). *Unity in Action: Multiplatform Game Development in C#* (3a ed.). Manning Publications.
- Borromeo, N. A. & Gomila Salas, J. G. (2024). *Hands-On Unity Game Development: Unlock the Power of Unity 2023 and Build Your Dream Game* (4a ed.). Packt Publishing.
- Ferrone, H. (2024). *Learning Design Patterns with Unity: Learn the Secret of Popular Design Patterns While Building Fun, Efficient Games in Unity 2023*. Packt Publishing.
- Millington, I. (2019). *AI for Games* (3a ed.). CRC Press.
- Nystrom, R. (2014). *Game Programming Patterns*. Genever Benning.
- Gibson Bond, J. (2022). *Introduction to Game Design, Prototyping, and Development: From Concept to Playable Game with Unity and C#* (3a ed.). Addison-Wesley.
- Baron, D. (2021). *Game Development Patterns with Unity 2021: Explore Practical Game Development Using Software Design Patterns* (2a ed.). Packt Publishing.
- Unity Technologies. (2025). *Unity Manual & Scripting API*. https://docs.unity3d.com
- Unity Technologies. (2025). *Unity Learn: Tutoriales y rutas de aprendizaje*. https://learn.unity.com
- Microsoft. (2025). *Documentación de C# y .NET*. https://learn.microsoft.com/es-es/dotnet/csharp/

---

## X. Cronograma

*(Ver documento oficial de la asignatura para el cronograma detallado por semana.)*
