# Refactorización de código siguiendo principios SOLID

El equipo de desarrollo ha identificado una brecha en la calidad del código de un proyecto de banca en línea. El código actual no sigue los principios SOLID, lo que dificulta su mantenimiento y escalabilidad. Como desarrollador junior, tu tarea es refactorizar una sección crítica del código para aplicar estos principios y mejorar su calidad.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | código limpio |
| **Nivel** | junior-l1 |
| **Tipo** | practical |
| **Tiempo estimado** | 8 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: JDK 17+, Maven 3.9+, IDE con soporte Java.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `mvn compile` en la raíz. Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Análisis del código existente

**Objetivo:** Identificar las áreas del código que no siguen los principios SOLID y documentar las razones.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Revisa el código existente y enumera las secciones que no cumplen con los principios SOLID.
- Documenta las razones por las que cada sección no cumple con los principios SOLID.

**Entregable:** Documento que detalla las áreas del código que no siguen los principios SOLID y las razones.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda que los principios SOLID son: Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation y Dependency Inversion.

</details>

### Fase 2: Refactorización del código

**Objetivo:** Aplicar los principios SOLID para mejorar la calidad del código.

**Tiempo estimado:** 4 horas

**Instrucciones:**

- Refactoriza el código para que siga los principios SOLID.
- Documenta los cambios realizados y las razones detrás de cada cambio.

**Entregable:** Código refactorizado que sigue los principios SOLID y documentación de los cambios realizados.

<details>
<summary>Pistas de conocimiento</summary>

- Considera cómo puedes aplicar el principio de Single Responsibility para que cada clase tenga una única razón para cambiar.
- Piensa en cómo puedes usar interfaces para seguir el principio de Dependency Inversion.

</details>

### Fase 3: Revisión y retroalimentación

**Objetivo:** Revisar el código refactorizado y recibir retroalimentación de un compañero.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Comparte tu código refactorizado con un compañero y solicita retroalimentación.
- Documenta la retroalimentación recibida y las mejoras que harás en base a ella.

**Entregable:** Documento que detalla la retroalimentación recibida y las mejoras planificadas.

<details>
<summary>Pistas de conocimiento</summary>

- Considera las sugerencias de tu compañero y cómo puedes incorporarlas para mejorar aún más el código.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué son los principios SOLID y por qué son importantes para la calidad del código?
- **paraQueSirve**: ¿Cómo aplicas el principio de Open/Closed en tu refactorización?
- **comoSeUsa**: ¿Cómo usas interfaces para seguir el principio de Dependency Inversion?
- **erroresComunes**: ¿Qué errores comunes evitas al aplicar los principios SOLID?
- **queDecisionesImplica**: ¿Qué decisiones tomaste para seguir el principio de Interface Segregation?

## Criterios de Evaluacion

- Identificar correctamente las áreas del código que no siguen los principios SOLID.
- Refactorizar el código para que siga los principios SOLID.
- Documentar los cambios realizados y las razones detrás de cada cambio.
- Incorporar retroalimentación recibida para mejorar el código.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
