# 📚 Estudio de Roles Básicos en Desarrollo Web y Móvil

##  Recurso Usen el Link odicial para aprender git /github Todos 
https://docs.github.com/es/get-started/start-your-journey/git-and-github-learning-resources
## 0) Integrantes del equipo de estudio y sus responsabilidades en el repositorio:


1. Linares Taco Viviana Flobele - vlinares@unsa.edu.pe - Desarrollador Frontend
2. Mendoza Larico Delaney Dariana - dmendozala@unsa.edu.pe - Desarrollador Frontend
3. Martel Gallegos Alexandra - amartelg@unsa.edu.pe - Desarrollador Android
4. Motta Medina, Brayan Teodoro - bmottam@unsa.edu.pe - Desarrollador Backend
5. Molina soncco, Percy - pmolinaso@unsa.edu.pe - Desarrollador QA Assurance
6. Mendoza Taco David Jose Luis  - dmendozat@unsa.edu.pe - Desarrollador Backend
7. Quispe Balcon Martha Beatriz - mquispebal@unsa.edu.pe - Desarrolador Android
8. Salas Zegarra, Marco Antonio - msalasze@unsa.edu.pe - Desarrollador QA
9. Valdivia Flores Manuel Djins - mvaldiviaf@unsa.edu.pe - Desarrollador Backend
10. Cruz Kana Pamela Greis - pcruzk@unsa.edu.pe - Desarrollador Android
11. Choquecota Pandia Mario Miguel - mchoquecota@unsa.edu.pe - Desarrollador QA
12. Velo Poma Yamira Yesica - yvelo@unsa.edu.pe - Desarrollador Frontend

## 1) Conceptos Generales para tener en cuenta
Cuando desarrollamos aplicaciones, ya sea para web o dispositivos móviles, usamos distintas herramientas que nos ayudan a trabajar más rápido y con mejor estructura. Entre estas herramientas están las librerías, los frameworks y los patrones de diseño, y aunque a veces se confunden, en realidad son cosas distintas.

##  ¿Qué es una Librería?

Una **librería** es como una caja de herramientas: ya viene con funciones listas que puedes usar cuando las necesites. Tú decides en qué momento y cómo las usas dentro de tu código.

- **Ejemplos en web:** jQuery (para manejar el DOM), Axios (para hacer peticiones HTTP).
- **Ejemplos en apps móviles:** Glide (para cargar imágenes en Android), Alamofire (para redes en iOS).

En resumen: una librería te ayuda con tareas puntuales, pero tú tienes el control de todo lo demás.

---

##  ¿Qué es un Framework?

Un **framework** es más grande que una librería. Es como si te dieran una base ya construida y tú tuvieras que seguir ciertas reglas para completar el resto. Aquí el que manda es el framework, porque ya viene con una estructura que tú tienes que respetar.

- **Ejemplos en web:** Angular, Vue, React (aunque muchos lo consideran librería, se usa como framework).
- **Ejemplos en móvil:** Flutter, React Native.

En resumen: el framework te guía paso a paso para que sigas su forma de trabajar. Es más completo, pero también más estricto.

---

##  ¿Qué son los Patrones de Diseño?

Los **patrones de diseño** no son código listo para usar, sino formas recomendadas de organizar tu programa para que sea más ordenado y fácil de mantener. Son soluciones a problemas que pasan muy seguido en la programación.

**Ejemplos comunes:**
- MVC (Modelo - Vista - Controlador)
- Singleton (una sola instancia de algo)
- Observer (algo se actualiza cuando otra cosa cambia)
- MVVM (usado en apps móviles con interfaces reactivas)

En resumen: los patrones te dan ideas de cómo organizar mejor tu código para que sea claro y escalable.

---

##  Diferencias

| Concepto           | ¿Quién controla el flujo? | ¿Para qué sirve?                   | Ejemplos Web        | Ejemplos Móvil       |
|--------------------|----------------------------|------------------------------------|---------------------|----------------------|
| **Librería**        | Tú, el programador         | Funciones específicas              | jQuery, Axios       | Glide, Alamofire     |
| **Framework**       | El framework               | Base para crear toda la app        | Angular, Vue, React | Flutter, React Native|
| **Patrón de diseño**| No aplica                  | Buena organización del código      | MVC, Singleton      | MVVM, Observer       |

---

##  Conclusión

Saber diferenciar entre **librerías**, **frameworks** y **patrones de diseño** es clave si queremos trabajar de forma eficiente y ordenada.  
Cada uno cumple una función distinta, y dependiendo del tipo de proyecto, nos conviene usar uno u otro.  
Esta base nos ayuda a tomar mejores decisiones como desarrolladores.

## 2) Conociendo Git
Git es una herramienta fundamental en el desarrollo de software que actúa como un sistema de control de versiones distribuido. A nivel local, Git nos permite mantener un historial completo de cada cambio que realizamos en nuestro código, incluso sin necesidad de estar conectados a un repositorio remoto (como GitHub o GitLab).
- **Seguimiento de Cambios (Versioning)**
  - Registro Histórico: Cada vez que "comiteamos" (commit) nuestros cambios, Git guarda una instantánea del proyecto en ese momento. Esto crea un registro inmutable de la evolución de nuestro código.
Cada commit incluye metadatos como el autor del cambio, la fecha y hora, y un mensaje descriptivo que explica qué se hizo. Esto es crucial para entender el desarrollo del proyecto.
- **Rastreo y Reversión de Modificaciones**
  - Podemos ver exactamente qué líneas de código se han añadido, modificado o eliminado entre cualquier versión (commit).
  - Si introducimos un error o una funcionalidad que no funciona, podemos revertir el proyecto a un estado anterior (a cualquier commit pasado) de forma segura y sencilla, sin perder el trabajo intermedio.
- **Gestión de Ramas (Branching)**
  - Git nos permite crear "ramas" (branches) locales. Una rama es una copia aislada de nuestro proyecto en un punto específico. Esto es ideal para desarrollar nuevas características o probar ideas sin afectar la rama principal (generalmente main o master).
  - Una vez que una rama de trabajo está lista y probada, podemos fusionar (merge) sus cambios de vuelta a la rama principal.
- **Colaboración Individual (Preparación para el Entorno Remoto)**
  - Aunque el uso de repositorios remotos es para la colaboración en equipo, tener un dominio sólido de Git localmente es el primer paso. Nos prepara para subir nuestros cambios, sincronizarnos con otros y resolver conflictos cuando trabajamos en equipo.

## 3) Conociendo GitHub
GitHub es una plataforma que permite trabajar de forma colaborativa utilizando Git, un sistema de control de versiones distribuido. Su uso es fundamental cuando varios integrantes de un equipo están desarrollando un mismo proyecto, ya que permite mantener el código organizado, documentado y con historial de cambios.

---

###  Uso del repositorio remoto

Un **repositorio remoto** es una copia del proyecto almacenada en línea (por ejemplo, en GitHub), que todos los integrantes del equipo pueden consultar, modificar o actualizar desde sus computadoras. Permite sincronizar el trabajo entre todos los miembros, compartir avances y evitar pérdidas de información.

Gracias al repositorio remoto, los desarrolladores pueden subir sus cambios con `git push`, descargar los cambios de otros con `git pull`, y mantener una versión centralizada del proyecto que refleje el estado más reciente.

---

###  ¿Cómo definimos un repositorio?

Un **repositorio** es el lugar donde se almacena todo el contenido de un proyecto: archivos, carpetas, imágenes, documentación y todo el historial de versiones. Es como una carpeta inteligente que no solo guarda archivos, sino que también recuerda cada cambio que se hizo, cuándo se hizo y quién lo hizo.

En GitHub, un repositorio puede ser:
- **Público:** cualquier persona puede verlo.
- **Privado:** solo los miembros autorizados tienen acceso.

---

###  ¿Cómo configurarlo para trabajar en equipo?

Para permitir que un grupo de personas trabaje en un mismo proyecto usando GitHub, se deben seguir algunos pasos importantes:

1. **Crear el repositorio remoto** en GitHub.
2. **Invitar a los colaboradores** al repositorio desde la configuración.
3. **Asignar roles** según el nivel de permisos (lectura, escritura o administrador).
4. **Trabajar con ramas (branches)** para que cada integrante realice sus aportes sin afectar directamente el código principal.
5. **Usar Pull Requests**, que permiten revisar y aprobar los cambios antes de integrarlos al proyecto principal.
6. **Establecer una convención de commits**, para mantener claridad en los cambios realizados.

Esta configuración permite que el trabajo del equipo sea ordenado, controlado y colaborativo.

---

###  Supervisión de posibles conflictos:

Cuando varias personas trabajan al mismo tiempo sobre el mismo archivo, es posible que se generen **conflictos** al momento de unir los cambios. Esto sucede si dos personas modifican la misma línea de código o archivo y luego intentan subir sus versiones.

Para evitar y manejar conflictos, se recomienda:

- Hacer `git pull` frecuentemente para mantenerse actualizado con los cambios del equipo.
- Dividir bien las tareas, para que no haya dos personas trabajando en lo mismo al mismo tiempo.
- Utilizar ramas separadas por cada funcionalidad o módulo.
- Resolver conflictos manualmente si ocurren, eligiendo qué parte del código conservar.

Supervisar y resolver estos conflictos a tiempo es clave para evitar errores en el proyecto y asegurar que el equipo trabaje de forma fluida.


### Temas a desarrollar por los miembros del Equipo:  
**Roles básicos en el desarrollo de aplicaciones web y aplicación móvil**

## 4) Desarrollador Frontend
☞ ¿De que se encarga?
- Crea interfaces atractivas y responsivas (adaptables a distintos dispositivos), garantizar una buena experiencia de usuario (UX/UI), conectar con el backend mediante APIs para mostrar datos dinámicos, y optimizar el rendimiento y accesibilidad de la web.
☞ Habilidades Requeridas: 
- Se requiere conocimientos HTML5, CSS3, JavaScript (ES6+), React, Git, Responsive Design, APIs REST, Webpack, TypeScript, Testing (Jest/Cypress), Accesibilidad (WCAG).
  
■ Relación con Backend (datos):

   El Frontend consume APIs (REST/GraphQL) proporcionadas por el Backend para mostrar datos dinámicos.
  
   Ambos deben coordinarse en:
  
   ➤ Estructura de datos (JSON/XML).
  
   ➤ Autenticación (JWT, OAuth).
  
   ➤ WebSockets (para comunicación en tiempo real).
  
■ Relación con Android (experiencia móvil, si es un equipo multi-plataforma):

  ➤ Si el equipo desarrolla una aplicación híbrida.
   
  ➤ El Frontend y el Android pueden trabajar con el mismo código.
   
  ➤ En proyectos separados (web + app nativa), ambos deben mantener consistencia en UX/UI (mismos colores, flujos, etc.).
   
■ Relación con QA (calidad y coherencia):

  ➤ Prueba la interfaz del Frontend (web) en busca de errores:
   
  ➤ Funcionales: Botones que no responden, formularios rotos.
   
  ➤ Rendimiento: Lentitud al cargar datos desde el Backend.
   
☞ Stack tecnológico:  

⍟ Lenguajes Base:

   ⮡ HTML5 (Estructura).
   
   ⮡ CSS3 (Estilos) + Sass/Less (Preprocesadores).
   
   ⮡ JavaScript (Lógica) + TypeScript (Tipado estático).

⍟ Frameworks/Librerías Principales:

   ⮡ React.js (Meta) + Next.js (SSR/SSG).
   
   ⮡ Vue.js + Nuxt.js.
   
   ⮡ Angular (Google, para aplicaciones empresariales).
   
   ⮡ Svelte/SvelteKit (En auge por su enfoque sin Virtual DOM).

⍟ Gestión de Estado:

   ⮡ Redux (React) / Pinia (Vue) / NgRx (Angular).
   
   ⮡ Context API (React) / Zustand (Alternativa ligera a Redux).

⍟ Estilización:

   ⮡ Tailwind CSS (Utility-first) / CSS Modules.
   
   ⮡ Styled Components (CSS-in-JS).
   
   ⮡ Bootstrap/Material UI (Componentes preconstruidos).

⍟ Herramientas de Desarrollo:

   ⮡ Vite (Bundler rápido, alternativa a Webpack).
   
   ⮡ npm/yarn/pnpm (Gestión de paquetes).
   
   ⮡ ESLint/Prettier (Linting y formateo).

⍟ Testing:

   ⮡ Jest (Unit testing).
   
   ⮡ Cypress/Playwright (E2E testing).
   
   ⮡ React Testing Library (Para componentes React).

## 5) Links recomendados para capacitación Rol Frontend
*(Separados por criterios)*  
🔹 **Sin certificaciones**:  
- MDN Web Docs: La referencia oficial para HTML, CSS, JavaScript. Imprescindible. https://developer.mozilla.org/en-US/docs/Web

- freeCodeCamp: Cursos interactivos y proyectos prácticos. https://www.freecodecamp.org/

- The Odin Project: Currículo completo y basado en proyectos. https://www.theodinproject.com/

- CSS-Tricks: Blog y recursos detallados sobre CSS y web. https://css-tricks.com/

- JavaScript.info: Tutorial exhaustivo de JavaScript. https://javascript.info/
    
🔹 **Con certificación**:  
- Coursera: Cursos y especializaciones de universidades/empresas (ej: Meta Front-End Developer). https://www.coursera.org/

- edX: Cursos de universidades de prestigio (ej: CS50 Web Programming). https://www.edx.org/

- Udemy: Amplia variedad de cursos individuales (busca los mejor valorados). https://www.udemy.com/

- Platzi: Rutas de aprendizaje completas (Escuela de Desarrollo Web, JavaScript, React.js). https://platzi.com/
    
🔹 **Proyectos completos de ejemplo**:  
- Frontend Mentor: Desafíos de diseño para codificar. https://www.frontendmentor.io/

- GreatFrontEnd: Colección de desafíos de codificación y preguntas de entrevista. https://www.greatfrontend.com/

- GitHub: Explora repositorios con proyectos ("awesome-frontend", "react-projects"). https://github.com/

- CodePen: Entorno online para prototipar y compartir código. https://codepen.io/

🔹 **Recomendadas por líderes (Microsoft, AWS, Google)**:  
- Google Developers (web.dev): Guías de rendimiento web y herramientas. https://web.dev/

- Microsoft Learn: Rutas de aprendizaje sobre HTML, CSS, JS, React, Angular. https://learn.microsoft.com/en-us/

- AWS Amplify Docs: Tutoriales para integrar Frontend con la nube. https://aws.amazon.com/amplify/

- React.dev (Meta): Documentación oficial del framework React. https://react.dev/

## 6) Desarrollador Backend
💡 ¿Qué es el Backend?
El backend es la parte del desarrollo web que gestiona la lógica, bases de datos y servidores. Es lo que el usuario no ve, pero permite que todo funcione correctamente en una aplicación o sitio web.

Por ejemplo, cuando haces login en una página, el backend valida tus credenciales, accede a la base de datos y devuelve una respuesta al frontend.

🧱 Componentes del Backend
Servidor: Máquina (física o en la nube) que ejecuta la lógica del sistema.

Aplicación backend: Código que maneja la lógica de negocio (por ejemplo: Node.js, Java, Python).

Base de datos: Sistema para almacenar datos persistentes (MySQL, MongoDB, PostgreSQL).

API: Interfaz para que otras aplicaciones (por ejemplo, el frontend) se comuniquen con el backend.

Autenticación y autorización: Controlan el acceso de los usuarios a los recursos.

🛠️ Tecnologías Backend populares
Lenguajes de programación:
JavaScript (Node.js)

Python (Django, Flask)

Java (Spring Boot)

PHP (Laravel, Symfony)

Ruby (Ruby on Rails)

Go y Rust (más modernos, usados en microservicios)

Bases de datos:
Relacionales: MySQL, PostgreSQL, SQLite

NoSQL: MongoDB, Redis, Cassandra

Frameworks:
Node.js con Express.js

Django (Python)

Spring Boot (Java)

Laravel (PHP)

FastAPI (Python, muy rápido y moderno)

Herramientas DevOps (usadas en backend):
Docker, Kubernetes, Nginx

CI/CD: Jenkins, GitHub Actions

Control de versiones: Git

📡 ¿Qué hace un desarrollador Backend?
Un desarrollador backend:

Diseña la estructura de datos y modelos.

Crea API RESTful o GraphQL.

Implementa lógica del negocio.

Administra bases de datos.

Asegura seguridad y autenticación.

Optimiza el rendimiento del servidor.

Colabora con frontend y DevOps.

🔐 Temas importantes en backend
Autenticación (JWT, OAuth2, sesiones)

Autorización de roles

Manejo de errores y excepciones

Pruebas (unitarias y de integración)

Manejo de archivos

Sockets y WebSockets (para tiempo real)

Trabajo con colas (RabbitMQ, Kafka)

Middlewares

Seguridad: CORS, XSS, CSRF, encriptación

🧩 Arquitecturas comunes
Monolítica: Todo el backend en un solo sistema.

Microservicios: El backend se divide en pequeños servicios independientes.

Serverless: Código backend que corre bajo demanda (ej: AWS Lambda).

MVC (Modelo-Vista-Controlador): Patrón común para estructurar el código.

🌐 Backend y APIs
El backend generalmente expone una API para que el frontend o clientes móviles puedan hacer peticiones HTTP (GET, POST, PUT, DELETE). Por ejemplo:

h
Copiar
Editar
GET /api/users
POST /api/login
📈 Salidas profesionales
Con conocimientos de backend puedes trabajar como:

Backend Developer

Full Stack Developer

DevOps Engineer (si aprendes despliegue)

Cloud Engineer

Arquitecto de Software

🧪 Recomendaciones para aprender backend
Aprende un lenguaje base: JavaScript (Node.js) o Python son ideales para empezar.

Usa un framework popular: Express.js, Django, Laravel, etc.

Conecta con una base de datos (MySQL o MongoDB).

Crea un API RESTful simple.

Aprende sobre autenticación con JWT o sesiones.

Prueba tu API con Postman o curl.

Sube tu app a la nube (Heroku, Vercel, Render, AWS).

## 7) Links recomendados para capacitación Rol Backend
🔹 Sin certificaciones (gratuitos, prácticos)
freeCodeCamp (APIs y microservicios)
https://www.freecodecamp.org/learn/back-end-development-and-apis/

MDN Web Docs (HTTP, servidores, etc.)
https://developer.mozilla.org/en-US/docs/Web/HTTP

Backend Developer Roadmap
https://roadmap.sh/backend

Node.js Tutorial
https://nodejs.dev/en/learn/

🔹 Con certificación
Coursera (Meta, IBM, etc.)
https://www.coursera.org/

edX (Harvard, MIT, etc.)
https://www.edx.org/learn/backend-development

Udemy – Cursos como Node.js, Java Spring Boot, Django
https://www.udemy.com/

🔹 Proyectos completos de ejemplo
Node.js Bootcamp (GitHub)
https://github.com/Mohammed-Taysser/Nodejs-Bootcamp

The Odin Project – Backend Node.js
https://www.theodinproject.com/paths/full-stack-javascript

App Ideas Collection (para portafolio)
https://github.com/florinpop17/app-ideas

🔹 Recomendadas por líderes (Microsoft, AWS, Google)
Microsoft Learn (C#, .NET, Azure)
https://learn.microsoft.com/en-us/training/

AWS Backend con Serverless & Lambda
https://explore.skillbuilder.aws/

Google Cloud Skills Boost (Backends escalables)
https://www.cloudskillsboost.google/



## 8) Rol QA
**QA** o **Quality Assurance** (Aseguramiento de la Calidad) es una disciplina fundamental en el desarrollo de software que se encarga de garantizar que los productos cumplan con los estándares de calidad establecidos antes de llegar al usuario final.
### ¿Qué hace un QA?

Un profesional de QA actúa como el **guardián de la calidad**, siendo responsable de identificar defectos, inconsistencias y problemas de usabilidad en aplicaciones, sistemas web, móviles o software en general. Su trabajo va más allá de simplemente "encontrar bugs"; se trata de asegurar que el producto funcione correctamente bajo diferentes condiciones y escenarios.

### Responsabilidades Principales

**Planificación de Pruebas:** Diseña estrategias de testing basadas en los requisitos del proyecto, creando casos de prueba detallados que cubran diferentes funcionalidades y escenarios de uso.

**Ejecución de Pruebas:** Realiza pruebas manuales y automatizadas, verificando que cada componente del software opere según lo esperado. Esto incluye pruebas funcionales, de rendimiento, de seguridad y de usabilidad.

**Documentación:** Registra detalladamente los defectos encontrados, proporcionando información precisa sobre cómo reproducir los problemas para facilitar su corrección por parte del equipo de desarrollo.

**Colaboración Cross-funcional:** Trabaja estrechamente con desarrolladores, product managers y diseñadores para comprender los requisitos y asegurar que se implementen correctamente.
### Tipos de Pruebas que Realiza

El QA maneja diferentes niveles de testing: pruebas unitarias (componentes individuales), pruebas de integración (interacción entre módulos), pruebas de sistema (funcionalidad completa) y pruebas de aceptación (validación final con criterios de negocio).
También se especializa en pruebas específicas como testing de APIs, pruebas de regresión para verificar que nuevas funcionalidades no rompan las existentes, y pruebas de compatibilidad across diferentes navegadores, dispositivos y sistemas operativos.

### Herramientas y Metodologías
Los profesionales de QA utilizan herramientas como Selenium, Cypress o Playwright para automatización, JIRA para gestión de defectos, y frameworks de testing específicos según la tecnología del proyecto. Trabajan dentro de metodologías ágiles como Scrum, participando en sprints y ceremonias del equipo.

### Impacto en el Negocio
Un QA efectivo previene que bugs críticos lleguen a producción, lo que evita costos de corrección post-lanzamiento, protege la reputación de la empresa y mejora la experiencia del usuario. Su trabajo contribuye directamente a la confiabilidad del producto y la satisfacción del cliente.
El rol de QA es esencial en cualquier equipo de desarrollo serio, actuando como una barrera de calidad que asegura que solo el software que cumple con los estándares establecidos llegue a los usuarios finales.

## Habilidades Esenciales para un Profesional de QA

### Habilidades Técnicas

* **Testing Manual y Automatizado:**  
Dominio de técnicas de pruebas manuales exploratorias y capacidad para crear y mantener scripts de automatización usando herramientas como Selenium, Cypress, Playwright o TestComplete.

* **Conocimientos de Programación:**  
Familiaridad con lenguajes como Python, Java, JavaScript o C# para escribir scripts de automatización, entender el código fuente y colaborar efectivamente con desarrolladores.

* **Bases de Datos:** 
Habilidades en SQL para validar datos, ejecutar consultas de verificación y entender cómo la aplicación interactúa con las bases de datos.

* **APIs y Servicios Web:**
Experiencia con herramientas como Postman, REST Assured o SoapUI para probar interfaces de programación y validar la comunicación entre sistemas.

* **Herramientas de Gestión:** 
Manejo de plataformas como JIRA, Azure DevOps, TestRail o Zephyr para documentar casos de prueba, reportar defectos y hacer seguimiento del progreso.

### Habilidades Analíticas

+ **Pensamiento Crítico:** 
Capacidad para analizar requisitos, identificar posibles escenarios de falla y diseñar casos de prueba que cubran edge cases y situaciones complejas.

+ **Resolución de Problemas:** 
Habilidad para investigar la causa raíz de los defectos, reproducir issues de manera consistente y proponer soluciones efectivas.

+ **Atención al Detalle:** 
Minuciosidad para detectar inconsistencias sutiles, errores de usabilidad y problemas que otros podrían pasar por alto.

### Habilidades de Comunicación

- **Documentación Clara:** 
Capacidad para escribir reportes de defectos detallados, casos de prueba comprensibles y documentación técnica que otros miembros del equipo puedan seguir fácilmente.

- **Comunicación Interpersonal:** 
Habilidades para explicar problemas técnicos a audiencias no técnicas, facilitar discusiones sobre calidad y mantener relaciones constructivas con desarrolladores y stakeholders.

- **Presentación:** 
Capacidad para comunicar métricas de calidad, resultados de pruebas y recomendaciones a gerencia y equipos de producto.
Conocimientos de Dominio

- **Experiencia de Usuario (UX):** 
Comprensión de principios de usabilidad para evaluar si la aplicación es intuitiva y cumple con las expectativas del usuario final.

- **Metodologías Ágiles:** 
Familiaridad con Scrum, Kanban y prácticas de desarrollo ágil para integrarse efectivamente en equipos modernos de desarrollo.

- **Comprensión del Negocio:** 
Conocimiento del dominio de la aplicación y los objetivos comerciales para priorizar pruebas y enfocar esfuerzos en áreas críticas.
Habilidades Blandas

- **Adaptabilidad:**
Flexibilidad para trabajar con diferentes tecnologías, metodologías y equipos, adaptándose rápidamente a cambios en requisitos o prioridades.

- **Gestión del Tiempo:** 
Habilidad para priorizar tareas, manejar múltiples proyectos simultáneamente y cumplir con deadlines ajustados.

- **Mentalidad de Mejora Continua:**
Disposición para aprender nuevas tecnologías, optimizar procesos de testing y mantenerse actualizado con las mejores prácticas de la industria.

- **Paciencia y Persistencia:** 
Capacidad para realizar pruebas repetitivas, investigar problemas complejos y mantener la calidad bajo presión.
Conocimientos Especializados

- **Seguridad:**
Comprensión básica de vulnerabilidades comunes (OWASP Top 10) y técnicas de testing de seguridad para identificar posibles brechas.

- **Performance Testing:**
Experiencia con herramientas como JMeter, LoadRunner o K6 para evaluar el rendimiento de aplicaciones bajo diferentes cargas de trabajo.

- **Testing Móvil:** 
Conocimiento de particularidades del testing en dispositivos móviles, incluyendo testing en diferentes sistemas operativos, resoluciones y condiciones de red.
Un QA exitoso combina estas habilidades técnicas con soft skills sólidas, manteniéndose siempre actualizado en un campo que evoluciona constantemente con nuevas tecnologías y metodologías.

## 9) Links recomendados para capacitación Rol QA

### Plataformas de Cursos Universitarios y Certificaciones

**Coursera - Cursos de Quality Assurance**
📌 https://www.coursera.org/courses?query=quality+assurance
Incluye cursos destacados como Software Testing and Automation de la Universidad de Minnesota y Foundations of Software Testing and Validation de la Universidad de Leeds, cubriendo QA de software, automatización de pruebas y metodologías de mejora de procesos Best Quality Assurance Courses & Certificates Online [2025] | Coursera

**Coursera - Software Testing Especializado**
📌 https://www.coursera.org/courses?query=software+testing
Ofrece cursos y certificados de universidades líderes y empresas reconocidas en testing de software Best Software Testing Courses & Certificates Online [2025] | Coursera
### Cursos Pagos Especializados

**Udemy - Quality Assurance Courses**
📌 https://www.udemy.com/topic/quality-assurance/
Aprende las mejores herramientas y estrategias de QA con instructores mejor valorados, desde testing manual hasta implementación de programas de aseguramiento de calidad Top Quality Assurance (QA) Courses Online - Updated [July 2025]

**Simplilearn - Automation Testing Masters Program**
📌 https://www.simplilearn.com/automation-testing-masters-program-certification-training-course
Conocimiento completo de tecnologías como Selenium, TestNG, Maven, Appium y Docker para construir frameworks de testing robustos Best Automation Testing Courses Online in 2025 – QA Automation Certification & Training
### Recursos Gratuitos de Alta Calidad

**ToolsQA - Tutorial Gratuito para Principiantes**
📌 https://www.toolsqa.com/software-testing/software-testing-tutorial/
Tutorial gratuito que incluye preparación para ISTQB y cierra la brecha entre conocimiento teórico e implementación del mundo real Free Software Testing Tutorial for Beginners | ISTQB Preparation Tutorials

**Software Testing Material**
📌 https://www.softwaretestingmaterial.com/
Plataforma que ayuda a millones de testers de software a construir carrera en testing, con recursos actualizados constantemente Software Testing Material: Free QA Resources & Tutorials

**Guru99 - Software Testing Tutorial**
📌 https://www.guru99.com/software-testing.html
Ofrece exposición en tiempo real al testing analizando proyectos en vivo y encontrando bugs, con proyectos de testing en vivo disponibles Software Testing Tutorial

**GeeksforGeeks - Software Testing Tutorial**
📌 https://www.geeksforgeeks.org/software-testing/software-testing-tutorial/
Plataforma educativa integral que empodera a estudiantes en múltiples dominios incluyendo testing de software Software Testing Tutorial - GeeksforGeeks
## Cursos Introductorios Gratuitos

**Udemy - Introduction to Software Testing**
📌 https://www.udemy.com/course/introduction-to-software-testing-or-software-qa/
Curso gratuito que enseña qué es el testing de software, cómo comenzar y dónde aprender más Free Software Testing Tutorial - Introduction to Software Testing or Software QA | Udemy

**Software Testing Help - Live Project Training**
📌 https://www.softwaretestinghelp.com/free-online-software-testing-qa-training-course/
Portal comunitario desde 2006 que ofrece entrenamiento gratuito con proyectos en vivo de testing manual Manual Software Testing Live Project Free Training

### Certificaciones Profesionales

**BrowserStack Test University**
📌 https://www.browserstack.com/guide/qa-professional-certification
Plataforma de aprendizaje online para QA y desarrolladores que ofrece más de 40 cursos relacionados con testing Top QA Certifications for Beginners & Advanced Professionals | BrowserStack

**LambdaTest - QA Certifications Guide**
📌 https://www.lambdatest.com/blog/qa-certifications/
Guía completa de las mejores 17 certificaciones de QA para 2025, cubriendo tanto testing manual como automatización Best 17 QA Certifications in 2025 | LambdaTest

### Recursos Adicionales y Comunidades

**Class Central - Quality Assurance Courses**
📌 https://www.classcentral.com/subject/quality-assurance
Más de 700 cursos online de QA que cubren metodologías de testing, sistemas de gestión de calidad y testing automatizado con Python 700+ Quality Assurance Online Courses for 2025 | Explore Free Courses & Certifications | Class Central

**GitHub - QA Resources Repository**
📌 https://github.com/3024k/QA-RESOURCES
Repositorio dedicado a almacenar recursos de conocimiento sobre SQA y otras tecnologías y herramientas útiles GitHub - 3024k/QA-RESOURCES: This repository is for storing the knowledge resources regarding SQA and other useful technologies, tools

### Recomendaciones de Uso
- Para Principiantes: Comienza con los tutoriales gratuitos de ToolsQA y Guru99, luego complementa con el curso introductorio de Udemy.
- Para Nivel Intermedio: Considera los cursos de Coursera de universidades reconocidas y explora BrowserStack Test University.
- Para Especialización: Udemy y Simplilearn ofrecen cursos avanzados en automatización y herramientas específicas.
- Para Certificación Profesional: Revisa la guía de LambdaTest para identificar las certificaciones más relevantes para tu carrera.

## 10) Desarrollador Android
## ¿Qué es?
Android es un sistema operativo basado en Linux diseñado principalmente para dispositivos móviles con pantalla táctil, como smartphones y tabletas.
Fue desarrollado por Google y es el sistema operativo móvil más utilizado en el mundo.

**Características principales:**
Es de código abierto, lo que permite a fabricantes y desarrolladores personalizarlo.
Permite crear aplicaciones nativas usando Java o Kotlin.
Ofrece acceso a funcionalidades del dispositivo como cámara, GPS, sensores y almacenamiento.
Su tienda de aplicaciones es Google Play Store.

## Retos
**01. Fragmentación**
¿Qué significa?
Android funciona en miles de modelos con diferentes características:
- Tamaños y resoluciones de pantalla.
- Distintos niveles de hardware (procesador, RAM).
- Versiones variadas de Android (de Android 8 a Android 13).
- Interfaces modificadas por los fabricantes (Samsung, Xiaomi, etc.).

¿Por qué es un reto?
Diseñar una app que funcione correctamente en todos los dispositivos es difícil.
Requiere:
- Diseños responsivos.
- Pruebas en varios dispositivos reales y simuladores.

Ejemplo: Una app que se ve bien en un Pixel puede fallar en un Samsung de gama baja.

**02. Gestión de permisos**
¿Qué significa?
Desde Android 6.0, los permisos se solicitan en tiempo de uso, no al instalar la app (como antes).

¿Por qué es un reto?
- El usuario puede rechazar permisos.
- La app debe funcionar sin fallar y explicar por qué necesita ese permiso.

Requiere:
- Mostrar un mensaje explicativo (rationale).
- Soportar reintentos sin bloquear la app.
Ejemplo: Si el usuario rechaza el permiso de cámara, la app debe avisar y seguir funcionando.

**03. Seguridad**
¿Qué significa?
Android es muy usado y es blanco frecuente de:
Malware, phishing y vulnerabilidades.

¿Por qué es un reto?
- Se deben proteger los datos sensibles.
- Cumplir con políticas de Google Play.

Requiere:
- Cifrar contraseñas y tokens.
- Validar entradas de usuario.
- Firmar el APK correctamente.

Ejemplo: Si no se cifra la base de datos local, otras apps pueden robar información si el dispositivo está rooteado.

**04. Rendimiento y consumo de batería**
¿Qué significa?
- Apps mal optimizadas consumen recursos:
- RAM.
- Procesador.
- Batería.

¿Por qué es un reto?
Una app lenta o pesada da mala experiencia al usuario.

Requiere:
- Usar WorkManager para tareas en segundo plano.
- Liberar recursos no usados.
- Optimizar imágenes y datos.

Ejemplo: Una app que sincroniza datos constantemente puede agotar la batería rápido.

**05. Conectividad**
¿Qué significa?
Muchas apps dependen de internet, pero no todos los usuarios tienen buena conexión.

¿Por qué es un reto?
La app debe funcionar con red lenta o sin conexión.

Requiere:
- Detectar desconexiones.
- Sincronizar cuando vuelva la red.
- Mostrar mensajes claros.

Ejemplo: Si se corta la red mientras se descargan datos, la app debe guardar en caché y reintentar más tarde.

## STACK DE TECNOLOGÍA

1. **Lenguaje de PROGRAMACIÓN**
   
   **Kotlin**: Oficial y recomendado por Google.  
   **Java**: Usado en proyectos antiguos.

3. **Entorno de Desarrollo (IDE)**
   
   **Android Studio**:  
   Completo, con emulador, depurador y herramientas de rendimiento.

5. **UI y Frameworks**
   
   **Jetpack Compose**:  
   Para crear interfaces modernas.  
   **ViewModel + LiveData**: Manejo eficiente de estado y ciclo de vida.

7. **Base de Datos Local**
   
   **Room**: Biblioteca moderna para persistencia local, parte de Jetpack.

9. **Consumo de APIs**
    
    **Retrofit + Kotlin Coroutines**: Para llamadas HTTP y operaciones asíncronas.

11. **Control de Versiones**
    
    **Git + GitHub**: Para gestionar código, historial y trabajo colaborativo.

## ESCALABILIDAD

**Arquitectura Limpia (Clean Architecture + MVVM)**  
Separa lógica, interfaz y datos. Facilita el crecimiento sin romper otras partes del sistema.

**Modularización del Código**

Divide el proyecto en módulos independientes (**UI, data, dominio**).  
Mejora el mantenimiento, pruebas y trabajo colaborativo.

**Inyección de Dependencias (Hilt)**

Gestiona objetos complejos de forma eficiente.  
Escalable para proyectos grandes.

**Jetpack Compose + Reutilización de Componentes UI**

UI declarativa, moderna y adaptable.  
Permite escalar la interfaz a múltiples dispositivos y diseños.




## 11) Links recomendados para capacitación Rol Android
## 🔹 Sin certificaciones

- **Developer Android - Documentación oficial (Android Developers)**: Referencia principal para desarrollo Android (Kotlin, Jetpack, UI, herramientas, etc).  
  https://developer.android.com

- **Vogella**: Tutoriales técnicos muy completos sobre Android, Java y herramientas relacionadas.  
  https://www.vogella.com/tutorials/android.html

- **CodePath Android**: Guías y recursos gratuitos sobre desarrollo Android moderno.  
  https://guides.codepath.org/android

- **Raywenderlich**: Tutoriales paso a paso y artículos sobre Kotlin, Android, Jetpack Compose y más.  
  https://www.raywenderlich.com/android

- **Kotlinlang.org**: Documentación oficial y tutoriales del lenguaje Kotlin.  
  https://kotlinlang.org/docs/home.html

---

## 🔹 Con certificación

- **Google Android Developer Certification (via Google/Udacity)**: Curso oficial para obtener la certificación de Android Developer por Google.  
  https://developer.android.com/certification

- **Coursera**: Cursos especializados como "Android App Development with Kotlin" (by Vanderbilt) o "Meta Android Developer Professional Certificate".  
  https://www.coursera.org

- **Udacity**: Cursos creados con Google, como "Developing Android Apps with Kotlin".  
  https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012

- **edX**: Programas como “Android App Development” por universidades como GalileoX o Universidad Autónoma de Madrid.  
  https://www.edx.org

---

## 🔷 Proyectos completos de ejemplo

- **GitHub**: Repositorios con proyectos Android listos (buscar: `android-sample`, `android-jetpack`, `awesome-android`).  
  https://github.com

- **Android Weekly**: Boletín con artículos, tutoriales y proyectos destacados de la semana.  
  https://androidweekly.net

- **CodePen y Replit**: Aunque menos usados en Android, pueden servir para practicar lógica en Kotlin.  
  https://replit.com

---

## 🔷 Recomendadas por líderes (Google, JetBrains, etc)

- **Google Codelabs**: Laboratorios paso a paso sobre Android con Jetpack, Kotlin, Firebase, etc.  
  https://developer.android.com/codelabs

- **JetBrains Academy**: Curso interactivo de Kotlin con proyectos reales.  
  https://www.jetbrains.com/academy

- **Firebase Docs**: Integración de backend en apps Android (auth, firestore, storage, etc).  
  https://firebase.google.com/docs

## 12) Mermaid del Proyecto: 

```mermaid
flowchart TD
    A["Programación"] --> B["Frontend"] & C["Backend"] & D["Android"] & E["Quality & A"]
    B --> F["CSS"] & G["HTML"] & n2["Java Script"]
    C --> n1["Rutas"] & n8["Controladores"] & n13["Base de Datos"]
    D --> n3["Curso Kotlin Platzi"] & n4["Microsoft Learn"]
    E --> n5["Untitled Node"]
    click A "https://developer.mozilla.org/es/docs/Web/HTML"
    click B "https://www.canva.com/design/DAGtMQ3AYMQ/pLPHPvi2M1KuNY3SXel7Xw/edit?utm_content=DAGtMQ3AYMQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton"
    click C "https://gamma.app/docs/Backend-en-Programacion-Web-El-Motor-Oculto-45ylg348bflrq98"
    click D "https://developer.mozilla.org/es/docs/Web/JavaScript"
    click E "https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML"
    click F "https://developer.mozilla.org/es/docs/Learn/CSS/First_steps"
    click G "https://www.w3schools.com/html/default.asp"
    click n2 "https://developer.mozilla.org/es/docs/Web/JavaScript"
    click n1 "🔗 https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Express_Nodejs/routes"
    click n8 "https://platzi.com/cursos/nodejs-mongo-websockets/conceptualmente-rutas-controladores-y-bases-de-dat/"
    click n13 "https://www.programando.org/blog/2022/03/06/el-camino-del-backend-developer-bases-de-datos/"
    click n3 "https://platzi.com/cursos/kotlin/"
    click n4 "https://learn.microsoft.com/en-us/training/"
    click n5 "https://example.com/"


