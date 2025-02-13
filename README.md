# Fase 1: Reconocimiento de la necesidad de accesibilidad web

## La Importancia de Diseñar Webs Accesibles

En la era digital actual, la **accesibilidad web** es fundamental para garantizar que todas las personas, independientemente de sus capacidades, puedan acceder, navegar y beneficiarse de la información y los servicios que ofrece internet. A continuación, se detalla por qué es crucial diseñar webs accesibles, sus beneficios y su relación con las normativas vigentes:

## ¿Por qué es importante diseñar webs accesibles?

- **Igualdad de Oportunidades:**  
  La accesibilidad web permite que personas con diferentes tipos de discapacidades (visual, auditiva, motriz, cognitiva, entre otras) puedan interactuar con el contenido digital de manera efectiva. Esto garantiza que todos los usuarios tengan igualdad de oportunidades para informarse, comunicarse y participar en la sociedad digital.

- **Cumplimiento Legal:**  
  Diseñar con accesibilidad en mente ayuda a cumplir con normativas y estándares internacionales y nacionales, como las **WCAG 2.1** y el **Real Decreto 1112/2018**. Este cumplimiento no solo evita posibles sanciones legales, sino que también establece un compromiso ético y profesional con la inclusión.

- **Mejora de la Experiencia del Usuario (UX):**  
  Un sitio web accesible ofrece una navegación intuitiva, estructuras claras y contenido organizado, lo que beneficia a todos los usuarios, no solo a aquellos con discapacidades. Una buena experiencia de usuario es clave para retener a los visitantes y fomentar una interacción positiva.

## Beneficios para los Usuarios y los Desarrolladores

- **Para los Usuarios:**
  - **Inclusión Digital:**  
    Las personas con discapacidades pueden acceder a la información y servicios sin barreras, lo que les permite participar plenamente en la vida digital.
  - **Interacción Simplificada:**  
    Un diseño accesible facilita la navegación y la comprensión de los contenidos, mejorando la experiencia de uso y reduciendo la frustración.

- **Para los Desarrolladores:**
  - **Diseño Robusto y Versátil:**  
    Al implementar pautas de accesibilidad, se crean interfaces que funcionan bien en diversos dispositivos y contextos, aumentando la compatibilidad y el alcance del sitio.
  - **Cumplimiento de Normativas:**  
    Incorporar estándares de accesibilidad reduce riesgos legales y proyecta una imagen de responsabilidad social y profesional, lo cual puede ser un factor diferenciador en el mercado.

## Relación con Normativas Vigentes

- **WCAG 2.1:**  
  Estas directrices internacionales ofrecen un marco de referencia para mejorar la accesibilidad del contenido web, proporcionando criterios medibles y aplicables para asegurar que las páginas sean utilizables por el mayor número de personas.

- **Real Decreto 1112/2018:**  
  Este decreto, aplicado en ciertos territorios, refuerza la necesidad de que los servicios digitales sean accesibles, estableciendo obligaciones legales para garantizar que los ciudadanos, incluidos aquellos con discapacidades, puedan acceder a la información y servicios públicos de manera efectiva.

## Contribución a la Inclusión Digital

La accesibilidad web no solo elimina barreras para personas con discapacidades, sino que también fomenta una experiencia de usuario más inclusiva y satisfactoria para todos. Al optimizar la navegación, mejorar la legibilidad y garantizar la adaptabilidad del contenido, se promueve una **inclusión digital** que beneficia a la sociedad en su conjunto, permitiendo una participación activa y equitativa en el entorno digital.

---

**Conclusión:**  
La implementación de la accesibilidad web es esencial tanto desde un punto de vista ético como práctico. Diseñar sitios web accesibles no solo cumple con las normativas legales y mejora la experiencia del usuario, sino que también impulsa una sociedad más inclusiva y equitativa, en la que cada individuo pueda disfrutar de los beneficios de la era digital sin restricciones.


# Fase 2: Análisis inicial de accesibilidad en documentos web
# Análisis Inicial de Accesibilidad en la Web de Cantina Chichilo

Se ha realizado un análisis preliminar de la accesibilidad de la web [Cantina Chichilo](http://www.cantinachichilo.com.ar) utilizando herramientas automáticas (como WAVE y Lighthouse) y pruebas manuales. A continuación, se documentan los principales problemas encontrados:

## Herramientas Utilizadas

- **WAVE:** Para detectar problemas técnicos de accesibilidad.
- **Lighthouse:** Para evaluar el rendimiento, la accesibilidad y otros aspectos clave.
- **Pruebas Manuales:** Verificación de la correcta utilización de etiquetas semánticas, textos alternativos, estructura de navegación y otros elementos que pueden no ser detectados automáticamente.
![Captura de pantalla 2025-02-13 161030](https://github.com/user-attachments/assets/db57e5ce-e836-419b-a747-7d86ae205fe2)
![Captura de pantalla 2025-02-13 161024](https://github.com/user-attachments/assets/bb44b2d9-8eb9-4f81-a7be-08243c417cf9)


## Problemas Identificados

### 1. Contraste Insuficiente

- **Descripción:**  
  Se han detectado áreas donde el contraste entre el texto y el fondo no cumple con los estándares mínimos establecidos por las WCAG. Esto dificulta la lectura para usuarios con baja visión o daltonismo.

- **Ubicación:**  
  - Secciones de "Promociones" y "Ofertas especiales" en la página principal.
  - Algunos bloques de texto sobre imágenes de fondo.

- **Impacto en la Experiencia del Usuario:**  
  Usuarios con discapacidades visuales pueden tener dificultades para leer el contenido, lo que reduce la accesibilidad y usabilidad general del sitio.

---

### 2. Falta o Uso Inadecuado de Texto Alternativo en Imágenes

- **Descripción:**  
  Algunas imágenes, especialmente las relacionadas con productos y banners promocionales, no cuentan con atributos `alt` descriptivos o los tienen vacíos.

- **Ubicación:**  
  - Imágenes de la galería de productos.
  - Banners promocionales en la página de inicio.

- **Impacto en la Experiencia del Usuario:**  
  Usuarios que dependen de lectores de pantalla no podrán comprender el contenido visual, lo que afecta la navegación y la percepción de la información.

---

### 3. Uso Incorrecto de Etiquetas Semánticas

- **Descripción:**  
  Se ha observado que en algunas secciones se utilizan etiquetas HTML no semánticas para elementos críticos como menús y artículos, lo que puede confundir a las tecnologías de asistencia.

- **Ubicación:**  
  - Menú de navegación principal y secundario.
  - Secciones de contenido en páginas internas.

- **Impacto en la Experiencia del Usuario:**  
  Las tecnologías de asistencia pueden interpretar incorrectamente la estructura del contenido, dificultando la navegación para usuarios con discapacidades.

---

### 4. Enlaces con Texto Poco Descriptivo

- **Descripción:**  
  Algunos enlaces emplean textos genéricos como "clic aquí" o "más información", sin ofrecer un contexto claro sobre su destino.

- **Ubicación:**  
  - Secciones informativas y artículos del blog.
  - Llamadas a la acción en diversas partes del sitio.

- **Impacto en la Experiencia del Usuario:**  
  Esto puede dificultar que los usuarios que utilizan lectores de pantalla determinen la relevancia del enlace, afectando la usabilidad y la navegación.

---

### 5. Problemas de Navegación en Dispositivos Móviles

- **Descripción:**  
  Durante las pruebas manuales se ha identificado que el menú de navegación presenta dificultades en dispositivos móviles, tales como botones pequeños y elementos que se solapan.

- **Ubicación:**  
  - Menú principal en la versión móvil del sitio.

- **Impacto en la Experiencia del Usuario:**  
  La usabilidad en dispositivos móviles se ve comprometida, dificultando el acceso a la información para usuarios que dependen de dispositivos táctiles.

---

## Conclusiones y Recomendaciones

El análisis ha identificado áreas clave para mejorar la accesibilidad de la web:

- **Ajustar el Contraste:**  
  Revisar y modificar la combinación de colores para asegurar un contraste adecuado en todos los bloques de contenido.

- **Implementar Textos Alternativos Adecuados:**  
  Asegurarse de que todas las imágenes cuenten con atributos `alt` descriptivos que expliquen su contenido o función.

- **Revisar la Semántica del HTML:**  
  Utilizar etiquetas HTML semánticas (como `<nav>`, `<main>`, `<article>`, `<header>`, `<footer>`) para estructurar correctamente el contenido y facilitar su interpretación por tecnologías de asistencia.

- **Optimizar los Textos de Enlaces:**  
  Reemplazar enlaces genéricos por descripciones claras que indiquen el destino o la función del enlace.

- **Mejorar la Navegación en Móviles:**  
  Rediseñar el menú de navegación para dispositivos móviles, asegurando que los botones sean lo suficientemente grandes y que los elementos no se solapen.

Implementar estas mejoras contribuirá a que la web de Cantina Chichilo sea más accesible y ofrezca una mejor experiencia de usuario para todos, especialmente para aquellos con discapacidades.


# Fase 3: Análisis de Principios, Pautas y Niveles de Conformidad

El objetivo de esta fase es familiarizarse con los principios fundamentales de las WCAG 2.1 y los niveles de conformidad (A, AA, AAA), y comprender cómo aplicarlos en el diseño y desarrollo de contenidos web accesibles.

## Principios Fundamentales de las WCAG 2.1

Las WCAG 2.1 se basan en cuatro principios clave que aseguran que el contenido web sea accesible para la mayor cantidad de usuarios:

### 1. Perceptible

El contenido debe presentarse de manera que pueda ser percibido por todos los usuarios, a través de distintos sentidos.

- **Pautas Específicas:**

- Proporcionar alternativas textuales para contenido no textual (por ejemplo, imágenes, vídeos).

- Asegurar que el contenido se presente de forma clara y organizada.

- **Ejemplo Práctico:**

Usar el atributo `alt` en imágenes:

```html

<img src="producto.jpg" alt="Zapato deportivo azul con suela blanca">
```
### 2\. Operable


Los elementos de la interfaz deben ser operables, permitiendo a los usuarios interactuar con ellos de manera eficiente.

-   **Pautas Específicas:**

    -   Garantizar que todas las funciones sean accesibles mediante teclado.
    -   Proveer tiempos de interacción adecuados y evitar contenidos que puedan causar reacciones físicas adversas (como flashes que provocan convulsiones).
-   **Ejemplo Práctico:**\
    Permitir la navegación mediante teclado:

    html

    CopiarEditar

    `<a href="contacto.html" tabindex="0">Contáctanos</a>`

### 3\. Comprensible

La información y el funcionamiento de la interfaz deben ser entendibles para todos los usuarios.

-   **Pautas Específicas:**

    -   Utilizar un lenguaje claro y sencillo.
    -   Ofrecer instrucciones y mensajes de error claros en formularios.
    -   Prever ayudas contextuales para facilitar la interacción.
-   **Ejemplo Práctico:**\
    Etiquetar correctamente los campos de un formulario:


    `<label for="email">Correo Electrónico:</label>
    <input type="email" id="email" name="email">`

### 4\. Robusto

El contenido debe ser lo suficientemente robusto para ser interpretado de manera fiable por una amplia variedad de agentes de usuario, incluyendo tecnologías de asistencia.

-   **Pautas Específicas:**

    -   Utilizar un marcado HTML semántico correcto (por ejemplo, `<nav>`, `<main>`, `<article>`, `<header>`, `<footer>`).
    -   Garantizar la compatibilidad con diferentes navegadores y dispositivos.
-   **Ejemplo Práctico:**\
    Estructurar correctamente el contenido:


    `<header>
      <h1>Bienvenidos a Nuestro Sitio</h1>
    </header>
    <nav>
      <ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="productos.html">Productos</a></li>
        <li><a href="contacto.html">Contacto</a></li>
      </ul>
    </nav>
    <main>
      <article>
        <h2>Nuestros Productos</h2>
        <!-- Contenido del artículo -->
      </article>
    </main>
    <footer>
      <p>&copy; 2025 Empresa Ejemplo</p>
    </footer>`

Niveles de Conformidad de las WCAG 2.1
--------------------------------------

Las WCAG 2.1 definen tres niveles de conformidad, que determinan el grado de accesibilidad del contenido:

-   **Nivel A:**\
    Es el nivel mínimo de accesibilidad. Se cumplen requisitos esenciales que permiten que el contenido sea utilizable, pero pueden quedar sin abordar algunas barreras.

-   **Nivel AA:**\
    Es el nivel recomendado para la mayoría de los sitios web. Este nivel aborda un mayor número de criterios que aseguran una experiencia accesible para la mayoría de los usuarios.

-   **Nivel AAA:**\
    Es el nivel más alto y estricto de accesibilidad. Asegura que el contenido sea accesible en la mayor medida posible, aunque puede ser difícil de implementar en todos los contextos.

### Nivel de Conformidad Objetivo: Nivel AA

El nivel AA se establece como objetivo para lograr un equilibrio adecuado entre accesibilidad y viabilidad técnica. Para cumplir con este nivel se deben considerar, entre otros, los siguientes requisitos:

-   **Contraste de Color:**\
    Asegurar que el contraste entre texto y fondo sea al menos de 4.5:1 para texto normal.

-   **Navegación por Teclado:**\
    Garantizar que todas las interacciones sean accesibles mediante teclado, sin depender exclusivamente del uso del ratón.

-   **Textos Alternativos y Multimedia Accesible:**\
    Proveer descripciones alternativas en imágenes y otros medios no textuales.

-   **Formularios Accesibles:**\
    Asegurar que todos los campos de entrada cuenten con etiquetas claras y mensajes de error comprensibles.

Conclusión
----------

Implementar estos principios y pautas garantiza que el contenido web sea:

-   **Perceptible:** Brindando alternativas para contenido visual y multimedia.
-   **Operable:** Asegurando que todas las funciones sean accesibles mediante distintos dispositivos y métodos de interacción.
-   **Comprensible:** Facilitando la comprensión y el uso a través de un lenguaje claro y una estructura lógica.
-   **Robusto:** Estructurando el contenido con HTML semántico para maximizar la compatibilidad con diversas tecnologías.

Adoptar el nivel de conformidad **AA** como objetivo permite que la mayoría de los usuarios, incluyendo aquellos con discapacidades, tengan una experiencia web positiva y sin barreras.

# Fase 4: Análisis y Priorización de Errores según Puntos de Verificación

## Objetivo

Identificar los errores más críticos en la web seleccionada ([Cantina Chichilo](http://www.cantinachichilo.com.ar)) según su impacto en la experiencia del usuario y proponer soluciones específicas para cada problema.

## Revisión de Problemas Detectados

De acuerdo al análisis inicial realizado en la Fase 2, se han detectado los siguientes problemas relevantes:

- Contraste insuficiente entre texto y fondo.
- Imágenes sin texto alternativo.
- Formularios sin etiquetas descriptivas.

Otros problemas identificados (no abordados en esta fase) incluyen el uso incorrecto de etiquetas semánticas, enlaces con textos poco descriptivos y problemas de navegación en dispositivos móviles.

## Priorización de Errores y Propuestas de Solución

### 1. Contraste Insuficiente entre Texto y Fondo

**Descripción:**  
El contraste entre algunos textos y sus fondos no cumple con los estándares mínimos de accesibilidad (mínimo 4.5:1 para texto normal), lo que dificulta la legibilidad, especialmente para usuarios con baja visión o daltonismo.

**Ubicación:**  
- Secciones de "Promociones" y "Ofertas Especiales" en la página principal.
- Bloques de texto superpuestos sobre imágenes de fondo.

**Impacto:**  
La baja legibilidad del contenido puede llevar a una experiencia de usuario deficiente, aumentando la exclusión de personas con discapacidades visuales.

**Solución Propuesta:**  
- Revisar y ajustar la paleta de colores para asegurar un contraste adecuado entre texto y fondo.
- Utilizar herramientas como WAVE o Contrast Checker para validar el ratio de contraste.
- Aplicar estilos CSS que refuercen la legibilidad en todos los dispositivos y contextos.

---

### 2. Imágenes sin Texto Alternativo

**Descripción:**  
Varias imágenes en la web carecen de atributos `alt` descriptivos, lo que impide que los usuarios que dependen de lectores de pantalla comprendan el contenido visual.

**Ubicación:**  
- Galería de productos.
- Banners promocionales en la página de inicio.

**Impacto:**  
La falta de descripciones en las imágenes reduce la accesibilidad para usuarios con discapacidades visuales, afectando la transmisión de información clave y la experiencia global.

**Solución Propuesta:**  
- Revisar todas las imágenes y agregar atributos `alt` descriptivos que expliquen el contenido o la función de cada imagen.
- Para imágenes meramente decorativas, utilizar `alt=""` para que sean ignoradas por los lectores de pantalla.
- Asegurarse de que las descripciones sean concisas y relevantes al contexto.

---

### 3. Formularios sin Etiquetas Descriptivas

**Descripción:**  
Los formularios presentes en la web no cuentan siempre con etiquetas (`<label>`) correctamente asociadas a sus campos de entrada, lo que dificulta la navegación e interacción para usuarios con tecnologías de asistencia.

**Ubicación:**  
- Formularios de contacto y suscripciones.
- Cualquier otro formulario de entrada de datos en el sitio.

**Impacto:**  
La ausencia de etiquetas descriptivas puede causar confusión y errores al momento de completar formularios, reduciendo la usabilidad y accesibilidad del sitio para todos los usuarios.

**Solución Propuesta:**  
- Añadir etiquetas (`<label>`) a todos los campos de entrada y asociarlas correctamente utilizando el atributo `for` vinculado al `id` correspondiente del campo.
- Incluir mensajes de error claros y accesibles para guiar al usuario en caso de entradas inválidas.
- Verificar que el formulario sea completamente navegable mediante teclado y compatible con lectores de pantalla.

## Conclusión

La priorización de errores se centra en los siguientes puntos críticos:

1. **Contraste Insuficiente entre Texto y Fondo:**  
   Es fundamental mejorar la legibilidad del contenido para asegurar que todos los usuarios, especialmente aquellos con discapacidades visuales, puedan acceder a la información.

2. **Imágenes sin Texto Alternativo:**  
   Agregar descripciones significativas a las imágenes es esencial para la inclusión de usuarios que dependen de tecnologías de asistencia.

3. **Formularios sin Etiquetas Descriptivas:**  
   Garantizar la correcta etiquetación de los formularios mejora significativamente la usabilidad y la accesibilidad para todos los usuarios.

Implementar estas soluciones no solo corregirá los errores más críticos, sino que también contribuirá a una experiencia web más inclusiva y satisfactoria para todos los usuarios en la web de Cantina Chichilo.

# Fase 5: Implementación para Alcanzar el Nivel Deseado

## Objetivo

Realizar las modificaciones necesarias en el código HTML/CSS para alcanzar el nivel AA de conformidad según las WCAG 2.1, tomando como base la web original ([Cantina Chichilo](http://www.cantinachichilo.com.ar)) y aplicando las mejoras en la versión modificada ([ProyectoAccesibilidad](https://imziki.github.io/ProyectoAccesibilidad/)).

## Comparativa de la Implementación

La versión mejorada del proyecto ha sido diseñada para solventar los problemas de accesibilidad detectados en la web original. A continuación, se presenta una comparativa siguiendo las áreas clave:

### 1. Contraste entre Texto y Fondo

**Web Original:**
- **Problema Detectado:**  
  Se identificaron problemas de contraste insuficiente, especialmente en secciones como "Promociones" y en bloques de texto sobre imágenes de fondo, lo que dificultaba la lectura para usuarios con baja visión.

**Web Mejorada:**
- **Implementación:**  
  Se han modificado los estilos CSS para mejorar la relación de contraste entre el texto y el fondo, utilizando combinaciones de colores que cumplen con el ratio mínimo exigido (4.5:1 para texto normal).
- **Resultado:**  
  La legibilidad ha mejorado significativamente, asegurando que el contenido sea perceptible para todos los usuarios.
  ![Captura de pantalla 2025-02-13 162723](https://github.com/user-attachments/assets/f9994234-212d-4e10-9cf6-62fd4ff978af)

---

### 2. Textos Alternativos en Imágenes y Elementos Multimedia

**Web Original:**
- **Problema Detectado:**  
  Muchas imágenes no contaban con atributos `alt` descriptivos, lo que impedía a los usuarios de tecnologías de asistencia comprender el contenido visual.

**Web Mejorada:**
- **Implementación:**  
  Se han añadido atributos `alt` a la mayoría de las imágenes, proporcionando descripciones contextuales y relevantes. Además, los elementos multimedia incluyen alternativas textuales cuando es necesario.
- **Resultado:**  
  Los usuarios que dependen de lectores de pantalla pueden acceder a la información visual de forma clara y completa.
  ![image](https://github.com/user-attachments/assets/e202af1a-f9b7-4d4a-861e-ee4de7ab42ab)

---

### 3. Formularios con Etiquetas Descriptivas

**Web Original:**
- **Problema Detectado:**  
  Los formularios carecían de etiquetas (`<label>`) correctamente asociadas a los campos de entrada, lo que generaba dificultades en la navegación e interpretación de los formularios por parte de usuarios con discapacidades.

**Web Mejorada:**
- **Implementación:**  
  Se han revisado y modificado todos los formularios para incluir etiquetas claras y descriptivas asociadas a cada campo de entrada mediante el atributo `for` vinculado al `id` correspondiente. También se han incorporado mensajes de error accesibles y ayudas contextuales.
- **Resultado:**  
  Los formularios son ahora intuitivos y accesibles, facilitando la interacción y reduciendo la posibilidad de errores durante su uso.
  ![Captura de pantalla 2025-02-13 162750](https://github.com/user-attachments/assets/cfd93f69-ace3-4698-b744-2dce2e767154)

---

### 4. Navegación Completa mediante Teclado

**Web Original:**
- **Problema Detectado:**  
  La navegación mediante teclado presentaba limitaciones, lo que afectaba la usabilidad para aquellos usuarios que no dependen del ratón.

**Web Mejorada:**
- **Implementación:**  
  Se ha optimizado la estructura de navegación para asegurar que todos los elementos interactivos sean accesibles mediante el teclado. Se han añadido atributos `tabindex` adecuados y se han implementado estilos de enfoque (focus) claros para resaltar los elementos activos.
- **Resultado:**  
  La navegación es fluida y completamente operable mediante teclado, garantizando una experiencia inclusiva para todos los usuarios.
  ![image](https://github.com/user-attachments/assets/9c806954-5cd4-4e6f-a2dd-12559fef1400)

---

## Conclusión

La versión modificada del proyecto ([ProyectoAccesibilidad](https://imziki.github.io/ProyectoAccesibilidad/)) demuestra mejoras significativas en comparación con la web original de Cantina Chichilo, cumpliendo con los siguientes puntos:

- **Mejora del Contraste:**  
  Se ha optimizado el contraste entre el texto y el fondo para cumplir con los requisitos del nivel AA.

- **Inclusión de Textos Alternativos:**  
  Las imágenes y elementos multimedia ahora cuentan con descripciones textuales que facilitan la comprensión del contenido visual.

- **Formularios Accesibles:**  
  Se han añadido etiquetas descriptivas y mensajes de error accesibles a todos los formularios.

- **Navegación por Teclado:**  
  La navegación se ha adaptado para ser completamente operable mediante teclado, asegurando la accesibilidad a usuarios que dependen de este método de interacción.

Estas modificaciones no solo permiten alcanzar el nivel AA de conformidad según las WCAG 2.1, sino que también mejoran la experiencia de usuario para un público más amplio, asegurando una mayor inclusión digital.

# Fase 6: Verificación mediante test externos
Análisis de la Categoría: Perceptible
=====================================
![Captura de pantalla 2025-02-13 163230](https://github.com/user-attachments/assets/4bb06e8c-f229-4286-8fc3-499cdfdaa5f6)

Resultados Destacados
---------------------

### Criterios Cumplidos (✓):

-   **1.3.1 - Información y relaciones (A):** La estructura semántica está correctamente implementada.

-   **1.4.1 - Uso del color (A):** Se verificó que el color no es el único medio para transmitir información.

-   **1.4.3 - Contraste Mínimo (A):** Se obtuvo una puntuación de 9.5 en contraste, cumpliendo los requisitos.

-   **1.3.3 - Características sensoriales (A):** Se han implementado alternativas textuales para evitar dependencia exclusiva de características sensoriales.

### Criterios No Aplicables (na):

-   **1.2.1 - Sólo audio/video (A)**

-   **1.2.2 - Subtítulos (A)**

-   **1.4.5 - Descripción auditiva (AA)**

-   **1.4.5 - Imágenes de texto (AA)**

**Justificación:** No hay contenido multimedia ni imágenes con texto en la web.

### Recomendaciones

-   Mantener el enfoque en accesibilidad semántica y alternativas textuales.

* * * * *

Análisis de la Categoría: Operable
==================================
![Captura de pantalla 2025-02-13 163235](https://github.com/user-attachments/assets/48b56d8c-8eb0-4af8-af3c-6f17facc06df)

Resultados Destacados
---------------------

### Criterios Cumplidos (✓):

-   **a.4.4 - Propósito de los enlaces (A):** Enlaces claramente identificables.

-   **a.1.1 - Teclado (A):** Navegación por teclado probada y funcionando correctamente.

-   **a.4.7 - Foco visible (AA):** El foco en los elementos interactivos es visible y correcto.

-   **a.4.5 - Múltiples vías (AA):** Existen varias formas de navegación en la web.

-   **a.4.2 - Títulos de página (A):** Se han ajustado los títulos para mayor claridad y coherencia.

### Recomendaciones

-   Seguir manteniendo una estructura clara en los títulos de página.

* * * * *

Análisis de la Categoría: Comprensible
======================================
![Captura de pantalla 2025-02-13 163239](https://github.com/user-attachments/assets/191bdca7-4e60-4f47-950b-1fed1027a9ad)

Resultados Destacados
---------------------

### Criterios Cumplidos (✓):

-   **3.1.1 - Idioma de la página (A):** Idioma principal definido.

-   **3.3.2 - Etiquetas o instrucciones (A):** Formularios con etiquetas adecuadas.

-   **3.3.1 - Identificación de errores (A):** Se han implementado mensajes claros de error en formularios.

-   **3.3.3 - Sugerencias ante errores (AA):** Se han añadido sugerencias para corrección de errores.

-   **3.2.3 - Navegación consistente (AA):** Se ha verificado la consistencia en la navegación.

### Recomendaciones

-   Realizar pruebas adicionales para mejorar aún más la experiencia del usuario.

* * * * *

Análisis de la Categoría: Robusto
=================================
![Captura de pantalla 2025-02-13 163245](https://github.com/user-attachments/assets/a5711357-2c20-492b-a4ac-dd5bff392f99)

Resultados Destacados
---------------------

### Criterios Cumplidos (✓):

-   **41:2 - Nombre, función, valor (A):** Compatibilidad con lectores de pantalla probada y funcionando correctamente.

-   **41:1 - Procesamiento (A):** Se han optimizado los elementos interactivos para mejorar la compatibilidad con tecnologías asistivas.

### Criterios No Aplicables (na):

-   **41:1 - Procesamiento (A):** No aplicable por falta de contenido dinámico.

### Recomendaciones

-   Continuar probando con diversas tecnologías asistivas para asegurar una experiencia óptima.

* * * * *

Conclusión General
==================

-   **Nivel A:** Cumplido con éxito.

-   **Nivel AA:** Alcanzado, con mejoras continuas para optimización.

**Acción prioritaria:** Seguir refinando la experiencia del usuario y la accesibilidad en base a pruebas y retroalimentación.

# Fase 7: Verificación Multiplataforma

## Sitio Evaluado
[imziki.github.io/ProyectoAccesibilidad](https://imziki.github.io/ProyectoAccesibilidad)

## Objetivo
Garantizar la funcionalidad del sitio web en diferentes navegadores, dispositivos y tecnologías asistivas.

---

## 1. Pruebas en Navegadores Modernos

- **Google Chrome:** ✅ El sitio se visualiza y funciona correctamente en la última versión de Chrome. Todos los elementos interactivos y de navegación operan sin inconvenientes.
- **Mozilla Firefox:** ✅ Compatibilidad completa con Firefox, con una experiencia de usuario fluida y sin errores.
- **Microsoft Edge:** ✅ Totalmente funcional en Edge, con una correcta representación de todos los componentes y una navegación eficiente.

---

## 2. Verificación en Dispositivos Móviles y Tabletas

- **Diseño Responsive:** ✅ Se ha probado en diversas resoluciones de pantalla, incluyendo smartphones y tabletas. La adaptación del diseño es adecuada, asegurando una experiencia de usuario óptima en dispositivos móviles.

---

## 3. Compatibilidad con Tecnologías Asistivas

- **Lectores de Pantalla:** ✅ Se realizaron pruebas utilizando Windows Narrator, confirmando que la audiodescripción de todo el contenido funciona correctamente. Los elementos interactivos y de navegación son accesibles y comprensibles para usuarios con discapacidades visuales.
- **Magnificadores de Pantalla:** ✅ El sitio es compatible con herramientas de aumento de pantalla, permitiendo que el contenido se visualice correctamente cuando se amplía, sin pérdida de calidad ni funcionalidad.

---

## Conclusión

La web **cumple con los estándares de accesibilidad y usabilidad en múltiples plataformas**. Las pruebas realizadas en navegadores modernos, dispositivos móviles y tecnologías asistivas han demostrado una funcionalidad y experiencia de usuario consistentes y satisfactorias.

---

## Recomendaciones

Aunque el sitio ha mostrado un alto nivel de compatibilidad y accesibilidad, se sugiere **realizar pruebas periódicas** y **mantener actualizadas las tecnologías utilizadas** para asegurar una experiencia óptima para todos los usuarios.

# Fase 8: SEO
### **SEO On-page**

Para mejorar la visibilidad de la página **imziki.github.io/ProyectoAccesibilidad** en los motores de búsqueda, se han implementado las siguientes prácticas de SEO On-page:

1.  **Etiquetas semánticas HTML5**:

    -   Se han utilizado etiquetas semánticas como `<header>`, `<main>`, `<footer>`, y `<article>` para estructurar adecuadamente el contenido de la web, lo que facilita a los motores de búsqueda entender la jerarquía y propósito del contenido.
2.  **Etiqueta `<title>`**:

    -   En cada página, se ha incluido una etiqueta `<title>` descriptiva que resume claramente el contenido de la página, lo que ayuda a los motores de búsqueda a identificar el tema principal.
3.  **Metaetiquetas**:

    -   Se ha configurado la etiqueta `<meta name="description">` para proporcionar una descripción clara y concisa del contenido de la página. Esta descripción puede aparecer como fragmento en los resultados de búsqueda, mejorando la tasa de clics.
        -   Ejemplo: `<meta name="description" content="Tienda online con las mejores ofertas en tecnología y gadgets." />`
    -   Aunque la etiqueta `<meta name="keywords">` es menos relevante para los motores de búsqueda modernos, se ha incluido para identificar las palabras clave relacionadas con el contenido.
    -   La etiqueta `<meta charset="UTF-8">` se ha añadido para asegurar que la codificación de caracteres sea correcta, evitando problemas de visualización del texto.
4.  **Encabezados jerárquicos**:

    -   Se ha utilizado la etiqueta `<h1>` para el título principal de la página y `<h2>`, `<h3>` para subsecciones, lo que mejora la estructura del contenido y facilita la lectura tanto para usuarios como para motores de búsqueda.
