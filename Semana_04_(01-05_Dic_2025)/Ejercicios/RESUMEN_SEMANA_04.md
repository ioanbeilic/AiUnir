# RESUMEN SEMANA 4 - Módulo 1, Temas 3-4

**Periodo**: 1-5 Diciembre 2025
**Material**: Secciones 5-6 (páginas 121-180)
**Temas**: Procesamiento del Lenguaje Natural y Análisis de Sistemas Robotizados

---

## TEMA 3: PROCESAMIENTO DEL LENGUAJE NATURAL (PLN)

### 3.1 Tipos de Conocimiento del Lenguaje para PLN

Para realizar tareas complejas de PLN se necesitan diferentes tipos de conocimiento:

**Fonética y Fonología**:
- Conocimiento de los sonidos del lenguaje
- Necesario para el procesamiento de voz

**Morfología**:
- Estructura y formación de palabras
- Análisis de raíces, prefijos y sufijos

**Sintaxis**:
- Estructura gramatical de las frases
- Análisis de las relaciones entre palabras

**Semántica**:
- Significado de palabras y frases
- Interpretación del contenido

**Pragmática**:
- Relación del significado con objetivos e intenciones
- Determina el tipo de expresión (pregunta, solicitud, declaración)
- Adapta el nivel de formalidad según el contexto

**Discurso**:
- Unidades lingüísticas más grandes que un enunciado
- Resolución de referencias cruzadas
- Coherencia entre partes de la conversación

### 3.2 Pipeline de PLN

El procesamiento del lenguaje natural sigue una secuencia de análisis:

1. **Análisis Fonético/Fonológico** (para voz) o **OCR/Tokenización** (para texto)
2. **Análisis Morfológico y Léxico**
3. **Análisis Sintáctico**
4. **Interpretación Semántica**
5. **Procesamiento del Discurso**

### 3.3 Lingüística Computacional

**Definición**: Disciplina que estudia la lengua y desarrolla aplicaciones lingüísticas con medios computacionales.

**El Experto en PLN**:
- Conoce modelos lingüísticos en profundidad
- Domina modelos lógicos (patrones estructurales)
- Maneja modelos probabilísticos (basados en datos)
- Tiene nociones de programación
- Conoce estadística y varios idiomas (inglés como base)

**Capacidades Necesarias**:
- Conocimientos lingüísticos (morfología, sintaxis, semántica)
- Programación (Python, Java, R)
- Estadística
- Familiaridad con frameworks de ML y Deep Learning

### 3.4 Aplicaciones del PLN

**1. Reconocimiento de Patrones de Lenguaje**:
- Filtra datos importantes en cadenas de texto
- Base para recuperación y clasificación

**2. Recuperación de Información (RI)**:
- Encuentra fragmentos específicos en grandes cantidades de texto
- No inventa contenido, identifica información valiosa

**3. Traducciones Automáticas**:
- Procesamiento por lingüística computacional
- Mejora constante con Deep Learning
- Ejemplos: Google Translate (100+ idiomas), DeepL

**4. Clasificación de Información**:
- Categorización mediante palabras clave
- Consulta más eficiente

**5. Resumen de Textos**:
- Basado en palabras/frases clave
- Detección de spam

**6. Generación de Lenguaje Natural (GLN/NLG)**:
- Máquinas responden con frases nuevas
- Más avanzado que chatbots simples

**7. Comprensión del Lenguaje Natural (CLN/NLU)**:
- Análisis de emociones y sentimientos
- Identificación de intencionalidad
- Aplicaciones en marketing y redes sociales

### 3.5 Sistemas de PLN Específicos

**Agentes Conversacionales**:
- Sistemas de diálogo que toman turnos
- Mantienen estado de conversación
- Ejemplos: Siri (20 idiomas), Alexa, Google Assistant
- **Chatbots avanzados**: Conversaciones no estructuradas con aprendizaje
- Casos de uso:
  - WHO Health Alert (información COVID-19)
  - Erica de Bank of America (14+ millones de usuarios)
  - Dom de Domino's (pedidos con humor)
  - Juliet de WestJet (atención al cliente aérea)
  - DoNotPay (primer robot abogado)
  - AskBenji (ayuda con becas federales)
  - Andy (enseñanza de idiomas)

**Traducción Automática**:
- Métodos estadísticos basados en frases
- Algoritmos de desambiguación
- Google Translate: 100+ idiomas
- DeepL: diferentes grados de formalidad
- Reconocimiento de voz + Síntesis de voz

**Recuperación de Información (RI)**:
- Método TF-IDF:
  - **TF**: Frecuencia de término en documento
  - **IDF**: Relevancia del término en el corpus
- Genera listas de palabras clave con peso/calificación
- Problema: textos largos tienen mayor peso
- Solución: Normalización (coseno, pivote, máximo TF)

**Extracción de Información (EI)**:
- Selecciona estructuras y combina datos
- Extrae hechos esenciales de textos
- Llena plantillas predefinidas
- Estructura texto no estructurado
- Resultados pueden ir a bases de datos

**Modelado de Temas (Topic Modeling)**:
- Da sentido a información no estructurada
- Aplicaciones:
  - Automatizar enrutamiento de comentarios
  - Categorizar contenido en redes sociales
  - Responder elementos críticos
  - Enriquecer sistemas de gestión del conocimiento
  - Seguimiento de marca

**Detección de Spam**:
- Uso de palabras clave
- Clasificación de mensajes no deseados
- Análisis de seguridad

**Autocorrección de Texto**:
- Diccionario integrado multiidioma
- Identifica errores ortográficos y gramaticales
- Detección de frases hechas
- Personalizable (agrega/elimina palabras)

### 3.6 Recursos y Componentes de PLN

**Corpus Lingüísticos**:
- Recopilación de textos del campo a analizar
- Características: variados, representativos, equilibrados, tamaño adecuado

**Tokenizadores**:
- Segmentadores de palabras
- Separan texto en unidades con sentido semántico
- Dificultades: fronteras ambiguas, formatos, abreviaturas

**N-gramas**:
- Agrupaciones de n tokens
- Unigramas, Bigramas, Trigramas
- Detectan estructuras repetitivas

**Etiquetadores de Partes de Oraciones**:
- Clasifican palabras morfológicamente
- Identifican verbos, adjetivos, preposiciones

**Lematizadores**:
- Asignan raíz léxica del diccionario
- Simplifican análisis semántico

**Supresión de Palabras Funcionales**:
- Eliminan palabras sin léxico
- Crean esquemas de significado

### 3.7 Entornos y Herramientas de PLN

**Plataformas Cloud**:
- Microsoft Azure Cognitive Services - LUIS
- AWS Amazon Comprehend
- Google Cloud Platform - Natural Language AI
- IBM Watson IA

**APIs y Herramientas**:
- **Aylien**: Análisis de contenido de noticias
- **NLTK**: Biblioteca Python más popular, modular
- **MonkeyLearn**: PLN simplificado con modelos pre-entrenados
- **Stanford Core NLP**: Potente y rápido, en Java
- **TextBlob**: Interfaz intuitiva sobre NLTK
- **SpaCy**: Biblioteca ultrarrápida para tareas avanzadas
- **GenSim**: Especializada en modelado de temas (LDA)

**Frameworks Open Source**:
- Apache OpenNLP
- AllenNLP
- Intel NLP Architect
- Flair

### 3.8 Deep Learning para PLN

**Word Embedding**:
- Transforma símbolos en vectores matemáticos
- Asigna símbolos discretos a vectores continuos
- La distancia entre vectores = distancia entre palabras
- Facilita generalización de comportamiento

**Arquitecturas de Redes Neuronales**:

1. **Redes Neuronales Prealimentadas (Feed-forward)**:
   - Procesamiento directo de entrada a salida

2. **Redes Neuronales Recurrentes (RNN)**:
   - Procesan secuencias
   - Utilizan contexto previo (palabra, frase, documento)
   - Mantienen memoria de conversación
   - Aplicaciones: traducción, clasificación, generación de texto

**Combinaciones Avanzadas**:
- **CNN + RNN**: Descripción de imágenes con texto
- **GAN + RNN**: Generación de poemas desde imágenes
- Aplicaciones en teclados predictivos y generación literaria

---

## TEMA 4: ANÁLISIS DE SISTEMAS ROBOTIZADOS

### 4.1 Conceptos Básicos

**Robótica**: Ciencia que trabaja sobre la capacidad de ejecutar tareas de manera similar a como lo harían los humanos.

**Robot**: Entidad autómata o máquina automática compuesta por:
- Sistema electromagnético
- Mecánica artificial
- Capaz de realizar tareas físicas e intelectuales

### 4.2 Historia de la Robótica

**Hitos Importantes**:
- **85 a.C.**: Herón de Alejandría - Primeros autómatas
- **1495**: Leonardo da Vinci - Diseño de robot humanoide
- **1912**: Torres Quevedo - Primera máquina de ajedrez
- **1920**: Karel Čapek - Acuña el término "robot" (de "robbota" = trabajo forzado)
- **1942**: Isaac Asimov - Tres Leyes de la Robótica
- **1948**: George Charles Davol - Primer robot industrial
- **1953**: Tortuga de Walter - Robot con sensores
- **1956**: Unimate - Primer robot industrial
- **1969**: Shakey - Primer robot móvil con visión e IA
- **1971-1977**: Robots soviéticos y americanos en Marte
- **Actualidad**: Robots humanoides con IA avanzada

**Tres Leyes de la Robótica (Asimov)**:
1. Un robot no puede dañar a un ser humano ni permitir que sufra daño
2. Debe obedecer órdenes humanas (excepto si contradicen la 1ª ley)
3. Debe proteger su propia existencia (si no contradice las leyes 1ª y 2ª)

### 4.3 Ventajas y Desventajas de los Robots

**Ventajas**:
- Reduce costes de producción
- Aumenta la producción
- Mejora calidad del producto
- Evita riesgos para humanos
- Trabajo 24/7 sin descanso ni fatiga
- No requiere vacaciones ni bajas laborales
- Sin impuestos adicionales (de momento)

**Desventajas**:
- Destrucción de empleo en sectores automatizables
- Requiere inversiones iniciales elevadas
- Necesita mantenimiento preventivo y correctivo
- Requiere reconversión de trabajadores desplazados

### 4.4 Clasificación de Robots por Aplicación

**1. Robots Científico-Sanitarios**:

**Ciencia**:
- Exploración de entornos difíciles (océanos, volcanes, espacio)
- ROV (vehículos operados a distancia)
- Investigación en condiciones extremas

**Medicina**:
- Cirugía robótica: Sistema Da Vinci (menos invasivo, recuperación rápida)
- Prótesis biónicas: LUKE (brazo con 10 articulaciones motorizadas, tacto)
- Exoesquelética: Rehabilitación de lesiones medulares
- Nanorobótica: Nanobots para medicina, purificación de agua

**Espacio**:
- Robots exploradores: Sojourner (1997), Spirit, Opportunity, Curiosity
- Misiones científicas en Marte y Luna
- Reactor nuclear para energía prolongada
- Inversión: de 2.88 billones (2018) a 4.36 millones estimados (2023)

**2. Robots Industriales/Agrícolas**:

**Industriales**:
- Brazos articulados (hasta 6 ejes)
- **Robots fijos**: Grandes, robustos, cargas pesadas (sector automoción)
- **Cobots** (robots colaborativos):
  - Trabajan con humanos
  - Sensores de seguridad
  - Pequeños y fáciles de programar
  - Accesibles para PYMEs
- Robots móviles autónomos (AMR)

**Agrícolas y Ganaderos**:
- Robots de invernadero (Fitorobot)
- Control de cultivos: Vinerobot, Vinbot (viñas)
- Drones aéreos para:
  - Control de riego
  - Detección de plagas
  - Optimización de recolección
- Aplicación de antiplagas mediante visión artificial

**3. Robots de Servicios**:

**Definición IFR**: Robot que realiza tareas útiles para personas o equipos, excluyendo automatización industrial.

**Mensajería y Logística**:
- Robots móviles terrestres
- Kiwibot: Entrega de comida en universidades (California)
- Respuesta a masificación de pedidos online

**Hostelería/Hogar**:
- Robots aspiradores: Roomba (iRobot)
- Robots mayordomo: Carl (automatización y vigilancia)
- Robots de cocina y limpieza

**Social y Compañía**:
- Ayuda a personas mayores o con discapacidad
- Recordatorios de medicación
- Asistencia física
- **Loro**: Robot para sillas de ruedas
  - Control por movimiento de ojos
  - Entiende gestos
  - Comunicación voz-texto
  - Conexión con dispositivos del hogar

**Robots Sociales Avanzados**:
- **Sophia** (Hanson Robotics): Piel Frubber (nanotecnología hiperrealista)
- **Ibuki**: Alta capacidad de interacción
- **Thespian**: Androide avanzado
- **Atlas** (Boston Dynamics): Robot humanoide

**4. Robots Militares y de Exploración**:

**Militares**:
- Autónomos o teleoperados
- Aplicaciones: transporte, búsqueda y rescate, ataque, defensa
- Ejemplos históricos: Goliath (WWII), Predator (drones)
- **Prohibición**: Armas totalmente autónomas (Convención de Ginebra)
- Vehículos de desactivación de explosivos
- Robots de vigilancia fronteriza: Samsung SGR-A14 (Corea del Sur)
- Limitación: Dificultad para condiciones no estándar

**Exploradores**:
- Movimiento autónomo o control remoto
- Evitan riesgo humano en zonas peligrosas
- Labores de rescate y desactivación
- **Afghan eXplorer** (MIT): Robot reportero en conflictos

**5. Robots Educativos**:

**Robótica Educativa**:
- Método multidisciplinario STEM
- Diseño y construcción de robots
- Desarrollo de habilidades:
  - Creatividad
  - Trabajo en equipo
  - Liderazgo
  - Resolución de problemas
  - Espíritu competitivo y emprendedor

**Herramientas**:
- Lenguajes: Arduino, Scratch
- Kits: Lego Robotics, Fischer Price, Clementoni, MakeBlock
- Niveles:
  - Infantil: Bee-Bot
  - Junior: Lego Wedo
  - Juvenil: Lego Mindstorms

### 4.5 Modelado y Control de Robots

**Componentes de un Robot**:

1. **Sistema Mecánico**:
   - Estructura de piezas rígidas
   - Articulaciones
   - Actuadores (neumáticos, hidráulicos, eléctricos)

2. **Sistema de Control**:
   - Sistemas electrónicos complejos
   - Ordenador con programa
   - Memoria de almacenamiento
   - Sensores (proximidad, temperatura, presión, posición, etc.)

**Teoría de Control**:
- Bucle de retroalimentación
- Control de movimiento según feedback
- Aplicaciones más allá de la robótica

**Programación de Robots**:
- Introducir instrucciones en sistema de control
- Describir tareas para cada elemento
- Adaptar funcionamiento a condiciones del entorno

---

## CONCEPTOS CLAVE PARA MEMORIZAR

### PLN:
- **6 tipos de conocimiento**: Fonética, Morfología, Sintaxis, Semántica, Pragmática, Discurso
- **Pipeline PLN**: Análisis Fonético/OCR → Morfológico → Sintáctico → Semántico → Discurso
- **TF-IDF**: Term Frequency - Inverse Document Frequency
- **RI vs EI**: Recuperación vs Extracción de Información
- **NLG vs NLU**: Generación vs Comprensión de Lenguaje Natural
- **RNN**: Redes para secuencias con memoria de contexto

### Robótica:
- **Definición robot**: Entidad autómata electromecánica programada
- **Tres Leyes de Asimov**: No dañar, obedecer (si no contradice 1ª), autoprotección
- **Tipos principales**: Científico-sanitarios, Industriales, Servicios, Militares, Educativos
- **Cobots**: Robots colaborativos seguros para trabajar con humanos
- **Componentes**: Sistema mecánico + Sistema de control + Sensores

### Aplicaciones Destacadas:
- **PLN**: Chatbots, traducción, análisis sentimientos, resumen textos
- **Robótica Médica**: Da Vinci (cirugía), LUKE (prótesis), nanobots
- **Robótica Espacial**: Curiosity, rovers de Marte
- **Robots Sociales**: Sophia, Loro, asistentes personales

---

## CONSEJOS DE ESTUDIO

1. **Distingue claramente** entre los diferentes tipos de conocimiento del lenguaje y sus aplicaciones
2. **Comprende el pipeline de PLN** y cómo cada etapa procesa la información
3. **Identifica las diferencias** entre herramientas de PLN (NLTK, SpaCy, etc.)
4. **Relaciona aplicaciones de robótica** con sus campos específicos
5. **Entiende la diferencia** entre robots fijos, colaborativos y móviles
6. **Conoce ejemplos concretos** de robots en cada categoría
7. **Memoriza las Tres Leyes de Asimov** y su importancia ética

---

_Resumen creado para Semana 4 - Diciembre 2025_
