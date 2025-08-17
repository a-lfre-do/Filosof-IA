---
title: Escritura de Prompts para Docentes
nav_order: 3
parent: Herramientas
---

# 🎤 Escritura de Prompts para Docentes

Los **prompts** son instrucciones cuidadosamente diseñadas para interactuar con modelos de IA y obtener respuestas útiles en contextos educativos. En el ámbito de la enseñanza de la filosofía, pueden servir como un **andamio pedagógico** que apoya la preparación, el desarrollo y la evaluación de aprendizajes en debates escolares.

Este documento presenta una **estructura ampliada** para redactar prompts que permitan a docentes y estudiantes usar la IA de manera clara, segura y productiva. La propuesta se inspira en la práctica de torneos de debate (formato **WSDC/MED**) y en la experiencia pedagógica del **Desafío Filosof-IA**.

---

## 🎯 Objetivos
- Aprender a **diseñar prompts efectivos** para debates filosóficos.  
- Entender el rol del **context engineering** en la calidad de las respuestas.  
- Aplicar buenas prácticas para guiar discusiones críticas y argumentativas.  
- Facilitar la autonomía de los estudiantes en el uso responsable de IA.  

---

## 📌 Elementos clave dentro de un prompt

Cada prompt puede producir diferentes resultados dependiendo del LLM con el que se está trabajando. Existen diferentes maneras de estructurar los prompt, puedes organizarlos en secciones que hacen explícitas las expectativas y delimitan el alcance de la tarea. Algunos de los elementos más relevantes son:

- **Rol** 🧑‍🏫  
  Indica quién debe “ser” la IA en la simulación (p. ej., jueza de debate, coach, contrincante, diseñador de mociones). Esto ayuda a orientar el tono y nivel de profundidad de la respuesta.

- **Tarea** 🎯  
  Precisa qué debe hacer la IA: generar mociones, preparar un plan de caso, simular un Punto de Información, evaluar un discurso, etc.

- **Contexto** 🌍  
  Explica la situación educativa: curso, edad de los estudiantes, formato del debate, objetivos pedagógicos. Permite que la respuesta esté alineada con las necesidades reales del aula.

- **Razonamiento paso a paso** 🔎  
  Indica el camino lógico que debe seguir la IA para llegar a una salida coherente y detallada, evitando respuestas superficiales o incompletas.

- **Formato de salida** 📝  
  Define cómo se presentará la respuesta (lista, tabla, guion por minutos, etc.), garantizando claridad y usabilidad directa en el aula.

- **Condiciones de parada** ⛔  
  Establecen límites para la respuesta (p. ej., no inventar datos, evitar lenguaje ofensivo, mantener nivel escolar). Esto protege la calidad y pertinencia del contenido generado.

---

# 🎙️ "Prompting" y "Prompt Engineering"

**Prompting** y **Prompt Engineering** son nombres otorgados inicialmente a la técnica de diseñar instrucciones claras, estructuradas y efectivas para interactuar con **Modelos de Lenguaje (LLM)** como ChatGPT.  
En el contexto de la enseñanza de la filosofía y la práctica del debate, esta habilidad permite a los docentes **optimizar el uso de la IA como herramienta pedagógica**, tanto para su práctica docente, como para guiar a el uso de sus estudiantes.

---

## 🛠️ Fundamentos del Prompt Engineering

Un **prompt** no es solo una pregunta:  
es una **instrucción estructurada** que orienta cómo el modelo procesa la información.  
La calidad de la salida depende en gran medida de:  
- **Claridad:** instrucciones específicas y sin ambigüedades.  
- **Estructura:** uso de formatos (listas, pasos, roles).  
- **Contexto:** información suficiente para guiar la generación.  
- **Rol asignado:** indicar al modelo desde qué perspectiva debe responder (ej. *“actúa como profesor de filosofía kantiana”*).  

---

## 🧭 Context Engineering

El **Context Engineering** es una práctica avanzada que consiste en **aprovechar la ventana de contexto del modelo** de la forma más estratégica posible.  
Se trata de **diseñar la interacción completa** (no solo el prompt aislado), teniendo en cuenta:

- **System prompt del LLM**  
  Cada modelo de lenguaje parte de un *system prompt* oculto que define su estilo y límites.  
  Ajustar nuestro prompt en sintonía con este marco aumenta la coherencia de las respuestas.  

- **Estructuración del contexto**  
  - Incluir definiciones, ejemplos y reglas dentro del prompt inicial.  
  - Usar **bloques delimitados** (ej. “###”, listas numeradas, comillas triples).  
  - Introducir el rol de la IA y los criterios de evaluación antes de la pregunta principal.  

- **Gestión de la ventana de contexto**  
  - Aprovechar el máximo de tokens disponibles para dar **instrucciones detalladas**.  
  - Mantener un **historial relevante** en la conversación, evitando información redundante.  
  - Usar *resúmenes intermedios* cuando la conversación se haga extensa.  

---

## ✅ Buenas Prácticas
- **Define roles claros**: moderador, filósofo histórico, oponente, juez, etc.  
- **Incluye criterios de evaluación**: profundidad, claridad, uso de ejemplos.  
- **Proporciona contexto suficiente**: fechas, corrientes filosóficas, casos concretos.  
- **Usa delimitadores de secciones** para organizar la salida del modelo.  
- **Reformula en lugar de repetir**: si la IA se desvía, corrige con instrucciones más precisas.  

---

## ⚠️ Errores Comunes a Evitar
- Prompts demasiado **genéricos**: *“Explícame la ética”*.  
- No aprovechar el **rol del sistema**: *“Responde como si fueras…”*.  
- Sobrecargar el prompt con **información irrelevante**.  
- No gestionar el **historial de contexto**, lo que puede generar incoherencias.  

---

## 📂 Recursos Relacionados
- [📄 Plantillas de Prompts](./Plantillas-de-Prompts.md)  
- [📘 Manual de Buenas Prácticas en el Aula](../Herramientas/Manual-de-Buenas-Practicas.md)  
- [⚖️ Ética y Responsabilidad en IA](../Etica/Etica-y-Responsabilidad-en-IA.md)  

---

## 🚀 Próximo Paso
Explora [📄 Plantillas de Prompts para Debates](./Plantillas-de-Prompts.md) para comenzar a aplicar estas técnicas en tu primera sesión de debate asistido por IA.

---

> Nota: Para un enfoque complementario centrado en reglas, políticas y ejemplos prácticos de aplicación en el aula, consulta también el [📘 Manual de Buenas Prácticas en el Aula](../Herramientas/Manual-de-Buenas-Practicas.md).
