# RESUMEN SEMANA 15 - Módulo 3, Temas 1-2

**Periodo**: 2-6 Marzo 2026
**Material**: Secciones 1-2 (páginas 1-60)
**Temas**: Introducción al Aprendizaje Automático y Análisis Exploratorio de Datos

---

## TEMA 1: INTRODUCCIÓN AL APRENDIZAJE AUTOMÁTICO

### 1.1 IA Fuerte vs IA Débil (Clasificación de John Searle)

**IA Fuerte (Inteligencia Artificial General)**:
- Persigue el objetivo original de la IA (Conferencia de Dartmouth, 1956)
- Busca desarrollar máquinas capaces de comportarse como un humano
- Aún no se ha logrado
- Representante principal: Ben Goertzel

**IA Débil**:
- Se centra en resolver problemas concretos o específicos
- Aplicaciones: reconocimiento de habla, traducción, clasificación de imágenes
- Ha conseguido importantes logros prácticos

### 1.2 Caracterización de IA Fuerte y Débil

| IA Débil | IA Fuerte |
|----------|-----------|
| Existe en la vida real | Solo existe en ciencia ficción |
| AlphaGo, Watson, etc. | 3CP0, Wall-e, etc. |
| Orientada a problemas concretos | Orientada a resolver problemas abiertos |
| Reactivo | Proactivo |
| Inflexibles - solo funcionan para el problema diseñado | Flexibles - se adaptan a cualquier situación |
| Son programadas o entrenadas por humanos | Se autoprograman |
| Implementadas sobre miles de neuronas artificiales | Implementadas sobre millones de redes neuronales |
| No razonan, solo computan | Imitan el comportamiento humano |
| Aprenden a partir de ejemplos similares | Aprenden como los humanos |
| Tareas repetitivas | Aprenden nuevas tareas |

### 1.3 Hitos de la IA Débil

- **1979**: BKG 9,8 gana al campeón mundial de Backgammon
- **1997**: Deep Blue vence a Garry Kasparov en ajedrez
- **2008**: Google lanza primera aplicación de reconocimiento de voz
- **2011**: Watson gana el concurso Jeopardy!
- **2012**: Primeras aplicaciones de reconocimiento de imágenes con gatos
- **2016**: AlphaGo gana al campeón mundial de Go
- **2017**: Robot Sophia se convierte en ciudadana saudí
- **2018**: Alpha Zero aprende a jugar ajedrez por sí misma

### 1.4 El Problema del Aprendizaje Automático

**Definición del Proceso de Aprendizaje**:
- **L**: Programa o algoritmo de aprendizaje (Learner)
- **P**: Profesor o entrenador (con herramientas)
- **T**: Tarea a ejecutar
- **D**: Experiencia o datos de entrenamiento
- **m**: Métrica de evaluación
- **E**: Entorno o ambiente

**Condición de Aprendizaje**:
> L aprende si mejora su desempeño en T dentro del entorno E, a medida que se le somete a la experiencia D, evaluado por P mediante m.

### 1.5 Tipos de Razonamiento

**Razonamiento Inductivo**:
- Parte de premisas particulares
- Obtiene conclusiones generales
- Proceso de generalización
- Base del aprendizaje automático (principio inductivo)

**Razonamiento Deductivo**:
- Parte de premisas generales
- Obtiene conclusiones particulares

### 1.6 Tipos de Aprendizaje Automático

**1. Aprendizaje Supervisado**:
- Se entrena con datos etiquetados (incluye respuestas)
- **Tareas**:
  - **Regresión**: Predecir variables continuas (ej: precio de casa)
  - **Clasificación**: Predecir variables categóricas (ej: género, enfermedad)

**2. Aprendizaje No Supervisado**:
- Se entrena sin etiquetas (solo preguntas, sin respuestas)
- **Tarea principal**:
  - **Clustering**: Agrupar datos por similaridad
    - Jerárquico
    - Particional

**3. Aprendizaje con Reforzamiento**:
- Basado en condicionamiento operante
- Aprende mediante recompensas y castigos
- Puede ser con reforzamiento positivo o negativo
- Algoritmos principales: Q-Learning, SARSA

### 1.7 Conjuntos de Datos (Datasets)

**Estructura**:
- Organizados de forma tabular (filas y columnas)
- **Filas**: Casos, instancias o tuplas
- **Columnas**: Variables, rasgos, predictores o características

**Clasificación de Variables por su Función**:
- **Variables Dependientes**: Variable predicha (objetivo)
- **Variables Independientes**: Predictores

**Clasificación de Variables por su Naturaleza**:

**Variables Cualitativas**:
- **Nominales**: Categorías sin orden (ej: color de cabello, género)
- **Ordinales**: Categorías con orden (ej: grado de satisfacción)

**Variables Cuantitativas**:
- **Discretas**: Valores puntuales, enteros (ej: número de niños, páginas)
- **Continuas**: Cualquier valor numérico (ej: altura, peso, temperatura)

### 1.8 Algoritmos vs Modelos

**Algoritmo de Aprendizaje**:
- Serie de pasos para calcular parámetros del modelo
- Es el método para adquirir conocimiento
- Mismo algoritmo para diferentes datasets

**Modelo de Aprendizaje**:
- Conjunto de parámetros calculados después del entrenamiento
- Es el conocimiento en sí
- Permite hacer predicciones
- Diferente para cada dataset

### 1.9 Algoritmos Principales por Tipo

**Aprendizaje Supervisado - Regresión**:
- Regresión Lineal
- Regresión Logística

**Aprendizaje Supervisado - Clasificación**:
- KNN (K-Nearest Neighbor)
- CART (Árboles de Clasificación y Regresión)
- Random Forest
- Naive Bayes
- SVM (Support Vector Machines)
- Redes Neuronales

**Aprendizaje No Supervisado - Clustering**:
- K-Means
- C-Means
- Fuzzy C-Means
- DBSCAN

**Aprendizaje con Reforzamiento**:
- Q-Learning
- SARSA

### 1.10 Requisitos de Datos por Algoritmo

**Métodos de Regresión**:
- Requieren rasgos numéricos
- No toleran valores faltantes (Missing Values)
- Muy sensibles a datos anómalos (Outliers)
- Usan todos los rasgos sin distinción

**Redes Neuronales**:
- Necesitan rasgos numéricos
- No toleran valores faltantes
- Relativamente tolerantes a outliers y ruido (si están bien configuradas)

**Aprendizaje Bayesiano (Naive Bayes)**:
- Trabaja con rasgos categóricos (versión inicial)
- Muy sensible a valores faltantes
- Sensible a redundancia y datos ruidosos
- Asume independencia entre rasgos

**Aprendizaje Basado en Instancias (KNN)**:
- Usa métricas de distancia o similaridad
- Problemas: alto uso de memoria, baja tolerancia al ruido
- Requiere técnicas de reducción de datos

**SVM (Support Vector Machines)**:
- Requiere rasgos numéricos
- Sin valores faltantes
- Robustos ante outliers y ruido

**Aprendizaje Basado en Reglas y Árboles de Decisión**:
- Necesitan rasgos nominales o discretizados
- Valores faltantes impactan negativamente
- Sensibles a datos anómalos y ruidosos

### 1.11 Proceso de Aprendizaje Automático

**Etapas del Proceso**:

1. **Establecimiento del Problema**:
   - Entender el problema a resolver
   - Reuniones con expertos del dominio
   - Revisar documentación y experiencias previas

2. **Recolección y Limpieza de Datos (Preprocesamiento)**:
   - Integración de datos
   - Análisis exploratorio
   - Detección de anomalías, valores faltantes
   - Normalización y transformación
   - **Etapa más importante: ~60% del tiempo del proyecto**

3. **Construcción y Evaluación de Modelos**:
   - Entrenamiento de modelos
   - Definición de parámetros
   - Evaluación con métricas
   - Ajuste y sintonización

4. **Despliegue**:
   - Poner el modelo en producción
   - Monitoreo constante
   - Reentrenamiento cuando sea necesario

---

## TEMA 2: ANÁLISIS EXPLORATORIO DE DATOS Y PREPROCESAMIENTO

### 2.1 Importancia del Preprocesamiento

**¿Por qué preprocesar?**:
- Los datos pueden tener errores de integración
- Pueden existir duplicados, valores faltantes, anomalías
- Los datos pueden estar en diferentes unidades o formatos
- Sin preprocesamiento, los modelos no serán confiables

**Etapas del Preprocesamiento**:
1. **Preparación de Datos**
2. **Reducción de Datos**
3. **División del Conjunto de Datos**

### 2.2 Preparación de Datos

#### 2.2.1 Integración de Datos

**Fuentes de Datos**:
- Datalakes en la nube
- Servidores remotos (API REST)
- Datawarehouses empresariales
- Bases de datos relacionales (SQL Server, MySQL, Oracle)
- Bases de datos NoSQL (MongoDB)
- Bases de datos de grafos (Neo4J)
- Ficheros (CSV, Excel)

**Problemas Comunes**:
- Duplicación de casos (tuplas)
- Rasgos redundantes
- Diferentes unidades de medida
- Mismos rasgos con nombres diferentes

#### 2.2.2 Detección de Rasgos Duplicados o Redundantes

**Definición**:
> Un rasgo es redundante cuando su información está contenida o puede derivarse de otro atributo.

**Técnicas de Detección**:

**Para Rasgos Nominales**: Prueba Chi-Cuadrado (χ²)
- Hipótesis nula: Los rasgos son independientes
- Si p > α: Rasgos independientes (no relacionados)
- Si p ≤ α: Rasgos correlacionados (redundantes)
- α (nivel de significación) típico: 0.05 (5%)

**Para Rasgos Numéricos**: Coeficiente de Correlación de Pearson
- r = 1: Perfectamente correlacionados (redundantes)
- 0 < r < 1: Correlación positiva (>0.85-0.90 = altamente correlacionados)
- -1 < r < 0: Correlación negativa
- r = -1: Correlación negativa perfecta

#### 2.2.3 Detección de Casos Duplicados

**Enfoques**:
- Enfoque probabilista (inferencia bayesiana)
- Enfoque de aprendizaje supervisado (CART, SVM)
- Enfoque basado en distancia

**Importancia**:
- Evitar desperdicio de espacio y tiempo
- Prevenir inconsistencias
- Problema complejo y sutil

#### 2.2.4 Manejo de Valores Faltantes (Missing Values)

**Representación**: NaN ("No es un Número")

**Métodos Univariados (Simples)**:
- Sustituir con la media o mediana del rasgo (si es cuantitativo)
- Sustituir con la moda del rasgo (si es categórico)
- Sustituir con la media/moda de la clase

**Métodos Multivariados (Elaborados)**:
- Máxima Verosimilitud (Maximum Likelihood)
- Maximización de la Esperanza (Expectation-Maximization)
- Imputación Múltiple
- Análisis de Componentes Principales Bayesiano (BPCA)
- KNN (K-Nearest Neighbor Imputation)
- KNN Ponderado (WKNNI)
- K-Means Clustering (KMI)
- Fuzzy K-Means (FKMI)
- SVM (SVMI)
- Descomposición de Valores Singulares (SVDI)
- Mínimos Cuadrados Locales (LLSI)

**Herramientas en Python (scikit-learn)**:
- `SimpleImputer`: Métodos univariados
- `IterativeImputer`: Métodos multivariados
- Pandas `fillna()`:
  - fillna(0): Sustituye con cero
  - method="bfill": Valor del caso siguiente
  - method="ffill": Valor del caso anterior

#### 2.2.5 Manejo de Datos Anómalos (Outliers)

**Definición (Hawkins, 1980)**:
> "Un outlier es una observación que se desvía tanto del resto que hace sospechar que fue generada por otro mecanismo"

**Tipos**:
- **Univariados**: Consideran un solo rasgo
- **Multivariados**: Consideran todos los rasgos de una instancia

**Detección de Outliers Univariados**:

**Rango Intercuartílico (IQR)**:
```
IQR = Q3 - Q1
```

**Outliers Leves**:
```
x < Q1 - 1.5 * IQR  o  x > Q3 + 1.5 * IQR
```

**Outliers Severos**:
```
x < Q1 - 3 * IQR  o  x > Q3 + 3 * IQR
```

**Herramienta Visual**: Gráfico de Caja y Bigote (Boxplot)

**Detección de Outliers Multivariados**:

**Categorías de Métodos**:
- Métodos basados en pruebas estadísticas
- Métodos basados en profundidad
- Métodos basados en desviación
- Métodos basados en distancia
- Métodos basados en densidad
- Métodos de alta dimensionalidad

**Herramienta en Python**: Librería PyOD (>30 algoritmos)
- ABOD (Angle Based Outlier Detection)
- Y muchos más...

**Tratamiento de Outliers**:
- Eliminarlos (si son muchos datos y pocos outliers)
- Sustituir con media/mediana
- Sustituir con valores en los bordes del bigote
- Depende del origen del outlier (error vs valor genuino)

#### 2.2.6 Normalización

**Objetivo**: Representar todos los atributos en una escala común sin distorsionar diferencias

**¿Cuándo Normalizar?**:
- Redes neuronales
- Algoritmos de regresión
- Métodos basados en distancia

**Métodos de Normalización**:

**1. Normalización Min-Max**:
```
x' = (x - minA) / (maxA - minA)
```
- Rango típico: [0, 1] o [-1, 1]
- Clase en Python: `MinMaxScaler`

**2. Normalización Z-Score**:
```
x' = (x - X̄) / σX
```
Donde:
- X̄ = media del atributo
- σX = desviación estándar

---

## CONCEPTOS CLAVE PARA MEMORIZAR

### Definiciones Esenciales:

- **IA Fuerte**: Busca máquinas que se comporten como humanos (aún no lograda)
- **IA Débil**: Resuelve problemas específicos (reconocimiento, traducción, etc.)
- **Aprendizaje Supervisado**: Aprende de datos con etiquetas
- **Aprendizaje No Supervisado**: Encuentra patrones sin etiquetas
- **Aprendizaje con Reforzamiento**: Aprende mediante recompensas/castigos
- **Dataset**: Conjunto de datos organizado en filas (casos) y columnas (rasgos)
- **Algoritmo**: Pasos para calcular parámetros del modelo
- **Modelo**: Parámetros calculados que permiten hacer predicciones

### Tipos de Variables:

**Por Función**:
- Dependiente (objetivo a predecir)
- Independientes (predictores)

**Por Naturaleza**:
- Cualitativas: Nominales, Ordinales
- Cuantitativas: Discretas, Continuas

### Problemas en Datos:

- **Missing Values (MV)**: Valores faltantes (NaN)
- **Outliers**: Valores anómalos o extremos
- **Duplicados**: Casos o rasgos repetidos
- **Redundancia**: Rasgos correlacionados

### Proceso ML:

1. Establecer problema (entender qué se necesita)
2. Preprocesar datos (~60% del tiempo)
3. Construir y evaluar modelos
4. Desplegar a producción

---

## CONSEJOS DE ESTUDIO

1. **Diferencia los tipos de aprendizaje**: Supervisado, No Supervisado, Reforzamiento
2. **Entiende la diferencia**: Algoritmo vs Modelo
3. **Conoce los tipos de variables**: Es fundamental para elegir técnicas
4. **Preprocesamiento es crítico**: 60% del tiempo se dedica a esto
5. **Cada algoritmo tiene requisitos**: Unos necesitan datos numéricos, otros categóricos
6. **Los outliers no siempre son malos**: Depende del contexto
7. **Normalizar no siempre es necesario**: Depende del algoritmo
8. **La integración de datos es compleja**: Múltiples fuentes y formatos

---

## HERRAMIENTAS PYTHON MENCIONADAS

**Para Preprocesamiento**:
- `sklearn.impute.SimpleImputer`: Missing values (univariado)
- `sklearn.impute.IterativeImputer`: Missing values (multivariado)
- `pandas.fillna()`: Missing values (simple)
- `sklearn.preprocessing.MinMaxScaler`: Normalización Min-Max
- `sklearn.preprocessing.StandardScaler`: Normalización Z-Score
- `pyod`: Detección de outliers (>30 algoritmos)

**Para Análisis**:
- Pandas: Análisis y manipulación de datos
- Matplotlib/Seaborn: Visualización (boxplots, etc.)

---

_Resumen creado para Semana 15 - Marzo 2026_
_MÓDULO 3: Aprendizaje Automático Aplicado - Inicio_
