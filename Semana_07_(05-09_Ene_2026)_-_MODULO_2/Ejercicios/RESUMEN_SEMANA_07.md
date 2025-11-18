# RESUMEN SEMANA 7 - Módulo 2, Temas 1-2

**Periodo**: 5-9 Enero 2026
**Material**: Secciones 1-2 (páginas 1-60)
**Temas**: Programas Informáticos y Lenguajes de Programación / Características de los Lenguajes

---

## TEMA 1: PROGRAMAS INFORMÁTICOS Y LENGUAJES DE PROGRAMACIÓN

### 1.2 Algoritmos

**Definición de Algoritmo**:
> Secuencia ordenada y finita de operaciones sencillas a través de la cual podemos determinar la solución a un problema.

**Características Básicas**:
1. **Serie finita**: Tiene inicio y fin
2. **Secuencialidad**: Pasos ordenados
3. **Sin ambigüedad**: Instrucciones claras y concretas
4. **Validez**: Sin errores
5. **Eficiencia**: Obtiene solución en poco tiempo
6. **Optimización**: Más eficiente posible sin errores
7. **Independencia**: Utilizables por cualquier máquina
8. **Precisión**: Resultados exactos
9. **Repetibilidad**: Ejecutables múltiples veces

**Condiciones que deben cumplir**:
- Finitud del número de acciones elementales
- Definibilidad (precisión en el lenguaje: pseudocódigo)
- Entrada especificada
- Salida especificada
- Efectividad (tiempo finito)

**Partes de un Algoritmo**:

1. **Entrada**: Datos con los que opera el algoritmo
2. **Proceso**: Pasos y operaciones que sigue el algoritmo
3. **Salida**: Resultado que entrega el algoritmo

**Algoritmia**:
- Tratamiento sistemático de técnicas para diseño y análisis de algoritmos eficientes
- Estudio conceptual (modelización de datos, modelos de máquinas, métodos)
- Criterios de evaluación (complejidad, verificación, expresión en lenguaje)

**Visualización de Algoritmos**:

**Diagramas de Flujo**: Representaciones gráficas de los pasos de un proceso

Símbolos principales:
- **Óvalo**: Comienzo o final del programa
- **Paralelogramo**: Operación de entrada
- **Rectángulo**: Instrucción o proceso
- **Diamante**: Decisión a tomar
- **Híbrido**: Operación de salida
- **Flechas**: Conectan pasos e indican dirección

### 1.3 Pseudocódigo

**Definición**:
- Versión simplificada de código en lenguaje plano
- Utiliza frases cortas para escribir código
- Destinado a ser leído por humanos (human-friendly)
- Cada línea representa una línea de código real

**Herramientas para Pseudocódigo**:

1. **PSeInt**:
   - Herramienta libre, gratuita y multiplataforma
   - Pseudolenguaje en español
   - Detecta errores y ofrece sugerencias
   - Permite trabajar con diagramas de flujo

2. **PseudoEditor**:
   - Editor online en inglés y gratuito
   - Resaltado de sintaxis dinámica
   - Almacenamiento en la nube

**Notación Algorítmica**:

**Acción Elemental**:
```
acción elemental
```

**Composición Secuencial**:
```
acción primera
acción segunda
...
acción n-ésima
```

**Composición Condicional**:
```
si condición entonces
    acción si
fin si
```

**Composición Alternativa**:
```
si condición entonces
    acción si
si no
    acción no
fin si
```

**Composición Selectiva**:
```
según indicador hacer
    valor primero: acción primera
    valor segundo: acción segunda
    ...
    valor último: acción última
fin según
```

**Composición Iterativa**:

1. Repetir...hasta:
```
repetir
    acción
hasta condición
```

2. Mientras...hacer:
```
mientras condición hacer
    acción
fin mientras
```

3. Para:
```
para índice = valor inicial hasta índice = valor final hacer
    acción
fin para
```

### 1.4 Programas Informáticos

**Definición**:
- Código escrito para resolver un problema siguiendo reglas sintácticas de un lenguaje
- Conjunto de sentencias que se convierten en operaciones ejecutadas por circuitos electrónicos

**Software**: Conjunto de programas informáticos y datos utilizados por los mismos

**Tipos de Dispositivos**:
- Ordenador personal
- Estación de trabajo
- Servidor
- Teléfono inteligente
- Dispositivo IoT

**Clasificación de Programas**:

1. **Software de Sistema**:
   - Sistemas operativos
   - Drivers de dispositivos
   - Firmware
   - Traductores de lenguajes
   - Utilidades

2. **Software de Aplicación**:
   - Procesadores de texto
   - Hojas de cálculo
   - Navegadores web
   - Software multimedia
   - Bases de datos
   - Aplicaciones móviles
   - CRM

3. **Software de Programación**:
   - IDEs (Eclipse, JetBrains, Visual Studio)
   - Herramientas de acceso a bases de datos
   - Herramientas de testing

### 1.5 Lenguajes de Programación

**Definición**:
- Expresan cálculos de forma comprensible para personas y máquinas
- Permiten dar instrucciones que las máquinas entienden
- Todos se reducen a lenguaje binario o código máquina (0s y 1s)

**Compilación**: Proceso de traducción de un programa a código máquina

**Rankings de Popularidad**:
- **IEEE**: Python #1, Java #2, C #3, C++ #4, JavaScript #5
- **TIOBE**: Python, C, Java, C++, C#
- **JetBrains**: JavaScript, HTML/CSS, SQL, Python, Java más utilizados

### Pensamiento Computacional

**Definición**: Proceso de pensamiento para crear soluciones ejecutables por computadora

**Elementos del Pensamiento Computacional**:

1. **Descomposición**: Dividir problema en partes más sencillas

2. **Reconocimiento de Patrones**: Identificar elementos comunes

3. **Abstracción**: Separar detalles importantes de los que no

4. **Diseño de Algoritmos**: Crear solución con pasos simples y repetibles

---

## TEMA 2: CARACTERÍSTICAS DE LOS LENGUAJES DE PROGRAMACIÓN

### 2.2 Evolución de los Lenguajes de Programación

**Lenguaje Máquina** (1ª Generación):
- Código binario (0s y 1s)
- Único lenguaje que entiende el hardware
- Dependiente del hardware
- Difícil de programar y depurar

**Lenguaje Ensamblador** (2ª Generación):
- Usa símbolos y mnemónicos
- Necesita ensamblador para traducir a código máquina
- Específico de cada arquitectura de procesador
- Más fácil que lenguaje máquina

**Lenguajes de Alto Nivel** (3ª Generación):
- Sintaxis similar al lenguaje natural
- Portables (independientes de la máquina)
- Ejemplos: Java, JavaScript, Python, Ruby, C++, PHP

**Compiladores vs Intérpretes**:

**Compiladores**:
- Traducen código fuente completo a código máquina
- Crean programas ejecutables
- Mejor rendimiento en ejecución
- Tiempo de compilación puede ser elevado

**Intérpretes**:
- Analizan y traducen instrucción por instrucción
- Mayor flexibilidad en desarrollo
- Ejecución más lenta que código compilado
- No requieren compilación previa

**Lenguajes Mixtos**: Java, Lisp (compilan a bytecode y luego interpretan)

### 2.3 Sintaxis y Estructura

**Componentes Comunes**:

1. **Tipos de Datos**:
   - Sistema de tipos para clasificar valores
   - **Tipado Fuerte**: No permite operar tipos diferentes
   - **Tipado Débil**: Permite intercambiar tipos
   - **Tipado Estático**: Comprobación en compilación
   - **Tipado Dinámico**: Comprobación en ejecución

2. **Variables**:
   - Contenedor de información en memoria
   - Componentes: identificador y valor
   - Nomenclatura: sin espacios, no empezar con número, no palabras reservadas
   - Convenciones: camelCase (Java), snake_case (Python)

3. **Estructuras de Datos**:
   - Listas
   - Tuplas
   - Diccionarios
   - Conjuntos

4. **Operadores**:

   **Aritméticos**: +, -, *, **, /, //, %

   **Comparación**: >, >=, <, <=, =, ===, !=

   **Lógicos**: and, or, not

   **Asignación**: =, +=, -=, *=, /=

5. **Estructuras de Control**:

   **Condicionales**:
   - if (si)
   - else (entonces)
   - else-if (entonces si)
   - switch (interruptor)

   **Repetitivas**:
   - **Determinadas**: for (rango máximo acotado)
   - **Indeterminadas**: while (depende de condiciones)

6. **Funciones o Procedimientos**:
   - Bloque de código reutilizable
   - Componentes: signatura (visibilidad, retorno, identificador, parámetros) y cuerpo
   - Variables locales existen solo durante ejecución

### 2.4 Paradigmas de Programación

**Definición**: Estilo de programación para lidiar con la complejidad

**Dos Familias Principales**:

#### 1. Programación Imperativa

**Características**:
- Especifica CÓMO se debe llevar a cabo un proceso
- Usa variables, estructuras de control
- Define flujo de control paso por paso

**Subparadigmas**:

**A. Programación Estructurada**:
- Tres estructuras básicas:
  - Secuencia (una tras otra)
  - Selección o condicional (if/else)
  - Iteración (for/while)

**Programación Procedimental**: Uso de procedimientos/funciones que modifican estado

**B. Programación Orientada a Objetos (POO)**:
- Organiza programas como objetos
- **Elementos básicos**: Clases y Objetos
- **Clase**: Plantilla con atributos y métodos
- **Objeto**: Instancia particular de una clase
- **Mecanismos**: Encapsulación, Herencia, Abstracción, Polimorfismo, Serialización, Asociación, Composición
- **Patrones de Diseño**: Soluciones a problemas comunes (Factory, Adapter, Builder, Prototype, etc.)

#### 2. Programación Declarativa

**Características**:
- Define QUÉ se espera del programa
- No especifica el CÓMO implementarlo
- Define lógica sin detallar flujo de control

**Subparadigmas**:

**A. Programación Funcional**:
- Llamadas a funciones concatenadas
- Funciones como parámetros de otras funciones
- Funciones como retorno de otras funciones

**Características**:
1. **Inmutabilidad de datos**: Crear nuevas variables sin modificar existentes
2. **Transparencia referencial**: Mismo resultado para misma entrada siempre
3. **Modularidad**: Diseño en pequeños módulos independientes
4. **Mantenibilidad**: Facilidad para evolucionar y corregir
5. **Funciones puras**: Sin efectos secundarios
6. **Funciones de orden superior**: Toman funciones como argumentos

**B. Programación Lógica**:
- Basada en lógica formal
- Compuesta por hechos y reglas
- Ejemplo: Prolog (programming in logic)
- Formato: "A es verdadero si B, C y D son verdaderos"

### 2.5 Características de Lenguajes para IA

**Computación Simbólica**:
- Manipulación de expresiones y símbolos matemáticos
- Símbolos combinados con reglas/heurísticas
- Campos: Álgebra computacional, Resolución de teoremas, Sistemas de planificación, Diagnosis, Sistemas expertos

**Ramas de IA**:
1. Razonamiento y resolución de problemas
2. Representación del conocimiento
3. Planificación
4. Aprendizaje automático (Machine Learning)
5. Procesamiento del lenguaje natural (PLN)
6. Percepción (visión, reconocimiento facial, voz, objetos)

**Características Necesarias**:
- Paradigma declarativo
- Manejo de estructuras de datos
- Búsqueda y optimización
- Lógica
- Métodos probabilísticos
- Manejo de incertidumbre
- Clasificación
- Estadística
- Recursión y Back tracking
- Aprovechamiento de recursos computacionales (CPU, GPU)

**Proceso de Ciencia de Datos**:
1. **Acceso y extracción**: Sensores, archivos, bases de datos, APIs
2. **Análisis**: Exploración, limpieza, tratamiento
3. **Preprocesamiento**
4. **Modelado**
5. **Visualización e interpretación**

**Lenguajes Principales para IA**:
- **Paradigma declarativo**: Lisp, Prolog, Haskell
- **Multiparadigma con frameworks**: Python, Java
- Beneficio del paradigma declarativo: libera al programador de aspectos técnicos
- Importancia de frameworks y librerías en constante evolución

---

## CONCEPTOS CLAVE PARA MEMORIZAR

### Definiciones Esenciales:
- **Algoritmo**: Secuencia ordenada y finita de operaciones para resolver un problema
- **Pseudocódigo**: Versión simplificada de código en lenguaje plano
- **Programa**: Código escrito en lenguaje de programación siguiendo reglas sintácticas
- **Software**: Conjunto de programas y datos
- **Compilación**: Traducción de código fuente a código máquina
- **Paradigma**: Estilo de programación

### Evolución de Lenguajes:
1. **Lenguaje Máquina**: Código binario (0s y 1s)
2. **Lenguaje Ensamblador**: Símbolos y mnemónicos
3. **Lenguajes Alto Nivel**: Sintaxis similar al lenguaje natural

### Paradigmas Principales:
- **Imperativa**: Estructurada, Procedimental, Orientada a Objetos
- **Declarativa**: Funcional, Lógica

### Estructuras de Control:
- **Condicionales**: if, else, else-if, switch
- **Repetitivas**: for (determinada), while (indeterminada)

### Tipos de Software:
1. Sistema (SO, drivers, firmware)
2. Aplicación (procesadores texto, navegadores, apps)
3. Programación (IDEs, herramientas desarrollo)

### Características POO:
- Clases y Objetos
- Encapsulación, Herencia, Abstracción, Polimorfismo

### Características Programación Funcional:
- Inmutabilidad
- Transparencia referencial
- Funciones puras
- Funciones de orden superior

---

## CONSEJOS DE ESTUDIO

1. **Practica con pseudocódigo**: Usa PSeInt para crear algoritmos sencillos
2. **Dibuja diagramas de flujo**: Visualiza la lógica de problemas simples
3. **Entiende la diferencia**: Compilación vs Interpretación
4. **Compara paradigmas**: Imperativo vs Declarativo, sus ventajas/desventajas
5. **Identifica estructuras**: Reconoce condicionales, bucles y funciones en ejemplos
6. **Relaciona con IA**: Cómo cada característica beneficia el desarrollo de IA

---

Resumen creado para Semana 7 - Enero 2026
