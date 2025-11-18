# 📚 RESUMEN SEMANA 5 - Módulo 1, Temas 3-4-5

**Periodo**: 8-12 Diciembre 2025
**Material**: Secciones 6-7 (páginas 151-210)
**Temas**: Procesamiento del Lenguaje Natural, Robótica y Sistemas Expertos

---

## TEMA 3: PROCESAMIENTO DEL LENGUAJE NATURAL (PLN)

### 3.1 Evolución del PLN

**Desarrollo Histórico**:
- Modelos tradicionales: Support Vector Machines (SVM) con vectores de alta dimensionalidad y entradas escasas
- Actualidad: Modelos de Deep Learning con entradas densas

### 3.2 Word Embedding

**Concepto Fundamental**:
> El word embedding transforma símbolos en objetos matemáticos sobre los que es fácil realizar operaciones

**Características**:
- Asigna símbolos discretos a vectores continuos en un espacio dimensional relativamente bajo
- Equipara la distancia entre vectores a la distancia entre palabras
- Facilita la generalización del comportamiento de una palabra sobre otra
- La red aprende estos vectores como parte del proceso de entrenamiento

**Ventaja Principal**:
- Permite predecir cómo se unen las palabras (aprendizaje combinatorio de vectores)
- Reduce sustancialmente los problemas de dispersión de datos

### 3.3 Arquitecturas de Redes Neuronales para PLN

**1. Redes Neuronales Prealimentadas (Feed-forward)**:
- Arquitectura simple de procesamiento directo

**2. Redes Neuronales Recurrentes (RNN)**:
- Configuración especial para procesar secuencias
- **Características clave**:
  - Entran secuencias que: a) devuelven algo y b) utilizan información anterior
  - Utilizan TODO el contexto de la frase (no solo la palabra anterior)
  - Pueden considerar: resto de la frase, frase anterior, documento entero
  - Ideales para entender sentidos de frases, contenido tóxico, etc.

### 3.4 Aplicaciones del PLN

**Traducción Automática**:
- Codificación y decodificación entre idiomas
- Ejemplo: Francés → Inglés usando encoder-decoder
- Clasificación de palabras y reorganización en idioma objetivo

**Generación de Texto**:
- Teclado predictivo (corrección y predicción de palabras)
- Combinación con CNN y GAN:
  - Escritura de poemas a partir de imágenes
  - Imitación de estilos literarios
  - Descripción automática de imágenes

**Datasets Utilizados**:
- Wikipedia corpus
- Comentarios tóxicos
- Tweets
- Libros específicos

---

## TEMA 4: ANÁLISIS DE SISTEMAS ROBOTIZADOS

### 4.1 Definiciones Fundamentales

**Robótica**:
> Ciencia que se ocupa del estudio, desarrollo y aplicaciones de los robots. Aglutina varias disciplinas tecnológicas y científicas para diseñar máquinas capaces de realizar tareas automatizadas.

**Robot**:
> Entidad autómata o máquina automática compuesta por un sistema electromagnético y mecánica artificial

**Clasificación según Russell & Norvig**:
- Los robots pertenecen a los **sistemas que actúan como humanos**
- Realizan labores de manera similar a como lo harían los humanos

### 4.2 Componentes de un Robot

**Sistema Mecánico**:
- Estructura de piezas rígidas unidas por articulaciones
- Actuadores: neumáticos, hidráulicos o eléctricos

**Sistema de Control**:
- Sistemas electrónicos complejos
- Ordenador para introducir y almacenar programas
- Describe acciones de cada elemento

**Sensores**:
- Proximidad, temperatura, presión, posición
- Iluminación, sonido, velocidad
- Microinterruptores, magnéticos
- Informan sobre condiciones del entorno

### 4.3 Ventajas de los Robots

- Reduce costes de producción
- Aumenta la producción
- Mejora la calidad del producto
- Evita trabajo en zonas de alto riesgo
- Funcionamiento 24/7 sin descanso
- No requiere vacaciones ni bajas laborales
- Actualmente no hay impuestos añadidos

### 4.4 Desventajas de los Robots

- Destrucción de empleo en sectores automatizables
- Requiere inversiones iniciales elevadas
- Necesita mantenimiento preventivo y correctivo
- Requiere planes de reconversión y formación para trabajadores desplazados

### 4.5 Historia de la Robótica

**Hitos Principales**:
- **Antigua Grecia**: Herón de Alejandría (85 a.C.) - Primeros autómatas
- **1920**: Karel Čapek acuña el término "robot" (de "Robbota" = trabajo forzado)
- **1956**: Isaac Asimov define "robótica" como ciencia
- **1956**: Unimate - Primer robot industrial
- **1997**: Sojourner en Marte
- **2020**: Mars 2020 mission

### 4.6 Clasificación de Robots por Aplicación

**Robots Científico-Sanitarios**:
- **Ciencia**: Exploración de entornos difíciles (océanos, volcanes, espacio)
  - ROV (Vehículos Operados a Distancia)
  - Rovers espaciales (Curiosity, Spirit, Opportunity)
- **Medicina**:
  - Cirugía robótica (Da Vinci)
  - Prótesis biónicas (LUKE arm con tacto en dedos)
  - Exoesqueletos para rehabilitación
  - Nanorobótica para medicina e investigación

**Robots Industriales/Agrícolas**:
- **Industrial**:
  - Robots fijos (no colaborativos): grandes dimensiones, cargas pesadas
  - Cobots (colaborativos): trabajan con humanos, sensores de seguridad
  - Robots móviles autónomos
- **Agrícola**:
  - Control de cultivos (Vinerobot, Vinbot)
  - Robots de invernadero (Fitorobot)
  - Drones para agricultura de precisión

**Robots de Servicios**:
- **Mensajería y logística**: Kiwibot
- **Hostelería/Hogar**: Robot mayordomo Carl, Roomba
- **Social y compañía**: Loro (asistente para discapacidad)
- **Robots humanoides**: Sophia (Hanson Robotics), Ibuki, Thespian, Atlas

**Robots Militares y Exploradores**:
- **Militares**: Goliath, Predator, Samsung SGR-A14
- **Exploradores**: Afghan eXplorer, desactivación de explosivos

**Robots Educativos**:
- Metodología STEM
- Kits: Lego Robotix, Bee-Bot, Lego Wedo, Lego Mindstorms
- Lenguajes: Arduino, Scratch

### 4.7 Modelado y Control de Robots en IA

**Diferencia entre Robótica Clásica y con IA**:
- **Clásica**: Comportamientos deterministas (misma entrada = misma salida)
- **Con IA**: Capacidad de tomar decisiones y aprender de la experiencia

**Entorno (Environment)**:
- **Estructurado**: Todo organizado, ubicaciones conocidas (línea de montaje)
- **No estructurado**: Variables, el robot debe adaptarse

**Control en Tiempo Real**:
- **Lazo Abierto**: Sin retroalimentación (ejemplo: túnel de lavado)
- **Lazo Cerrado (PID)**: Con retroalimentación (Proporcional-Integral-Derivado)
- **Lazo OODA**: Observe-Orient-Decide-Act (para IA en robots)

**Componentes del Sistema de Control**:
- **Sensores**: Internos y externos
- **Controlador**: Microcontrolador o microprocesador
- **Actuador**: Ejecuta el proceso

**Tiempo Real**:
- **Duro**: Hardware impone restricciones, recursos garantizados
- **Suave**: Software usa frames (intervalos de tiempo fijos)

### 4.8 Lazo OODA (Observe-Orient-Decide-Act)

**Origen**: Coronel John Boyd (Fuerza Aérea EEUU)

**Proceso**:
1. **Observe**: Recoger datos del entorno usando sensores
2. **Orient**: Poner datos en marco de referencia común
3. **Decide**: Analizar alternativas y seleccionar acción
4. **Act**: Ejecutar acción enviando comandos a motores

**Ventaja**:
- Permite que robots establezcan objetivos y trabajen para lograrlos
- No solo ejecutan comandos, sino que tienen libertad para determinar cómo alcanzar objetivos

### 4.9 Framework ROS (Robot Operating System)

**Características**:
- Código adaptable a cualquier robot (abstracción de hardware)
- Trabajo en múltiples máquinas simultáneamente
- Código abierto y gratuito
- Integrable con muchas librerías de terceros

**Conceptos Clave de ROS**:

**Node (Nodo)**:
- Proceso encargado de realizar tareas y cálculos
- Se combinan usando topics o servicios

**Topic (Tema)**:
- Canal de información unidireccional entre nodos
- Los nodos pueden suscribirse pero el topic no sabe quién está suscrito

**Master**:
- Servicio de nombre y registro para nodos
- Habilita comunicación entre pares

**Service (Servicio)**:
- Método solicitud-respuesta (diferente a topics)
- Un nodo proveedor ejecuta rutina y envía resultado al cliente

**Message (Mensaje)**:
- Estructura de datos para intercambio entre nodos

**Package (Paquete)**:
- Núcleo de organización ROS
- Contiene nodos, librerías, datos, componentes

**Stack (Pila)**:
- Conjunto de nodos que proporcionan funcionalidad compleja

**Bags (Bolsas)**:
- Utilidad para grabar y reproducir topics ROS

---

## TEMA 5: SISTEMAS EXPERTOS Y AGENTES INTELIGENTES

### 5.1 Definición de Agente Inteligente

**Concepto**:
> Un agente es un ente que recibe información del entorno y actúa en consecuencia. Se espera que actúe de forma inteligente.

**Actuación Inteligente**:
- Orientada a maximización de un objetivo
- Usa toda la información disponible
- Ejemplo: escapar de un depredador para sobrevivir

**Función del Agente**:
```
f: P* --> A
P*: conjunto de percepciones finito
A: acción en función de percepciones
```

### 5.2 Entorno de Trabajo (REAS)

**Componentes**:
- **R**endimiento: Indicadores de éxito
- **E**ntorno: Lugar donde trabaja el robot
- **A**ctuadores/Acciones: Posibles acciones
- **S**ensores: Dispositivos de entrada

**Ejemplo - Coche Autónomo**:
- Rendimiento: km recorridos, infracciones, accidentes, comodidad
- Entorno: calles, señales, vehículos, peatones
- Acciones: arrancar, parar, frenar, acelerar, girar
- Sensores: velocímetros, GPS, cámaras

### 5.3 Propiedades de Entornos de Trabajo

**Observable**:
- **Totalmente**: Sensores dan toda la información relevante
- **Parcialmente**: Información incompleta (ruido, sensores inexactos)

**Determinismo**:
- **Determinista**: Estado siguiente totalmente determinado
- **Estocástico**: Incertidumbre en el resultado

**Temporalidad**:
- **Secuencial**: Acciones de corto plazo afectan largo plazo (ajedrez)
- **Episódico**: Acciones independientes entre episodios

**Dinamismo**:
- **Estático**: Entorno no cambia mientras agente decide
- **Dinámico**: Entorno cambia durante decisión (tráfico)

**Valores**:
- **Discreto**: Número finito de estados (aunque muy alto)
- **Continuo**: Rango continuo de valores (velocidad, posición)

**Agentes**:
- **Individual**: Un solo agente trabaja
- **Multiagente**: Múltiples agentes interactúan

### 5.4 Tipos de Agentes Inteligentes

**1. Agentes Reactivos Simples**:
- Reaccionan ante estímulo según reglas predefinidas
- Descartan información histórica
- Limitados a entornos totalmente observables
- Ejemplo: Robot aspirador succiona al detectar suciedad

**2. Agentes Reactivos Basados en Modelos**:
- Incorporan histórico de información
- Tienen estado interno
- Representan conocimiento mediante modelo formal
- Ejemplo: Videojuego con estado "protegido"

**3. Agentes Basados en Objetivos**:
- Establecen objetivo a conseguir
- Más flexibles que reglas fijas
- Requieren búsqueda y planificación
- Ejemplo: Llegar a destino con GPS

**4. Agentes Basados en Utilidad**:
- Incorporan función de utilidad
- Miden satisfacción con la solución
- Función matemática a maximizar/minimizar
- Ejemplos: minimizar distancia, tiempo, coste
- Permiten decisiones racionales con algoritmos de propósito general

**5. Agentes que Aprenden**:

**Componentes**:
- **Elemento de actuación**: Selecciona acciones según estímulos
- **Crítica**: Evalúa la actividad del agente (retroalimentación)
- **Elemento de aprendizaje**: Desarrolla mejoras
- **Generador de problemas**: Sugiere acciones exploratorias

**Proceso**:
1. Actuación genera críticas (evaluaciones)
2. Retroalimentación alimenta aprendizaje
3. Cambios se comparten con elemento de actuación
4. Experimentos exploran soluciones mejores a largo plazo

**Implementación**:
- Aprendizaje por refuerzo

**Ejemplo - Taxi Autónomo**:
- Elemento de actuación: Conocimientos para seleccionar acciones
- Crítica: Observación del entorno (cambio de carril, reacciones)
- Aprendizaje: Evolución del comportamiento
- Generador: Pruebas de nuevas estrategias

---

## 🎯 CONCEPTOS CLAVE PARA MEMORIZAR

### Procesamiento del Lenguaje Natural:
- **Word Embedding**: Transformación de símbolos a vectores matemáticos
- **RNN**: Redes que procesan secuencias considerando TODO el contexto
- **Aplicaciones**: Traducción, generación de texto, análisis de sentimientos

### Robótica:
- **Robot**: Máquina automática con sistema electromagnético y mecánica artificial
- **Componentes**: Sistema mecánico + Sistema de control + Sensores
- **Tipos**: Científicos, industriales, servicios, militares, educativos
- **ROS**: Framework estándar para programación de robots

### Control y IA en Robótica:
- **Lazo OODA**: Observe-Orient-Decide-Act
- **Diferencia clave**: IA permite tomar decisiones y aprender (vs. determinista)
- **Entornos**: Estructurado vs. No estructurado
- **Tiempo Real**: Duro (hardware) vs. Suave (software/frames)

### Agentes Inteligentes:
- **Definición**: Función que convierte percepciones en acciones (f: P* → A)
- **REAS**: Rendimiento, Entorno, Actuadores/Acciones, Sensores
- **5 Tipos**: Reactivos simples, Basados en modelos, Basados en objetivos, Basados en utilidad, Que aprenden
- **Entorno más complejo**: Parcialmente observable, estocástico, secuencial, dinámico, continuo, multiagente

---

## 💡 CONSEJOS DE ESTUDIO

1. **Diferencia PLN clásico vs. moderno**: Entiende la evolución de SVM a Deep Learning
2. **Visualiza las RNN**: Comprende cómo procesan secuencias y contexto
3. **Clasifica robots**: Identifica aplicaciones y características de cada tipo
4. **Domina ROS**: Conoce sus conceptos fundamentales (nodos, topics, servicios)
5. **Progresión de agentes**: Entiende la complejidad creciente de los 5 tipos
6. **Propiedades de entornos**: Practica clasificando diferentes escenarios
7. **Lazo OODA**: Comprende cada fase y su aplicación práctica

---

_Resumen creado para Semana 5 - Diciembre 2025_
