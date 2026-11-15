# HealthTech Functional & Clinical Portfolio (Español)

Repositorio que contiene el diseño, la documentación funcional y la interfaz de presentación de casos de estudio en el sector de la tecnología sanitaria (*HealthTech*). Este proyecto sirve como escaparate para demostrar la intersección entre los flujos asistenciales reales de Atención Primaria y la ingeniería de software.

## 🚀 Contenido del Portfolio
- **Caso 1:** Optimización de Alertas de Urgencia Vital en AP (Flujos por turnos y doble check).
- **Caso 2:** Digitalización de Electrocardiogramas y Convivencia con Sistemas Legacy (APMadrid).
- **Caso 3:** El puente funcional-técnico (Traducción de requerimientos clínicos a especificaciones de desarrollo).
- **Caso 4:** Automatización de Inventario de Sensores con PowerShell y OCR (Solución de campo en entorno clínico restringido).

## 🛠️ Tecnologías utilizadas
- HTML5 / Tailwind CSS (Diseño editorial y ultraligero).
- JavaScript nativo para interactividad limpia.
- Arquitectura orientada a especificaciones funcionales (Gherkin, flujos de usuario, matrices de riesgo).
- Web3Forms API (Pasarela serverless para recepción de contacto sin servidor propio).


## 🧩 Decisiones de alcance

Este portfolio prioriza **claridad funcional sobre complejidad técnica**.
Decisiones conscientes:

- **HTML estático + Tailwind CDN**: el objetivo es que la documentación
  funcional sea legible y desplegable en 0 fricción. No hay backend
  porque no hay estado que persistir.
- **JS vanilla**: la interactividad es presentacional (navegación entre
  casos, filtros). Framework innecesario para el alcance.
- **Sin tests**: no hay lógica de negocio que testear. Los "tests"
  aquí son los escenarios Gherkin documentados.
- **Contacto serverless (Web3Forms)**: al no existir backend, el envío del formulario se delega en una API externa vía fetch asíncrono con protección honeypot, evitando levantar infraestructura solo para gestionar mensajes.

👉 Si buscas un ejemplo de arquitectura escalable, este no es el repo.
   Si buscas un ejemplo de traducción clínico-técnica, sí.

## 🌐 Enlace en vivo
Puedes ver la página funcionando en [GitHub Pages](https://LuisenLou.github.io/healthtech-portfolio/).


---

---



# HealthTech Functional & Clinical Portfolio (English)

Repository containing the design, functional documentation, and presentation interface for case studies in the healthcare technology (*HealthTech*) sector. This project serves as a showcase to demonstrate the intersection between real Primary Care healthcare workflows and software engineering.

## 🚀 Portfolio Contents
- **Case 1:** Optimization of Life-Threatening Emergency Alerts in PC (Shift-based workflows and double check).
- **Case 2:** Digitization of Electrocardiograms and Coexistence with Legacy Systems (APMadrid).
- **Case 3:** The functional-technical bridge (Translation of clinical requirements into development specifications).
- **Case 4:** Sensor Inventory Automation via PowerShell & OCR (Field automation in restricted clinical environments).

## 🛠️ Technologies used
- HTML5 / Tailwind CSS (Editorial and ultralight design).
- Native JavaScript for clean interactivity.
- Architecture oriented toward functional specifications (Gherkin, user flows, risk matrices).
- Web3Forms API (Serverless gateway for contact reception without your own server).

# 🧩 Scope Decisions

This portfolio prioritizes **functional clarity over technical complexity**.
Conscious decisions:

- **Static HTML + Tailwind CDN**: the goal is for the functional documentation to be legible and deployable with zero friction. There is no backend because there is no state to persist.
- **Vanilla JS**: the interactivity is presentational (navigation between cases, filters). A framework is unnecessary for this scope.
- **No tests**: there is no business logic to test. The "tests" here are the documented Gherkin scenarios.
- **Serverless contact (Web3Forms)**: since there is no backend, form submission is delegated to an external API via asynchronous fetch with honeypot protection, avoiding the need to spin up infrastructure just to manage messages.

👉 If you're looking for an example of scalable architecture, this is not the repo.
   If you're looking for an example of clinical-technical translation, it is.

## 🌐 Live link
You can see the page running at [GitHub Pages](https://LuisenLou.github.io/healthtech-portfolio/).
