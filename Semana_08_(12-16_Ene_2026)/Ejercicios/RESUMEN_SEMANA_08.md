# RESUMEN SEMANA 8 - Módulo 2, Temas 3-4

**Periodo**: 12-16 Enero 2026
**Material**: Secciones 3-4 (páginas 61-120)
**Temas**: Lenguajes de Programación para IA y Lenguajes de Marcado

---

## TEMA 3: PRINCIPALES LENGUAJES DE PROGRAMACIÓN PARA IA

### 3.1. Introducción y Objetivos

**Objetivos del Tema**:
- Identificar la existencia de diferentes lenguajes de programación
- Conocer los distintos lenguajes y sus características
- Distinguir las fortalezas de cada lenguaje
- Decidir el uso de un lenguaje u otro según el problema

### 3.2. Lenguajes de Programación para IA

**Principales Lenguajes**:
- Lisp
- Prolog
- R
- Python
- Haskell
- Java
- JavaScript
- C++
- Julia

**Consideraciones Importantes**:
- Con el crecimiento de Big Data e IA es común usar **múltiples lenguajes** en una misma arquitectura
- Se utilizan diferentes lenguajes para cada fase del proyecto de IA
- Desde la captura de datos hasta el procesamiento y obtención de conclusiones

### 3.3. Python

**Historia**:
- Creado en 1989 por **Guido van Rossum**
- Primera versión publicada en 1991
- Nombre en homenaje al grupo **Monty Python**
- Objetivo: ser fácil de usar y aprender, pero potente

**Filosofía Python**:
- **Zen de Python** por Tim Peters (ejecutar: `import this`)
- **PEP 8**: Guía de estilo de Python
- Código más legible que C++ o Java

**Ventajas de Python**:

1. **Tipado dinámico**:
   - No necesita definir el tipo de variables al inicializarlas
   - Python asigna el tipo automáticamente
   - Facilita el aprendizaje pero dificulta la detección de errores de tipo

2. **Lenguaje multiparadigma**:
   - Programación orientada a objetos (como Java, C++)
   - Programación imperativa (como C)
   - Programación funcional (como Haskell)

3. **Interpretado/Scripts**:
   - Puede ejecutarse de forma interpretada (consola)
   - O mediante scripts (archivos .py)

4. **Extensible**:
   - Gran cantidad de módulos y librerías
   - Implementado en C++, permite crear nuevos módulos en C++

**Versiones de Python**:

**Problema Histórico**:
- Hasta diciembre 2019 existían 2 versiones activas
- **Python 2** vs **Python 3**

**Línea Temporal**:
- **1991**: Python 1.0
- **2008**: Python 3.0 (cambio radical, no retrocompatible)
- **2008**: Python 2.6 (soporte para versión 2)
- **2010**: Python 2.7 y 3.1
- **Enero 2020**: Python 2.7 descontinuado
- **Actualidad**: Solo Python 3 recibe actualizaciones

### 3.4. R

**Definición**:
- Lenguaje popular para **modelado estadístico** y **análisis de datos**
- Conjunto integrado de herramientas de software

**Historia**:
- **1976**: Conceptualizado en Laboratorios Bell por John Chambers
- Desarrollado como extensión del lenguaje S
- **1992**: Proyecto R por Ross Ihaka y Robert Gentleman
- **1995**: Primera versión
- **2000**: Versión beta estable

**Aspectos Clave de R**:
- Conjunto de operadores para cálculos en matrices
- Colección amplia de herramientas para análisis de datos
- Facilidades gráficas para análisis y visualización de datos
- Lenguaje bien desarrollado, simple y eficaz (llamado "S")
- Sistema totalmente integrado (environment)
- Vehículo para nuevos métodos de análisis de datos interactivos

**Usos Principales de R** (según JetBrains 2021):
- **71%**: Análisis de datos
- **54%**: Propósitos educativos
- **23%**: Machine learning
- **8%**: Programming parsers/scrapers/ETL scripts
- **4%**: Código de producción
- **3%**: Otros

**Paquetes Populares de R**:
- **ggplot2**: 54%/57%
- **dplyr**: 36%/37%
- **data.table**: 27%/34%
- **plotly**: 25%/32%
- **tidyr**: 24%
- **shiny**: 18%/22%
- **randomForest**: 15%/17%
- **devtools**: 14%/15%
- **stringr**: 14%/14%
- **caret**: 12%/13%

**Ventajas de R**:
- Open Source
- Buen soporte para manipulación de datos
- Amplio ecosistema de paquetes (CRAN: https://cran.r-project.org/)
- Capacidad para visualización de datos
- Compatibilidad
- Generación de reportes
- Portabilidad
- Útil para proyectos de estadística
- Ideal para Machine Learning
- Recibe actualizaciones constantes

### 3.5. Java

**Definición**:
- Lenguaje de programación y plataforma para desarrollo de software portable
- Alto nivel y multiparadigma

**Historia**:
- **Años 90**: Iniciativa de Sun Microsystems para dispositivos inteligentes
- **2010**: Oracle adquiere Sun y toma el relevo del desarrollo

**Características**:
- Rápido, seguro y fiable
- Soporta múltiples paradigmas: estructurada, orientada a objetos, funcional

**Tipos de Aplicaciones Java**:
1. **Aplicaciones standalone**: ejecutables sin instalación, pueden trabajar offline
2. **Aplicaciones web**: software cliente-servidor accedido desde navegador
3. **Aplicaciones móviles e IoT**: para dispositivos inteligentes

**Características Principales**:

1. **Fácil de aprender**: respecto a C y C++

2. **Robusto**: tipado fuerte y mecanismos de gestión de excepciones

3. **Arquitectura neutral**: gracias a la JVM (Máquina Virtual Java) se ejecuta en cualquier plataforma

4. **Capacidad multihilo**: permite ejecutar múltiples tareas simultáneamente

**Proceso de Compilación**:
- Código fuente: **.java**
- Compilador: **javac**
- Código intermedio: **.class** (bytecode)
- JVM interpreta y compila a código nativo del SO

**Plataforma Java**:

**Componentes**:
1. **Bibliotecas estándar (Java API)**: interfaces y clases con funcionalidades comunes
2. **Máquina Virtual Java (JVM)**: registros, pila, recolector de basura, interpreta bytecode

**Ediciones**:
- **Java SE** (Standard Edition): para estaciones de trabajo y ordenadores
- **Java EE** (Enterprise Edition / Jakarta EE): para servidores empresariales, servicios web, bases de datos

**Versiones Java**:
- Desde versión 9: ciclo de release cada **6 meses**
- Versiones **LTS** (Long Term Support): recomendadas por mantenimiento a largo plazo

**Popularidad**:
- Entre los 3 lenguajes más populares (TIOBE Index)
- Stack Overflow 2021: 35.35% de uso

**Usos de Java** (JetBrains 2021):
- **39%**: Websites
- **26%**: Utilities
- **19%**: System Software
- **16%**: Finance
- **15%**: Libraries/Frameworks
- **14%**: Database/Data Storage
- **12%**: IT Infrastructure
- **7%**: Business Intelligence/Data Science/Machine Learning

### 3.6. Lisp

**Definición**:
- Lenguaje de programación funcional
- De propósito general
- Basado en aplicación de funciones a datos
- Utiliza funciones matemáticas para control de datos

**Historia**:
- Creado en los **años 50** por **John McCarthy**
- Nombre: **LISP** (List-Processing)
- Creado para procesamiento de listas

**Elemento Fundamental**:
- La **lista**: estructura de datos
- Cada función y programa en Lisp se representa en forma de lista

**Dialectos Importantes**:
- Scheme
- **Common Lisp** (consolidándose como estándar)
- Clojure
- Emacs Lisp
- Racket

**Características**:

**Tipos de Elementos Básicos**:
1. **El átomo**: datos elementales (números, símbolos, caracteres, cadenas)
2. **Las listas**: incluye la lista "nil" (lista nula sin elementos)

**Propiedades**:
- Trata elementos de manera **no destructiva**
- Funciones devuelven lista resultado sin modificar parámetros recibidos
- Uno de los primeros lenguajes en manejar **excepciones** (catch y throw)
- Comentarios comienzan por ';'
- Parámetros van por valor o referencia según clasificación de la función

**Organización de Datos**:
- Átomos literales (símbolos)
- Átomos numéricos
- Estructura básica: la lista

**Relación con IA**:
- Especialmente vinculado a programación en IA
- Código y datos tienen la misma estructura (en forma de lista)
- Utilizado en SHRDLU (sistema de comprensión del lenguaje natural)

**Lisp como Modelo de Referencia**:
- Considerado modelo de referencia para programación funcional

### 3.7. JavaScript

**Definición**:
- Lenguaje de alto nivel y multiparadigma
- Creado para dotar de **dinamismo** a páginas web
- Evita apariencia estática

**Características**:
- Los programas se llaman **scripts**
- Se escriben en documentos HTML o archivos externos (.js)
- Ejecutados por el navegador al cargar la página
- Soportado por todos los navegadores web

**Elementos de Sintaxis**:
- Variables
- Operadores
- Funciones
- Estructuras de datos
- Estructuras de control condicional
- Estructuras de control repetitivo

**Historia**:
- Originalmente llamado **LiveScript**
- Renombrado a JavaScript (Java era popular en esa época)
- **Importante**: Java y JavaScript son completamente diferentes
- Objetivo: superar limitación de webs estáticas

**Versiones (ECMAScript)**:

| Versión | Año |
|---------|-----|
| ECMAScript 1 (ES1) | 1997 |
| ECMAScript 2 (ES2) | 1998 |
| ECMAScript 3 (ES3) | 1999 |
| ECMAScript 4 (ES4) | No publicado |
| ECMAScript 5 (ES5) | 2009 |
| ECMAScript 6 (ES6) | 2015 |
| ECMAScript 2016 | 2016 |
| ECMAScript 2017 | 2017 |
| ECMAScript 2018 | 2018 |
| ECMAScript 2019 | 2019 |
| ECMAScript 2020 | 2020 |

**Desde 2016**: versiones anuales usando el año como nombre

**Machine Learning con JavaScript**:

**TensorFlow.js**:
- Biblioteca de código abierto para desarrollar y entrenar modelos de ML
- Plataforma de extremo a extremo para ML
- Ecosistema flexible de herramientas, bibliotecas y recursos
- Permite usar modelos listos o convertir modelos de TensorFlow Python
- Entrena e implementa modelos en navegador y Node.js

**Privacidad y Personalización**:
- Modelo base en servidor, copia en dispositivo del usuario
- Ajuste del modelo con datos del usuario mediante bibliotecas JS de ML
- Mantiene datos en dispositivos de usuarios
- Libera recursos del servidor
- Permite uso offline

**Dispositivos Móviles**:

**Frameworks multiplataforma**:
- Apache Cordova
- Ionic
- Flutter
- React Native

**Ventajas**:
- Escribir código una vez, implementar para iOS y Android
- Lanzan "vista web" (objeto navegador que ejecuta JavaScript)
- React Native: versión especial de TensorFlow.js

**Usos de JavaScript** (JetBrains 2021):
- **73%**: Websites
- **25%**: Utilities
- **11%**: System Software
- **11%**: Libraries/Frameworks
- **9%**: Finance
- **7%**: Database/Data Storage
- **6%**: Entertainment
- **5%**: IT Infrastructure
- **5%**: Programming Tools
- **4%**: Business Intelligence/Data Science/Machine Learning

### 3.8. Prolog

**Definición**:
- Lenguaje de **programación lógica** y semi-interpretado
- Programación lógica: paradigma donde programas son aserciones lógicas
- Subparadigma del paradigma declarativo

**Historia**:
- Desarrollado en Universidad de Aix-Marseille (Marsella, Francia)
- Creadores: **Alain Colmerauer** y **Philippe Roussel**
- Objetivo original: procesamiento de lenguajes naturales (no crear lenguaje de programación)

**Funcionamiento**:
- Similar a Java
- Código fuente se compila a **bytecode**
- Bytecode se interpreta en **WAM** (Warren Abstract Machine)
- **No hay estándar**: bytecode de un entorno puede no funcionar en otro

**Componentes de Entorno Prolog**:
1. **Compilador**: transforma código fuente a bytecode
2. **Intérprete**: ejecuta bytecode (similar a CLI de SO)
3. **Biblioteca de utilidades**: funcionalidades básicas (manipular cadenas, E/S, etc.)

**Elementos en Prolog**:

1. **Átomos**: definición genérica de objeto del mundo real

2. **Predicados**: especifican características de objetos o relaciones entre ellos

3. **Hechos**:
   - Algo que ocurre en el mundo
   - Característica o relación entre objetos
   - Ejemplo: `tiene(coche,ruedas).`
   - Nombres de objetos y relaciones: minúscula
   - Primero la relación, luego objetos separados por comas
   - Termina con punto "."

4. **Variables**:
   - Representa el valor de un Átomo
   - Puede estar instanciada o no instanciada
   - Nombres comienzan con **mayúscula**
   - Variable anónima: "_" (comodín)

5. **Reglas**:
   - Hecho que depende de uno o más hechos
   - Implicaciones lógicas: p → q
   - Estructura: cabeza :- cuerpo
   - Cabeza: un único hecho
   - Cuerpo: uno o más hechos separados por "," (AND lógico)
   - Termina con "."

**Entornos de Desarrollo**:
- SICStus
- CIAO Prolog (auto documentador, preprocesador)
- Prácticamente todos son multiplataforma
- Muchos basados en Emacs

### 3.9. Otros Lenguajes y Tecnologías

**Otros lenguajes relevantes para IA**:
- C
- C++
- MATLAB
- Julia

---

## TEMA 4: LENGUAJES DE MARCADO

### 4.1. Introducción y Objetivos

**Objetivos del Tema**:
- Comprender qué son los lenguajes de marcado
- Diferencias con lenguajes de programación
- Conocer los diferentes tipos de lenguaje de marcado
- Saber en qué situaciones aplicar cada uno
- Conocer tecnologías relacionadas

### 4.2. Los Lenguajes de Marcado

**Definición**:
- Lenguaje legible por humanos
- Usado para anotar un documento electrónico
- Permite que máquinas comprendan mejor estilo y estructura

**Características**:
- Utiliza **etiquetas** para definir elementos
- Basado en palabras reales inteligibles (no sintaxis ininteligible)
- Conjuntos específicos de instrucciones
- Explican qué son las partes de un documento y cómo formatearlas

**Etiquetas**:
- Usan corchetes angulares: `<>`
- Van en pares
- Símbolos: `<` y `>`
- Barra inclinada cuando se cierran
- Ejemplo: `<title> </title>`

**Elementos**:
- Incluyen etiquetas y contenido entre ellas
- Ejemplo: `<title>Ejemplo de título</title>`

**Lenguajes de Marcado Populares**:
- XML
- HTML
- XHTML
- MathML
- SGML
- KML

**Importante**: ML significa **Markup Language**

**Renderizado**:
- Lenguajes funcionan en segundo plano
- No se ven etiquetas al abrir documento
- Se ve contenido **renderizado** (con formato aplicado)

### 4.3. Tipos de Lenguajes de Marcado

**1. Marcado Semántico** (o Descriptivo):
- Explica el **propósito** del texto
- Si es título, párrafo, etc.
- Semántica: interpretación correcta del significado
- Muchas etiquetas HTML tienen significado semántico
- Ejemplo: `<h1>` significa encabezado más importante

**2. Marcado de Presentación**:
- Se encarga del **aspecto** del contenido
- Indica formato visual de textos
- Características visuales específicas
- Ejemplo: `<i>` para texto en cursiva

### 4.4. HTML

**Definición**:
- **HTML**: HyperText Markup Language
- Lenguaje de marcado de hipertexto
- Componente más básico de entornos web
- Define significado y estructura del contenido web

**Características**:
- **'Hipertexto'**: enlaces que conectan páginas entre sí
- **No es lenguaje de programación**: es lenguaje de marcado
- Solo define estructura, no permite lógica de control

**Etiquetas HTML**:
- Abren con: `<`
- Cierran con: `>`
- Etiquetas de apertura: `<p>`
- Etiquetas de cierre: `</p>`
- Todo entre ambas adopta la estructura indicada

**Historia**:
- **1989**: Tim Berners-Lee inventa WWW en CERN (Ginebra, Suiza)
- **WWW**: World Wide Web, sistema de documentos de hipertexto
- **1993**: HTML 1.0 (primera versión oficial)

**Versiones de HTML**:

| Versión | Año |
|---------|-----|
| HTML 1.0 | 1993 |
| HTML 2.0 | 1995 |
| HTML 3.2 | 1997 |
| HTML 4.0 | 1998 |
| XHTML | 2000 |
| HTML 5.0 | 2014 |
| HTML 5.1 | 2016 |
| HTML 5.2 | 2017 |

**Estándar Web**:
- Formulado por:
  - **W3C** (Consorcio WWW): desde 1994, dirigido por Tim Berners-Lee
  - **WHATWG** (Web Hypertext Application Technology Working Group): desde 2004

**Funcionamiento de la Web**:

**Proceso al acceder a sitio web**:
1. URL se traduce a dirección IP (usando DNS)
2. Se envía petición HTTP a la IP solicitando recurso web
3. Servidor procesa petición y devuelve documento HTML
4. Navegador renderiza HTML interpretando código HTML, CSS y JavaScript

**HTML 5**:

**Novedades Importantes**:
1. **Simplificación en declaraciones**:
   - Doctype html
   - Codificación de caracteres
   - Links a hojas CSS
   - Scripts de JavaScript

2. **Etiquetas y atributos eliminados**

3. **Nuevas etiquetas semánticas**:
   - `<main>`
   - `<header>`
   - `<footer>`
   - `<nav>`
   - `<section>`
   - `<aside>`
   - `<article>`

**Tecnologías Web**:

**Pilares Básicos**:
1. **HTML**: estructura del contenido
2. **CSS** (Cascading Style Sheets): presentación/diseño gráfico
3. **JavaScript**: comportamiento/dinamismo

**CSS**:
- Lenguaje de diseño gráfico
- Define presentación de contenido estructurado
- Permite definir aspecto visual

**JavaScript**:
- Lenguaje de programación multiparadigma
- Dota a web de comportamiento
- Permite lógica condicional, operaciones, cargar datos
- Crear HTML programáticamente
- Interactividad basada en usuario

**Estructura HTML**:

**IDEs para Desarrollo**:
- IDEs de JetBrains
- Visual Studio Code
- Sublime Text
- Atom
- Brackets

**Estructura Mínima HTML 5**:
- DOCTYPE
- head
- body

**Codificación**:

**Juego de Caracteres**:
- Toda información se almacena en formato numérico
- Necesaria correspondencia entre códigos numéricos y caracteres
- **Unicode**: conjunto de juegos de caracteres estándar
- Codificaciones: UTF-8, UTF-16, UTF-32

**UTF-8**:
- Desde 2014: codificación predeterminada en HTML 5
- Unicode Transformation Format
- Etiqueta: `<meta charset="UTF-8">`

**Entidades Carácter**:
- Referencias a caracteres especiales
- Permiten mostrar caracteres especiales en HTML
- Ejemplo: `&amp;` para &

**Entidades Numéricas**:
- Referencias a caracteres
- Equivalentes al número Unicode
- Ejemplo: `&#38;` para &

**Accesibilidad**:

**Definición**:
- Capacidad de acceso por todas las personas
- Independiente de conocimientos o discapacidades
- Conjunto de prácticas para máxima usabilidad

**Prácticas de Accesibilidad**:
- Subtítulos en vídeos
- Imágenes/multimedia que sustituyan o complementen textos
- Tamaño fuente variable
- Tamaño elementos en pantallas táctiles
- Interacción por voz
- Reproducción de contenido textual mediante voz
- Ajustes en colores

**Recursos**:
- ARIA
- WCAG (Web Content Accessibility Guidelines)
- WebAIM (Web Accessibility in Mind)
- A11Y Style Guide

**Usabilidad**:

**Definición**:
- Técnicas que ayudan a realizar tareas en entornos gráficos
- Interfaz debe permitir acciones de forma sencilla e intuitiva

**Principios**:
1. **Anticipación**: sitio debe anticiparse a necesidades del usuario
2. **Autonomía**: interfaz suficientemente intuitiva
3. **Colores**: paleta en armonía, facilita visualización
4. **Reversibilidad**: permitir deshacer acciones
5. **Ley de Fitts**: objetivos cerca de posición previa

**Validación HTML**:
- Herramientas online para verificar marcado correcto
- Detectan: etiquetas mal cerradas, mal escritas, orden incorrecto
- Ejemplo: **W3C Markup Validation Service**

**HTML Semántico**:
- Utilizar elementos HTML correctos para cada propósito
- Mejor usar etiquetas semánticas que genéricas

**Elementos Genéricos**:
- `<div>`, `<span>`

**Elementos Semánticos**:
- `<button>`, `<form>`, `<table>`, `<h1>`, `<article>`, `<footer>`, `<nav>`, `<header>`

**Ventajas**:
- Motores de búsqueda indexan mejor (favorece SEO)

**Atributos Importantes**:
- **alt**: texto descriptivo para imágenes si no cargan
- **title**: información extra que se muestra en tooltip

### 4.5. XML

**Definición**:
- **XML**: eXtensible Markup Language
- Lenguaje de marcado extensible
- Estándar aprobado por W3C

**Características**:
- Sintaxis genérica para marcar datos con etiquetas legibles
- Formato estándar flexible
- Personalizable para dominios diversos
- Meta lenguaje de marcado

**Aplicaciones**:
- Sitios web
- Intercambio de datos
- Gráficos vectoriales
- Genealogía
- Serialización de objetos
- Llamadas a procedimientos remotos
- Sistemas de correo de voz

**Ventajas**:
- Programas pueden leer y manipular datos en documentos XML
- Amplia gama de librerías en varios lenguajes
- Software estándar (navegadores, editores) puede trabajar con XML
- Misma sintaxis subyacente en todos los casos

**Unidad Básica**:
- **Elemento**: unidad básica de datos y marcado

**Especificación XML**:
- Define sintaxis exacta del marcado
- Cómo elementos están delimitados por etiquetas
- Aspecto de las etiquetas
- Nombres aceptables para elementos
- Dónde se colocan atributos

**Diferencias con HTML**:
- XML es **meta lenguaje de marcado**
- No tiene conjunto fijo de etiquetas
- Permite inventar nuevos elementos según necesidades
- Ejemplo: químicos usan elementos de química, músicos de música

**Extensibilidad**:
- "X" en XML significa Extensible
- Lenguaje puede ampliarse y adaptarse
- Flexible en elementos que permite
- Estricto en otros aspectos (gramática)

**Gramática XML**:
- Suficientemente específica para analizadores XML
- **Documentos bien formados**: satisfacen la gramática
- Documentos mal formados: rechazados por procesadores

**Aplicaciones XML**:
- Conjuntos de etiquetas acordados
- Aplicación de XML en dominio particular
- Ejemplo: SVG (gráficos vectoriales)

**Marcado**:
- Describe estructura del documento
- Asociación entre elementos
- Indica semántica (fecha, persona, código de barras)
- No dice nada sobre presentación (negrita, cursiva)
- Lenguaje de marcado estructural y semántico

**Esquema**:
- Documenta marcado permitido
- Instancias se comparan con esquema
- **Documentos válidos**: coinciden con esquema
- Validez depende del esquema
- No todos los documentos necesitan validación

### 4.6. XHTML

**Definición**:
- **XHTML**: eXtensible HyperText Markup Language
- Desarrollado por W3C en 2000
- Versión más extendida de HTML
- HTML definido como aplicación XML

**Características**:
- Conserva todas las características de HTML
- Introduce reglas más estrictas
- Sitios independientes de dispositivo y navegador
- Se muestra correctamente en todos los navegadores/plataformas

**Diferencias con HTML**:

1. **Siempre usar <!DOCTYPE>**:
   - Declaración de tipo de documento XHTML obligatoria
   - Elementos obligatorios: `<html>`, `<head>`, `<title>`, `<body>`

2. **Elementos correctamente insertados**:
   - No permite anidar incorrectamente

3. **Etiquetas de cierre obligatorias**:
   - Siempre requeridas (en HTML a veces se pueden omitir)

4. **Minúsculas obligatorias**:
   - Mayúsculas y minúsculas se distinguen
   - Todas las etiquetas y atributos en minúsculas

5. **Valores entre comillas**:
   - Valores de atributos deben ir entre comillas

6. **No minimizar atributos**:
   - Mal: `<input checked />`
   - Bien: `<input checked="checked" />`

7. **Usar id en lugar de name**:
   - Atributo name parcialmente obsoleto

**Beneficios de XHTML**:
- Código más limpio (etiquetas cerradas y anidadas correctamente)
- Usa menos ancho de banda (optimiza carga)
- Buen formato facilita transporte a dispositivos inalámbricos
- Funciona con CSS para crear páginas fácilmente

**XHTML vs. HTML**:
- HTML: lenguaje principal para páginas web
- XHTML: versión extendida
- HTML: aplicación de SGML
- XHTML: aplicación de XML
- HTML: framework flexible, analizador HTML permisible
- XHTML: subconjunto restrictivo XML, analizador XML estándar

---

## CONCEPTOS CLAVE PARA MEMORIZAR

### Lenguajes de Programación:

**Python**:
- Creador: Guido van Rossum (1989)
- Tipado dinámico, multiparadigma, interpretado, extensible
- Zen de Python y PEP 8
- Python 2.7 descontinuado en enero 2020

**R**:
- Para modelado estadístico y análisis de datos
- Primera versión: 1995
- Open source, amplio ecosistema CRAN
- Ideal para visualización y Machine Learning

**Java**:
- Sun Microsystems (años 90), ahora Oracle
- Multiparadigma, arquitectura neutral
- JVM (bytecode .class)
- Ediciones: SE, EE/Jakarta EE
- Ciclo release: 6 meses, versiones LTS

**Lisp**:
- John McCarthy (años 50)
- Programación funcional
- Elemento fundamental: lista
- Dialectos: Common Lisp, Scheme, Clojure

**JavaScript**:
- Para dinamismo en páginas web
- Soportado por todos los navegadores
- ECMAScript: versiones anuales desde 2016
- TensorFlow.js para Machine Learning

**Prolog**:
- Programación lógica
- Universidad Aix-Marseille
- WAM (Warren Abstract Machine)
- Elementos: átomos, predicados, hechos, variables, reglas

### Lenguajes de Marcado:

**Conceptos Generales**:
- Etiquetas: `<>`
- Elementos: etiquetas + contenido
- Marcado semántico vs presentación

**HTML**:
- Tim Berners-Lee (1989)
- HTML 1.0 (1993), HTML 5 (2014)
- Estándares: W3C, WHATWG
- UTF-8: codificación predeterminada
- Tecnologías: HTML + CSS + JavaScript

**XML**:
- eXtensible Markup Language
- Meta lenguaje de marcado
- Bien formado vs válido
- Esquemas para validación

**XHTML**:
- W3C (2000)
- HTML como aplicación XML
- Reglas más estrictas que HTML
- Minúsculas obligatorias, cierre de etiquetas siempre

### Accesibilidad y Usabilidad:
- Accesibilidad: acceso por todas las personas
- Usabilidad: facilidad para realizar tareas
- Principios: anticipación, autonomía, colores, reversibilidad, Ley de Fitts

---

## CONSEJOS DE ESTUDIO

1. **Distingue claramente** entre lenguajes de programación y lenguajes de marcado
2. **Conoce las fortalezas** de cada lenguaje (Python: fácil y versátil, R: estadística, Java: empresarial)
3. **Entiende la historia** de versiones (Python 2 vs 3, HTML 5, ECMAScript)
4. **Memoriza creadores** y fechas clave
5. **Practica con ejemplos** de cada lenguaje
6. **Comprende las diferencias** entre HTML, XML y XHTML
7. **Asocia lenguajes con aplicaciones** específicas
8. **Recuerda componentes** (JVM para Java, WAM para Prolog)

---

_Resumen creado para Semana 8 - Enero 2026_
