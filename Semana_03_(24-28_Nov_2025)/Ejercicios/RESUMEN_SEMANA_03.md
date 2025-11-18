# 📚 RESUMEN SEMANA 3 - Módulo 1, Temas 2-3

**Periodo**: 24-28 Noviembre 2025
**Material**: Secciones 3-4 (páginas 61-120)
**Temas**: Utilización de Modelos de IA y Procesamiento del Lenguaje Natural

---

## TEMA 2: UTILIZACIÓN DE MODELOS DE INTELIGENCIA ARTIFICIAL

### 2.1 ¿Por qué es importante la IA?

**Tres clases principales de sistemas empresariales**:
- Sistemas informacionales
- Sistemas transaccionales
- Sistemas inteligentes (enfoque del máster)

**Aportes concretos de la IA**:

1. **Automatiza el aprendizaje por repetición**:
   - Realiza tareas frecuentes con alto volumen de datos
   - Totalmente fiable y sin fatiga
   - Llamada "automatización inteligente" (Intelligent Automation)

2. **Agrega inteligencia a productos existentes**:
   - Mejora productos ya desarrollados
   - Ejemplo: Siri en productos Apple
   - Se combina con Big Data

3. **Se adapta mediante algoritmos de aprendizaje progresivo**:
   - Los datos realizan la programación
   - El algoritmo se convierte en predictor o clasificador
   - Mismo algoritmo para funciones variadas

4. **Analiza datos complejos con redes neuronales profundas (Deep Learning)**:
   - Construye sistemas de detección de fraude
   - Necesita muchos datos para entrenar
   - IoT aporta datos donde faltan

5. **Es increíblemente precisa con Deep Learning**:
   - Ejemplo: detección de cáncer en resonancias magnéticas con precisión similar a radiólogos expertos

6. **Saca el mayor provecho de los datos**:
   - Los datos se vuelven propiedad intelectual
   - En un mundo "data driven", proporciona ventaja competitiva
   - Mejores datos = mejor posición

### 2.3 Modelos de Sistemas de IA

**Proceso de definición de problemas**:
1. Definir representación de estados
2. Determinar estado inicial
3. Determinar estado final/meta
4. Definir operadores/reglas de transición

**Objetivo**: Encontrar secuencia de reglas que lleven del estado inicial al estado meta.

**Criterios de eficiencia**:
- ¿Permite llegar a una solución?
- ¿Es una buena solución?
- Coste de búsqueda (tiempo y memoria)
- Coste total (búsqueda + camino)

### Automatización de Tareas

**Beneficios inmediatos**:
- Reducir costos generales
- Aumentar productividad
- Aumentar disponibilidad
- Mejorar precisión y fiabilidad
- Mejorar rendimiento en todos los departamentos
- Mejorar enfoque del problema

**Concepto de Hiperautomatización**: Trasladar tareas rutinarias de personas hacia sistemas automáticos.

**Las 4 Capacidades de la Automatización Inteligente** (según Bornet, Barkin y Wirtz):

#### 1. Capacidad de Visión
- Percepción, interpretación y comprensión del mundo visual
- **Tecnologías clave**:
  - OCR (Reconocimiento Óptico de Caracteres)
  - ICR (Reconocimiento Inteligente de Caracteres)
  - Análisis de imágenes y vídeos
  - Biometría avanzada
- **Aplicaciones**: Diagnóstico médico por imagen, identificación de delincuentes

#### 2. Capacidad de Ejecución
- "Hacer" tareas en entornos digitales
- Completar formularios, escribir texto, enrutar información
- **Tecnologías clave**:
  - Workflow inteligente
  - Plataformas Low Code
  - RPA (Robot Process Automation)
- **Función**: Une las otras tres capacidades

#### 3. Capacidad de Lenguaje
- Leer, hablar, escribir, interactuar con lenguaje humano
- **Aplicaciones**:
  - Traducción de texto
  - Extracción de información
  - Análisis de sentimientos
  - Voz a texto / texto a voz
  - Clasificación de información
- **Tecnología**: Procesamiento del Lenguaje Natural (PNL)

#### 4. Capacidad de Pensar y Aprender
- Relacionada con toma de decisiones
- Crea conocimiento mediante análisis y predicción
- **Tecnologías clave**:
  - Big Data
  - Machine Learning
  - Visualización de datos
- **Función**: Proporciona información para decisiones

### Sistemas Basados en Reglas

**Componentes**:
- **Base de conocimiento**: Datos (hechos) + Conocimiento (reglas)
- **Motor de inferencia**: Manipula componentes y extrae conclusiones

**Estructura de regla**: "Si premisa, entonces conclusión"

**Métodos de inferencia**:
- **Modus Ponens**: Encadenamiento hacia adelante (de hechos a conclusiones)
- **Modus Tollens**: Encadenamiento hacia atrás (de conclusión a hechos)

**Ventajas**:
1. Representación natural del conocimiento experto
2. Estructura uniforme (Si... entonces...)
3. Separación entre base de conocimiento y procesamiento
4. Capacidad para trabajar con incertidumbre

**Desventajas**:
1. Relaciones opacas entre reglas
2. Estrategias de búsqueda ineficientes
3. Incapaz de aprender sin aditivos

### 2.4 Sistemas de Razonamiento Impreciso

**Factores de Certeza (CF)**:
- Valor entre -1 y +1
- +1 = certeza total
- -1 = falsedad total
- 0 = desconocido

**Propagación con un antecedente**:
```
cf(H,E) = cf(E) · cf(regla)
```

**Propagación con múltiples antecedentes**:
- **AND**: Tomar el mínimo de los cf
- **OR**: Tomar el máximo de los cf

**Razonamiento Bayesiano**:

Teorema de Bayes:
```
P(H|E) = P(E|H) · P(H) / P(E)
```

**Naïve Bayes**:
- Clasificadores probabilísticos
- Suposición: atributos de entrada independientes entre sí respecto a la clase
- Buenos resultados con conjuntos de entrenamiento medio/grandes

### Lógica Difusa (Fuzzy Logic)

**Concepto**: Extiende lógica tradicional permitiendo "grado de pertenencia" a un conjunto (valores entre 0 y 1).

**Componentes**:
- **Conjunto difuso**: Distribución de posibilidades de pertenencia
- **Función de pertenencia (μ)**: Define grado de pertenencia (0 a 1)
- **Variable lingüística**: Variable cuyos valores son términos lingüísticos (bajo, medio, alto)

**Variables Lingüísticas** (X, T(X), U, G, M):
- X: nombre de la variable
- T(x): conjunto de valores lingüísticos
- U: universo de discurso (rango de valores)
- G: regla sintáctica para generar valores
- M: regla semántica (asocia términos con conjuntos difusos)

**Modificadores Lingüísticos**:
- "Muy": μ²(x) - Reduce grado de pertenencia
- "Más o menos": √μ(x) - Aumenta grado de pertenencia

**Reglas Difusas**:
```
SI x es a
ENTONCES y es b
```

**Ventajas**:
- Maneja imprecisión e incertidumbre
- Expresión mediante palabras de uso cotidiano
- Reduce cantidad de código
- Controla procesos gobernados por reglas intuitivas

**Aplicaciones**: Control de procesos, medicina, biología, economía, política

---

## TEMA 3: PROCESAMIENTO DEL LENGUAJE NATURAL (PLN)

### 3.1 ¿Qué contempla el PLN?

**Definición**: Campo interdisciplinario de la IA que tiene como objetivo que las máquinas realicen tareas que involucren el lenguaje humano.

**Campos involucrados**:
- Informática (análisis sintáctico, semántica)
- Ingeniería electrónica/telecomunicaciones (reconocimiento de voz)
- Lingüística computacional (morfología, fonología, pragmática)
- Psicología (mecanismos cognitivos)
- Sociología (influencia social en el lenguaje)

**Nombres alternativos**:
- Procesamiento del lenguaje y del habla
- Tecnología del lenguaje
- Lingüística computacional
- Reconocimiento y síntesis del habla

### 3.2 Historia del PLN

#### Paradigmas Fundacionales (1940-1950)

**1. Autómatas**:
- Origen: Trabajo de Turing (1936)
- Contribuciones:
  - Modelo simplificado de neurona (McCulloch y Pitts, 1943)
  - Autómatas finitos y expresiones regulares (Kleene, 1951)
  - Cadenas de Markov aplicadas al lenguaje (Shannon, 1948)
  - Gramáticas de estados finitos (Chomsky, 1956)
- **Resultado**: Teoría del lenguaje formal

**2. Teoría de la Información**:
- Shannon: Teorema de codificación de canal
- Concepto de entropía aplicado al lenguaje
- Primera medida de entropía del inglés
- 1952: Primer sistema de reconocimiento de voz (Bell Labs)
  - 97-99% precisión para 10 dígitos

#### Paradigma Simbólico y Estocástico (1957-1970)

**Paradigma Simbólico**:
- Línea 1: Teoría del lenguaje formal (Chomsky)
  - Gramáticas libres de contexto (1956)
  - Algoritmos de análisis (top-down, bottom-up)
  - TDAP: Primer sistema de análisis (1958-1959)

- Línea 2: Inteligencia Artificial
  - Simposio fundacional (1956): McCarthy, Minsky, Shannon, Rochester
  - Logic Theorist y General Problem Solver (Newell y Simon)
  - Primeros sistemas de comprensión del lenguaje natural
  - SHRDLU (Winograd, 1972): robot que mueve bloques

**Paradigma Estocástico**:
- Método bayesiano en reconocimiento óptico de caracteres
- Sistema de reconocimiento de texto (Bledsoe y Browning)
- **Brown Corpus** (1963): primer corpus online
  - 1 millón de palabras
  - 500 textos de diferentes géneros

#### Cuatro Paradigmas de Investigación (1970-1983)

1. **Estocástico**: HMM para reconocimiento de voz
2. **Basado en Lógica**:
   - Q-system (Colmerauer, 1978)
   - DCG (Definite Clause Grammar)
   - LFG (Lexical Functional Grammar)
3. **Comprensión del lenguaje natural**:
   - SHRDLU
   - Escuela de Yale (Schank)
   - Redes semánticas
   - Sistema LUNAR (Woods, 1967)
4. **Modelado del discurso**:
   - Estructura y enfoque del discurso (Grosz)
   - Resolución de referencias (Hobbs)
   - Modelo BDI (creencias-deseos-intenciones)

#### Revivir del Empirismo (1983-1993)

**Modelos de Estados Finitos**:
- Fonología y morfología (Kaplan y Kay, 1981)
- Sintaxis (Church, 1980)

**Retorno del Empirismo**:
- Modelos probabilísticos en reconocimiento de voz (IBM Watson Research)
- Etiquetado morfosintáctico (POS tagging)
- Análisis y resolución de ambigüedades
- **Enfoque de evaluación**: Métricas cuantitativas y comparación de resultados
- Desarrollo en generación de lenguaje natural

#### Unión de Vertientes (1994-1999)

**Cambios principales**:
1. Modelos probabilísticos se vuelven estándar
2. Explotación comercial:
   - Reconocimiento de voz
   - Revisión de ortografía y gramática
3. Comunicación aumentativa para discapacitados
4. Auge de la web: necesidad de recuperación y extracción de información

#### Auge del Aprendizaje Automático (2000-presente)

**Recursos clave**:
- **Linguistic Data Consortium (LDC)**: materiales anotados
- **Penn Treebank**: anotaciones sintácticas
- **Prague Dependency Treebank**: estructura de dependencias
- **PropBank**: anotaciones semánticas

**Enfoques**:
- **Supervisado** (hasta 2005):
  - SVM (Máquinas de Vectores de Soporte)
  - Máxima entropía
  - Regresión logística multinomial
  - Modelos bayesianos

- **No supervisado** (desde 2005):
  - Traducción automática sin datos anotados
  - Modelado de temas
  - Etiquetado morfosintáctico (Goldwater y Griffiths, 2007)
  - Etiquetado semántico (Titov y Klementiev, 2012)

- **Deep Learning** (desde 2006):
  - Término acuñado por Geoffrey Hinton
  - Redes neuronales recurrentes (RNN)
  - Alternativa a HMM en análisis
  - Modelos seq2seq para chatbots
  - Base de agentes conversacionales actuales

### 3.3 Conocimiento del Lenguaje en PLN

**6 Tipos de Conocimiento Necesarios**:

#### 1. Fonética y Fonología
- **Qué es**: Conocimiento sobre sonidos lingüísticos
- **Para qué**: Reconocimiento y síntesis de voz
- **Cómo**: Pronunciación de palabras y generación acústica de sonidos

#### 2. Morfología
- **Qué es**: Componentes significativos de palabras
- **Para qué**: Reconocer variaciones (plurales, conjugaciones)
- **Cómo**: Descomposición en raíz y terminaciones

#### 3. Sintaxis
- **Qué es**: Relaciones estructurales entre palabras
- **Para qué**: Ordenar y agrupar palabras correctamente
- **Cómo**: Conocimiento de estructura gramatical

#### 4. Semántica
- **Tipos**:
  - **Semántica léxica**: Significado de palabras individuales
  - **Semántica composicional**: Significado de combinaciones de palabras
- **Para qué**: Comprender el significado y la relación con la estructura sintáctica

#### 5. Pragmática
- **Qué es**: Uso del lenguaje en contexto
- **Para qué**: Interpretar intenciones y actos de habla

#### 6. Discurso
- **Qué es**: Análisis de texto más allá de la oración
- **Para qué**: Coherencia, cohesión y referencia en el texto

**Interrelación**: Estos conocimientos se utilizan de forma conjunta. La sintaxis y la semántica, por ejemplo, trabajan juntas en el procesamiento.

---

## 🎯 CONCEPTOS CLAVE PARA MEMORIZAR

### Automatización Inteligente:
- **4 capacidades**: Visión, Ejecución, Lenguaje, Pensar y Aprender
- **Hiperautomatización**: Trasladar tareas rutinarias humanas a sistemas automáticos
- **RPA**: Robot Process Automation para ejecución de tareas

### Sistemas de Razonamiento:
- **Factores de Certeza**: Escala de -1 a +1
- **Teorema de Bayes**: P(H|E) = P(E|H)·P(H) / P(E)
- **Naïve Bayes**: Clasificador probabilístico que asume independencia

### Lógica Difusa:
- **Función de pertenencia**: Valor entre 0 y 1
- **Variables lingüísticas**: Valores en lenguaje natural (bajo, medio, alto)
- **Modificadores**: "muy" (reduce), "más o menos" (aumenta)

### Historia del PLN:
- **1940-1950**: Paradigmas fundacionales (autómatas, teoría de la información)
- **1957-1970**: Simbólico vs Estocástico
- **1970-1983**: 4 paradigmas (estocástico, lógica, comprensión, discurso)
- **1983-1993**: Revivir del empirismo
- **1994-1999**: Unión de vertientes
- **2000-presente**: Auge del Machine Learning y Deep Learning

### Hitos Importantes PLN:
- **1952**: Primer sistema de reconocimiento de voz (Bell Labs)
- **1963**: Brown Corpus (primer corpus online)
- **1972**: SHRDLU (Winograd)
- **2006**: Término "Deep Learning" (Hinton)

### Conocimientos del Lenguaje:
1. Fonética/Fonología (sonidos)
2. Morfología (componentes de palabras)
3. Sintaxis (estructura)
4. Semántica (significado)
5. Pragmática (contexto)
6. Discurso (texto completo)

---

## 💡 CONSEJOS DE ESTUDIO

1. **Entiende las 4 capacidades** de la automatización inteligente y cómo se relacionan
2. **Diferencia** entre sistemas basados en reglas, factores de certeza y lógica difusa
3. **Conoce la cronología** del PLN y los paradigmas de cada época
4. **Identifica las tecnologías clave** de cada capacidad de IA
5. **Relaciona conceptos**: ¿Cómo Deep Learning cambió el PLN?
6. **Comprende los 6 tipos de conocimiento** del lenguaje y su interrelación

---

_Resumen creado para Semana 3 - Noviembre 2025_
