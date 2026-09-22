# Mi portafolio personal (Proyecto Incremental)
## Evaluación de la unidad — HTML + CSS + GitHub (100 puntos totales)

> [!NOTE]
> **Enfoque Pedagógico: Habilidad de Autoaprendizaje y Adaptación**
> En el mundo profesional del desarrollo de software y diseño, la capacidad de adaptación y el autoaprendizaje son fundamentales. A menudo te asignarán tareas o tecnologías de las que no eres especialista. Tu trabajo consistirá en investigar y encontrar la solución. Por ello, este proyecto evalúa activamente tu habilidad para utilizar de forma autónoma las guías de estudio provistas y los recursos externos para resolver tus dudas.

---

# ¿Qué vamos a construir?

Un sitio web personal de **3 páginas** con un **contenedor central** como base de diseño:
- **Inicio (`index.html`):** Tarjeta de presentación.
- **Proyectos (`proyectos.html`):** 3 proyectos destacados.
- **Contacto (`contacto.html`):** Formulario de contacto.

**Tecnologías a utilizar:**
- HTML5 (Estructura y semántica)
- CSS3 (Estilos y Responsive Design)
- AOS (Librería de animaciones)
- Git / GitHub / GitHub Pages

---

# Requisitos generales para cada entrega

Para aprobar cada fase, el sitio debe cumplir obligatoriamente con:
- Estar subido a un repositorio público en **GitHub**.
- Estar publicado y funcionando mediante **GitHub Pages**. **Importante:** Se evaluará la versión del sitio correspondiente al **último deployment (publicación)** realizado antes de la fecha y hora límite de entrega.
- Tener un **mínimo de 3 commits nuevos** por entrega (mínimo 9 en total al final). **Importante:** Se revisará el **último commit a la fecha y hora de entrega**.
- **Configurar visualización de publicaciones:** Debes activar la opción **"Deployments"** en el panel de detalles del repositorio en GitHub (sección *About* -> Haz clic en el engranaje ⚙️ -> marca la opción *Deployments* bajo *Include in the home page* -> *Save changes*). Esto es indispensable para auditar tu historial de publicaciones.
- Presentar rutas relativas y enlaces completamente funcionales.
- Mantener los archivos ordenados (directorios `/css` e `/img`).

> [!IMPORTANT]
> **Uso de Inteligencia Artificial (IA) como asistente:** Se permite usar herramientas de IA como apoyo para resolver dudas puntuales o aprender a implementar elementos específicos (por ejemplo, preguntar *"¿cómo colocar un enlace?"* y seguir las instrucciones de la IA paso a paso). **Sin embargo, no puedes pedirle a la IA que construya todo tu proyecto**. La profesora lo notará rápidamente al evaluar tu código y al pedirte explicaciones de lo que construiste.

---

# Fases del proyecto

El proyecto se desarrolla y evalúa en 3 fases incrementales. Puedes consultar el calendario completo con los plazos oficiales vigentes en la [Guía de Fechas de Entrega](documentacion/fechas_entrega.md):

| Fase | Entrega | Puntaje | Guía Detallada |
|:---|:---|:---:|:---|
| **Formativa 01** | Página de inicio (`index.html`) con tarjeta de presentación | **30 pts** | [Ver Guía Formativa 01](documentacion/guia_formativa_01.md) |
| **Formativa 02** | Navegación completa y páginas de Proyectos y Contacto | **30 pts** | [Ver Guía Formativa 02](documentacion/guia_formativa_02.md) |
| **Parcial (Final)** | Optimización semántica, Responsive Design, Efectos especiales con AOS o CSS | **40 pts** | [Ver Guía Parcial 01](documentacion/guia_parcial_01.md) |
| **Total** | | **100 pts** | |


---

# 📘 ¿Cómo documentar tu Autoaprendizaje?

Para obtener el puntaje completo en el criterio de **Autoaprendizaje y Adaptación** en tus entregas, debes demostrar cómo superaste de forma autónoma tus dudas o desafíos técnicos:

1. **Comentarios en tu código:** Escribe comentarios breves indicando qué guías o recursos te ayudaron a implementar una sección.
   * *Ejemplo HTML:* `<!-- Solucionado con la guía de HTML/CSS: Atributos obligatorios de formulario -->`
   * *Ejemplo CSS:* `/* Aplicado desde guia_diseno.md: Regla de color 60-30-10 para la jerarquía visual */`
2. **Registro de desafíos (Bitácora):** Agrega una sección llamada `## 🛠️ Desafíos y Autoaprendizaje` en tu propio repositorio (en el pie de tu index o en una bitácora) respondiendo brevemente a:
   * **El problema:** ¿Qué error tenías o qué no sabías cómo hacer?
   * **La investigación:** ¿Qué guía de estudio (`guia_diseno.md`, `guia_git.md`, `guia_html_css.md`, `guia_ia.md`), tutorial o documentación oficial consultaste?
   * **La solución:** ¿Cómo lo resolviste finalmente?

---

# Fase 1: Formativa 01 — Mi primera página (30 pts)

### ¿Qué se debe entregar?
* **Estructura HTML5:** Documento base bien organizado.
* **Tarjeta de presentación central:**
  * Foto o avatar.
  * Nombre y descripción personal/profesional.
  * Área de especialidad o intereses.
  * Mínimo 2 enlaces funcionales (ej. redes sociales).
* **CSS básico:** Diseño personalizado centrado, libre elección de colores y tipografía.

---

# Rúbrica Formativa 01 (30 pts)

| Criterio | Logro completo | Logro parcial | Logro insuficiente | Máx |
| :--- | :--- | :--- | :--- | :---: |
| **Estructura HTML** | HTML5 estructurado de forma ordenada y correcta. | Errores menores en etiquetas o anidación. | Incompleto o desorganizado. | **6** |
| **Card de presentación** | Contenedor centralizado con avatar, descripción e intereses. | Faltan campos en la tarjeta de presentación. | Tarjeta incompleta o no centrada. | **6** |
| **CSS y diseño** | CSS externo aplicando pautas de color y contraste de la `guia_diseno.md`. | Personalización limitada o sin seguir las pautas de color/contraste. | CSS ausente o mal vinculado. | **6** |
| **Git & GitHub** | Mínimo 3 commits descriptivos aplicando pautas de la `guia_git.md`. | Commits con mensajes poco claros o menos de 3. | Sin historial de avance en Git. | **4** |
| **GitHub Pages** | Publicado y accesible mediante URL funcional. | Cargado pero con errores de ruta o archivos. | No publicado o inaccesible. | **3** |
| **Autoaprendizaje** | Resuelve un desafío técnico y documenta su proceso de búsqueda y solución (en código o bitácora). | Resuelve problemas autónomamente pero no documenta el proceso. | Depende enteramente de clases; no evidencia uso de guías. | **5** |

---

# Fase 2: Formativa 02 — Mi sitio personal (30 pts)

### ¿Qué se debe entregar?
* **Navegación común:** Enlace fluido entre Inicio, Proyectos y Contacto (sin rutas rotas).
* **Página de Proyectos (`proyectos.html`):** 3 proyectos con nombre, descripción e imagen.
* **Página de Contacto (`contacto.html`):** Formulario funcional visualmente con `label`, `input`, `textarea`, botones y atributos (`required`, tipos correctos).
* **Consistencia visual:** Estilos, colores y tipografías coherentes entre las 3 páginas.

---

# Rúbrica Formativa 02 (30 pts)

| Criterio | Logro completo | Logro parcial | Logro insuficiente | Máx |
| :--- | :--- | :--- | :--- | :---: |
| **Navegación** | 3 páginas conectadas perfectamente mediante menú común. | Errores de consistencia o enlaces rotos. | Sin navegación funcional. | **4** |
| **Proyectos** | 3 proyectos estructurados con texto e imagen según guías. | Faltan elementos, descripciones o imágenes rotas. | Página ausente o muy incompleta. | **5** |
| **Contacto** | Formulario completo con atributos avanzados (`required`, tipos correctos). | Faltan campos clave, etiquetas o atributos de validación. | Formulario no estructurado. | **5** |
| **Consistencia** | Estilos, colores y tipografías coherentes en las 3 páginas. | Inconsistencias visuales marcadas entre páginas. | Diseños totalmente no relacionados. | **4** |
| **Git & GitHub** | Mínimo 3 nuevos commits descriptivos del avance. | Commits insuficientes o sin descripciones claras. | Sin commits correspondientes a esta fase. | **4** |
| **Publicación** | Todo funcional y actualizado en GitHub Pages. | Errores menores de carga en assets (imágenes, CSS). | No publicado en la web. | **3** |
| **Autoaprendizaje** | Investiga y aplica autónomamente soluciones para maquetación o validación basándose en las guías y tutoriales. | Aplica soluciones pero no documenta qué guías o recursos utilizó. | No demuestra resolución autónoma de problemas técnicos. | **5** |

---

# Fase 3: Parcial — Sitio web final (40 pts)

### ¿Qué se debe entregar?
* **HTML Semántico:** Uso de `header`, `nav`, `main`, `section`, `article`, y `footer`.
* **CSS y Responsive:** El contenedor central debe adaptarse a desktop y mobile sin scroll horizontal ni textos cortados.
* **Interactividad CSS:** Estados hover en enlaces y botones.
* **Librería AOS:** Incorporación y funcionamiento de animaciones en al menos 3 elementos.
* **Proceso y calidad:** Aplicación de mejoras según feedback anterior, imágenes con atributo `alt` y estructura de carpetas limpia.

---

# Rúbrica Parcial (40 pts)

| Criterio | Logro completo | Logro parcial | Logro insuficiente | Máx |
| :--- | :--- | :--- | :--- | :---: |
| **Estructura HTML** | HTML5 semántico (`header`, `nav`, `main`, `footer`) y bien organizado. | Errores de semántica o estructuración. | Errores semánticos graves o ausencia de etiquetas HTML5. | **6** |
| **CSS y presentación** | Diseño coherente, personalizado, pulido y limpio. | Inconsistencias visuales menores o estilos descuidados. | CSS incompleto o mal estructurado. | **4** |
| **Funcionamiento** | Enlaces funcionales, imágenes con `alt` y formulario validado. | Errores menores en rutas o carga de assets. | Errores graves de navegación o enlaces rotos. | **5** |
| **Responsive** | Se adapta a móviles y escritorios sin scroll horizontal ni textos cortados. | Problemas menores de adaptación en resoluciones específicas. | No adaptado / se rompe en vistas móviles. | **5** |
| **Librería AOS** | Integración y personalización autónoma de AOS en al menos 3 elementos. | Implementación con errores menores de sincronización o sobrecargada. | AOS no implementado o no funciona. | **4** |
| **Mejoras aplicadas** | Implementa mejoras según feedback previo y las sugerencias de las guías de estudio. | Pocas mejoras o correcciones aplicadas. | Ignora el feedback anterior y las guías. | **4** |
| **Git y proceso** | Mínimo 3 nuevos commits descriptivos (mínimo 9 en todo el proceso). | Commits escasos o mensajes genéricos. | Sin historial estructurado de avance en Git. | **3** |
| **Publicación** | Publicación final impecable en GitHub Pages. | Errores menores de carga remota de recursos. | Inaccesible en línea. | **3** |
| **Autoaprendizaje y Documentación** | Documenta formalmente en el README o bitácora cómo investigó y resolvió de forma autónoma los desafíos de diseño responsivo o librerías externas. | Documenta superficialmente sus hallazgos y fuentes. | No evidencia aprendizaje autónomo ni documenta su proceso. | **6** |

---

# Checklist antes de la entrega final

- [x] ¿El menú de navegación conecta correctamente las 3 páginas?
- [x] ¿El sitio funciona y se lee bien en celulares (sin scroll horizontal)?
- [x] ¿Se usó HTML semántico (`header`, `nav`, `main`, `section`, `article`, `footer`)?
- [x] ¿Las imágenes tienen atributo `alt` y se cargan correctamente?
- [x] ¿El formulario de contacto tiene `label` e inputs apropiados?
- [x] ¿Incorporaste animaciones AOS en al menos 3 elementos?
- [x] ¿Tienes al menos 9 commits en total (mínimo 3 nuevos por fase)?
- [x] ¿Está publicado y actualizado en GitHub Pages?
- [x] ¿Activaste la opción **"Deployments"** en la configuración de **"About"** en tu repositorio de GitHub (haciendo clic en el engranaje ⚙️) para permitir a la profesora ver tu historial de publicación?

---

## 🛠️ Desafíos y Autoaprendizaje (Bitácora de Entrega Parcial 01)

Como parte de los requisitos de evaluación y desarrollo autónomo, a continuación se documentan los principales retos técnicos enfrentados durante la construcción y optimización final del portafolio:

### 1. Integración y Sincronización de la Librería de Animaciones AOS (Animate On Scroll)
* **El problema:** Para la entrega parcial era obligatorio incorporar dinamismo y efectos visuales modernos mediante una librería externa sin sobrecargar la experiencia del usuario. Además, en pruebas iniciales en dispositivos móviles, algunas animaciones con traslación lateral (`fade-right` / `fade-left`) producían una barra de desplazamiento horizontal momentánea durante la carga.
* **La investigación:** Se consultó la [Guía Parcial 01](documentacion/guia_parcial_01.md) y la documentación oficial de [AOS en GitHub (michalsnik/aos)](https://github.com/michalsnik/aos). Se investigaron las propiedades de inicialización como `duration`, `once` y el manejo de desbordes con CSS.
* **La solución:** Se vincularon los recursos CDN oficiales de AOS (`aos.css` en `<head>` y `aos.js` al pie del `<body>`). Se inicializó la librería con `{ duration: 800, once: true }` para asegurar que las animaciones ocurran de manera fluida y una sola vez por visualización. Para eliminar cualquier riesgo de scroll horizontal en celulares, se aplicó `overflow-x: hidden` a las etiquetas `html` y `body` en `css/style.css`. Por último, se configuraron efectos personalizados como `zoom-in` para el avatar, `fade-down` para encabezados y `fade-up` con atributos `data-aos-delay` escalonados (100ms, 200ms, 300ms) en las tarjetas de proyectos y canales de contacto.

### 2. Diseño Responsivo Adaptable (Mobile-First) y Eliminación de Scroll Horizontal
* **El problema:** En pantallas de smartphones pequeños (menos de 400px de ancho), las tarjetas anchas de proyectos y el layout de dos columnas de la página de contacto quedaban comprimidos o podían desbordar el contenedor principal si no se gestionaban adecuadamente los anchos y márgenes.
* **La investigación:** Se repasaron las directrices de diseño responsivo de la [Guía HTML y CSS](documentacion/guias_estudio/guia_html_css.md), la [Guía de Diseño](documentacion/guias_estudio/guia_diseno.md) y las recomendaciones de herramientas de inspección como Responsively App.
* **La solución:** Se diseñó un sistema de medios (`@media (max-width: 768px)`) que adapta el contenedor principal `.card` al `95%` de la pantalla con un padding ergonómico de `24px 18px`. En la página de proyectos, se reorganizó la tarjeta mediante `flex-direction: column-reverse` para que la imagen se ubique arriba del contenido textual y se adapte al 100% del ancho. En la página de contacto, el grid de dos columnas se transformó a `grid-template-columns: 1fr`, priorizando la tarjeta de contacto directo con `order: -1` para que el visitante pueda contactar de inmediato en móvil. Se aplicó una regla universal `img { max-width: 100%; height: auto; }` para asegurar que ningún recurso visual se desborde.

### 3. Reestructuración a HTML5 Semántico y Accesibilidad Web
* **El problema:** Gran parte del maquetado dependía de contenedores genéricos (`<div>`), lo cual no cumplía con los estándares de la pauta respecto al significado estructural del código y la accesibilidad para lectores de pantalla. Asimismo, ninguna de las páginas contaba con un pie de página (`footer`) formal.
* **La investigación:** Se estudió la sección de Maquetación Semántica de la [Guía Parcial 01](documentacion/guia_parcial_01.md), verificando la función específica de cada etiqueta: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`.
* **La solución:** Se reestructuraron las tres páginas del sitio:
  * `<header class="main-header">` para albergar la barra de navegación `<nav>`.
  * `<main class="card">` como contenedor principal semántico del contenido central.
  * `<section>` para agrupar áreas lógicas (biografía, redes sociales, lista de proyectos y formulario).
  * `<article class="project-row">` para cada proyecto individual de Canva.
  * `<footer class="card-footer">` al final de la tarjeta de cada página para mostrar los créditos y derechos de autor de Yanipsia Adasme.
  * Se verificó que todas las imágenes incluyan descripciones precisas en el atributo `alt` y que los enlaces que abren nuevas pestañas posean `rel="noopener noreferrer"`.

