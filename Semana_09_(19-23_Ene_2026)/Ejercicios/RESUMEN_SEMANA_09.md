# RESUMEN SEMANA 9 - Modulo 2, Tema 4 (Seccion 5)

**Periodo**: 19-23 Enero 2026
**Material**: Seccion 5 (paginas 121-133)
**Tema**: Lenguajes de Marcado - LaTeX, Markdown, JSON y YAML

---

## TEMA 4: LENGUAJES DE MARCADO (CONTINUACION)

### 4.7. LaTeX

**Historia y Origen**:
- **TEX** (1977): Desarrollado por Donald E. Knuth como sistema de composicion tipografica para libros con expresiones matematicas
- **LATEX** (1985): Desarrollado por Leslie Lamport basado en TEX (LATEX 2.09)
- Permite enfocarse en la estructura del documento en lugar del formato

**Definicion**:
> Sistema de preparacion de documentos para una composicion tipografica de alta calidad mediante un paquete de macros

**Caracteristicas Principales**:
- Compilador de archivos .tex a formatos como PDF
- Uso principal: documentos tecnicos o cientificos de tamano medio a grande
- Puede usarse para cualquier tipo de publicacion

**Aplicaciones de LaTeX**:
- Cartas y aplicaciones
- Articulos, informes, publicaciones
- Tesis y libros
- Documentos de quimica, fisica, computacion, biologia
- Leyes, literatura, musica y cualquier tematica

**Capacidades Automaticas**:
- Generar listas de contenidos, indices, glosarios
- Numerar capitulos y figuras automaticamente
- Incluir y organizar bibliografia
- Mantener indices y referencias cruzadas
- Evitar errores en numeracion y referencias

**Operaciones Principales**:

1. **Editar**: Utilizar un editor o IDE para generar un archivo .tex con el codigo LaTeX
2. **Compilar**: El motor de LaTeX convierte los archivos .tex en documentos PDF
3. **Visualizar**: Ver el documento generado (ej: TeXnicCenter tiene boton de visualizacion)

**Ventajas**:
- Ampliamente utilizado en entornos cientificos
- Muchas revistas aceptan documentos en LaTeX
- Excelente calidad del documento final
- Salida en distintos formatos: dvi, pdf, ps
- Ficheros fuente .tex son archivos ASCII (compilables en cualquier SO)
- Gratuito
- Muy potente

**Desventajas**:
- No es WYSIWYG (What You See Is What You Get)
- Necesita proceso de compilacion (posibles errores)
- No es un procesador de textos, sino sistema de preparacion de documentos
- Requiere concentrarse en el contenido, no en la apariencia

**Ejemplo de Codigo LaTeX**:
```latex
\documentclass{article}
\title{Cartesian closed categories and the price of eggs}
\author{Jane Doe}
\date{September 1994}
\begin{document}
\maketitle
Hello world!
\end{document}
```

---

### 4.8. Markdown

**Historia**:
- Creado por John Gruber en 2004
- Uno de los lenguajes de marcado mas populares del mundo

**Definicion**:
> Lenguaje de marcado ligero que permite agregar elementos de formato a documentos de texto sin formato

**Sintaxis Basica**:
- **Encabezado**: Se agrega signo # antes (ejemplo: # Encabezado uno)
- **Negrita**: Dos asteriscos antes y despues (ejemplo: \*\*texto en negrita\*\*)
- Extension de archivos: .md o .markdown

**Caracteristica Principal**:
- NO es WYSIWYG
- Sintaxis disenada para ser legible y simple
- El texto se puede leer incluso sin procesarlo
- Considerado lenguaje de marcado ligero

**Principales Usos**:
- Contenido para sitios web estaticos (Jekyll, GatsbyJS, Hugo)
- Documentos
- Notas
- Libros
- Presentaciones
- Mensajes de correo electronico
- Documentacion tecnica

**Ventajas**:
- **Portable**: A diferencia de formatos propietarios como Microsoft Word
- **Independiente de plataforma**: Funciona en cualquier dispositivo/SO
- **Ampliamente soportado**: Reddit, GitHub y muchas aplicaciones lo admiten

**Como Funciona**:
1. El texto se almacena en archivo con extension .md o .markdown
2. Se necesita aplicacion capaz de renderizar el archivo
3. Usa **procesador Markdown** (analizador o implementacion)
4. Toma texto con formato Markdown y lo envia a formato HTML
5. Puede verse en navegador web o imprimirse con hoja de estilo

---

### 4.9. Otras Tecnologias

#### JSON (JavaScript Object Notation)

**Definicion**:
> Formato de intercambio de datos entre plataformas software

**Proposito**:
- Formato de texto para intercambiar datos entre sistemas informaticos
- Evita necesidad de multiples traductores entre sistemas
- Formato unico acordado para comunicacion de datos

**Relacion con JavaScript**:
- Siglas: **J**ava**S**cript **O**bject **N**otation
- NO es necesario aprender JavaScript para usar JSON
- Gran popularidad porque JavaScript lo interpreta nativamente
- Formato idoneo para intercambio backend-frontend en aplicaciones web

**Ventajas para Desarrollo Web**:
- El frontend (JavaScript vanilla, Angular, React, Vue) puede recibir datos JSON
- API REST en backend puede enviar datos en formato JSON
- Al ser nativo para JavaScript, no hay tiempo perdido en conversion de formatos

**Contexto Historico**:
- Otros formatos de intercambio: XML (anterior a JSON), CSV
- No todos los sistemas usan JSON, pero muchos lo han adoptado
- Algunos sistemas siguen usando XML u otros formatos

---

#### YAML (YAML Ain't Markup Language)

**Definicion**:
> Lenguaje de serializacion de datos usado frecuentemente para escribir archivos de configuracion

**Caracteristicas Generales**:
- YAML es para datos, no para documentos
- Se utiliza en conjunto con otros lenguajes de programacion
- Extension de archivos: .yml o .yaml

**Sintaxis**:
- Caracteristicas de Perl, C, XML, HTML y otros lenguajes
- **Superconjunto de JSON**: Los archivos JSON son validos en YAML
- Usa sangria estilo Python para indicar anidamiento
- Caracteres de tabulacion NO permitidos (usar espacios)
- No hay simbolos de formato (llaves, corchetes, etiquetas de cierre, comillas)

**Estructura de Archivo YAML**:

1. **Mapas**:
   - Asocian pares clave-valor
   - Cada clave debe ser unica
   - El orden no importa
   - Similar a diccionario Python o variable Bash

2. **Listas**:
   - Valores enumerados en orden especifico
   - Puede contener cualquier numero de elementos
   - Secuencia comienza con guion (-) y espacio
   - Sangria la separa del padre
   - Similar a lista Python o matriz Bash/Perl

3. **Escalares**:
   - Datos arbitrarios codificados en Unicode
   - Valores: cadenas, enteros, fechas, numeros, booleanos

**Validacion**:
- Usar **linter** para verificar sintaxis
- Comando **yamllint** ayuda a garantizar validez antes de entregar

**Uso Principal - Archivos de Configuracion**:
- Se recomienda YAML sobre JSON para configuracion
- Mejor legibilidad y mas facil de usar
- Aunque JSON y YAML pueden usarse indistintamente

**Herramientas que Usan YAML**:

1. **Ansible**:
   - Crea procesos de automatizacion
   - **Playbooks**: Archivos YAML con 1+ reproducciones
   - Define estado deseado de un sistema
   - Cada Playbook ejecuta tareas que invocan modulos Ansible
   - Modulos escritos en cualquier lenguaje que devuelva JSON
   - Playbook consta de mapas y listas
   - Permite programar tareas repetitivas automaticamente

2. **Kubernetes**:
   - Funciona segun estado definido vs estado real
   - Objetos Kubernetes representan estado de cluster
   - Recursos (pods, objetos, implementaciones) se crean con archivos YAML
   - Al crear objeto, se incluyen especificaciones del estado deseado
   - Kubectl convierte archivo YAML a JSON para solicitud API
   - Desarrolladores/administradores especifican estado definido via archivos YAML/JSON
   - Kubernetes usa controlador para analizar diferencia entre estado definido y real

**Ventaja de Control de Versiones**:
- Archivos YAML pueden agregarse a control de codigo fuente (GitHub)
- Los cambios se pueden rastrear y auditar

---

## COMPARATIVA: XHTML vs HTML5

**Sensibilidad a Mayusculas**:
- **XHTML**: Distingue entre mayusculas y minusculas en etiquetas
- **HTML5**: NO es sensible a mayusculas/minusculas (como HTML)

**Compatibilidad de Navegadores**:
- **XHTML**: Compatible con todos los navegadores
- **HTML5**: Algunas etiquetas semanticas no compatibles en versiones antiguas

**Dispositivos**:
- **HTML5**: Mas adecuado para dispositivos moviles
- **XHTML**: Mas adecuado para pantallas de escritorio

**Permisividad**:
- **HTML5**: Mas permisible al escribir etiquetas y elementos
- **XHTML**: Mas estricto

---

## CONCEPTOS CLAVE PARA MEMORIZAR

### Lenguajes de Marcado para Documentos:

**LaTeX**:
- Sistema de composicion tipografica de alta calidad
- Ideal para documentos cientificos y tecnicos
- Archivos .tex compilados a PDF
- No es WYSIWYG

**Markdown**:
- Lenguaje de marcado ligero
- Sintaxis simple y legible
- Archivos .md o .markdown
- Ampliamente usado en GitHub, Reddit
- NO es WYSIWYG

### Formatos de Intercambio de Datos:

**JSON**:
- JavaScript Object Notation
- Formato de intercambio de datos
- Nativo para JavaScript
- Ideal para APIs REST

**YAML**:
- Para serializacion de datos y configuracion
- Superconjunto de JSON
- Usa sangria estilo Python
- Archivos .yml o .yaml
- Usado en Ansible y Kubernetes

### Aplicaciones Practicas:

- **LaTeX**: Publicaciones cientificas, tesis, articulos academicos
- **Markdown**: Documentacion tecnica, README de GitHub, contenido web
- **JSON**: APIs REST, intercambio datos frontend-backend
- **YAML**: Archivos de configuracion, Playbooks Ansible, recursos Kubernetes

---

## CONSEJOS DE ESTUDIO

1. **Entiende la diferencia** entre lenguajes para documentos (LaTeX, Markdown) y formatos de datos (JSON, YAML)
2. **Identifica casos de uso**: Que lenguaje usar segun la necesidad
3. **Conoce las sintaxis basicas**: Cada lenguaje tiene caracteristicas distintivas
4. **Relacion WYSIWYG**: LaTeX y Markdown NO son WYSIWYG
5. **JSON vs YAML**: YAML es superconjunto de JSON, mejor para configuracion
6. **Herramientas practicas**: Ansible usa YAML para Playbooks, Kubernetes para recursos

---

## PUNTOS IMPORTANTES

### LaTeX:
- Creado por Leslie Lamport (1985) basado en TEX de Donald Knuth (1977)
- 3 operaciones: Editar, Compilar, Visualizar
- Genera automaticamente indices, bibliografia, numeracion

### Markdown:
- Creado por John Gruber (2004)
- Procesador Markdown convierte a HTML
- Usado en Jekyll, GatsbyJS, Hugo

### JSON:
- Formato de intercambio de datos
- Nativo en JavaScript
- Alternativa: XML (anterior), CSV

### YAML:
- Lenguaje de serializacion
- Superconjunto de JSON
- Usado en Ansible (Playbooks) y Kubernetes (recursos)
- Validacion con yamllint

---

_Resumen creado para Semana 9 - Enero 2026_
