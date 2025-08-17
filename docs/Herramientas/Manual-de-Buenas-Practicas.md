---

title:  📚 Buenas Prácticas

---

# 📚 Buenas Prácticas para el uso de IA en el Aula

A continuación se ofrecen pautas para facilitar la integración de **IA generativa** (p. ej., LLMs) en el aula de forma **ética, segura y pedagógica**. Sirve tanto para **docentes** como para **estudiantes**, con listas de verificación, ejemplos paso a paso y plantillas.

> Idea fuerza: la IA es un **asistente** para aprender mejor; no reemplaza el pensamiento crítico ni la guía humana.

---

## 🎯 Principios fundamentales

1. **Asistencia, no sustitución**
   - La IA apoya; la autoría final es humana.
2. **Transparencia**
   - Declarar siempre **cuándo y cómo** se usó IA.
3. **Verificación**
   - Contrastar con textos de la asignatura y fuentes fiables.
4. **Privacidad y seguridad**
   - No subir datos sensibles; anonimizar ejemplos.
5. **Equidad y diversidad**
   - Incluir perspectivas variadas; evitar sesgos.

📎 Material de organismos internacionales:
- UNESCO — [Guía para el uso de IA generativa en educación e investigación](https://www.unesco.org/es/articles/guia-para-el-uso-de-ia-generativa-en-educacion-e-investigacion)  
- UNESCO — [Marco de competencias para docentes en materia de IA](https://www.unesco.org/es/articles/marco-de-competencias-para-docentes-en-materia-de-ia) 

🔗 Enlaces internos:
- [Ética y Responsabilidad en IA](../Etica/Etica-y-Responsabilidad-en-IA.md) · [Alfabetización de Datos en Contexto Educativo](../Fundamentos/Alfabetizacion-de-Datos-en-Contexto-Educativo.md)  
- [Prompt Engineering para Docentes](./Prompt-Engineering-para-Docentes.md) · [Plantillas de Prompts para Debates](./Plantillas-de-Prompts-para-Debates.md) · [Sesgos, Equidad y Justicia en IA](../Fundamentos/Sesgos-Equidad-Justicia-en-IA.md)

---

## 🧑‍🎓 Checklist rápido para estudiantes

Usa esta lista **antes de entregar** cualquier trabajo con apoyo de IA:

- [ ] **Propósito claro**: sé qué tarea resuelve la IA.  
- [ ] **Prompt de calidad**: define rol, contexto y formato.  
- [ ] **Verifiqué datos**: comprobé fechas, citas, definiciones.  
- [ ] **Detecté sesgos**: consideré perspectivas alternativas.  
- [ ] **Reelaboré**: reescribí con mis palabras y añadí ideas propias.  
- [ ] **Cité fuentes**: incluí referencias del curso.  
- [ ] **Declaré uso de IA**: añadí mi nota de transparencia (ver plantilla).  
- [ ] **Cumplo política del curso**: revisé las reglas de la asignatura.

**Plantilla — Declaración de uso de IA** _(añádela al final de tu trabajo)_:
> Utilicé IA generativa para: [tormenta de ideas / contraargumentos / estructura].  
> Herramienta: [nombre]. Prompts clave: [resumen].  
> Cambios propios: [síntesis, ejemplos, referencias].  
> Verifiqué la información con: [lecturas del curso / fuentes].

---

## 👩‍🏫 Políticas de aula sugeridas (para docentes)

**Usos legítimos**: lluvia de ideas, bosquejos, contraargumentos, organización, feedback preliminar.  
**Usos no permitidos**: entregar texto de IA como propio; citas inventadas; datos falsos.

**Cláusulas breves para el sílabo**:
- “Se permite IA como apoyo **con declaración de uso** y **verificación** posterior.”  
- “Los datos personales de estudiantes **no** deben introducirse en sistemas externos.”  
- “Siempre existirá una **alternativa humana** para tutoría y evaluación.”

---

## 🧰 Buenas prácticas por fases

**Antes**
- Define objetivos y criterios de evaluación.
- Elige herramientas alineadas al curso.
- Prepara prompts modelo.

**Durante**
- Pide **formato de salida** (viñetas, tabla corta, esquema).
- Solicita **razonamiento paso a paso** cuando sea útil.
- Interrumpe para verificar: “¿qué faltó? ¿qué sesgo ves?”

**Después**
- Revisión humana final.
- Reflexión metacognitiva: “¿cómo cambió tu idea?”
- Guarda ejemplos para retroalimentación colectiva.

---

## 🧪 Ejemplos extendidos para docentes (paso a paso)

> Cada ejemplo incluye: objetivo, tiempo, materiales, pasos, prompt sugerido, evaluación y variaciones.

### 1) Taller de falacias con revisión crítica
**Objetivo**: identificar falacias; mejorar argumentos.  
**Tiempo**: 40–60 min.  
**Materiales**: fragmentos de textos del curso; LLM.

**Pasos**  
1) Entrega un argumento breve del temario.  
2) Pide al LLM detectar posibles falacias (máx. 3).  
3) En grupos, contrastan con el texto base.  
4) Cada grupo corrige el argumento original.

**Prompt sugerido**  
```markdown
Actúa como crítico lógico. 
Texto: “[…]”. 
Tarea: nombra hasta 3 falacias (si existen), define cada una en 1–2 líneas y sugiere una corrección breve.
Formato: lista numerada.
```

**Evaluación (rúbrica mini)**  
- Detección correcta (sí/no).  
- Corrección clara (sí/no).  
- Conexión con lectura (alta/media/baja).

**Variaciones**: crear ejemplos deliberadamente ambiguos; comparar salidas de 2 modelos.

---

### 2) Debate guiado con contraargumentos
**Objetivo**: practicar dialéctica; reconocer supuestos.  
**Tiempo**: 50–70 min.  
**Materiales**: moción; LLM.

**Pasos**  
1) LLM genera **tres contraargumentos** a una postura del estudiante.  
2) El estudiante responde y justifica con lecturas.  
3) Cierre: identificación de supuestos implícitos.

**Prompt sugerido**  
```markdown
Rol: entrenador de debate. 
Moción: “La evaluación automatizada es justa”. 
Tarea: 3 contraargumentos breves con su supuesto implícito.
Formato: viñetas.
Límite: 60–80 palabras.
```

**Evaluación**  
- Refiere a autores del curso.  
- Contraargumentos relevantes.  
- Respuesta propia bien justificada.

---

### 3) Ensayo con IA como apoyo transparente
**Objetivo**: planificar, estructurar y revisar.  
**Tiempo**: 1–2 semanas.  
**Materiales**: consignas; bibliografía.

**Fases**  
- **Idea**: lluvia de ideas con IA (no texto final).  
- **Esquema**: pedir estructura en viñetas.  
- **Borrador**: redacta el estudiante.  
- **Revisión IA**: solicitar sugerencias de claridad y cohesión.  
- **Revisión humana**: profesor/pares.  
- **Declaración de uso**: adjuntar.

**Prompt sugerido (para revisión)**  
```markdown
Rol: editor académico. 
Texto del estudiante: “[…]”.
Tarea: sugiere mejoras de claridad y cohesión; no reescribas todo; marca 3 cambios clave.
Formato: viñetas.
```

**Evaluación**  
- Coherencia del argumento.  
- Uso de fuentes reales.  
- Transparencia de uso de IA.

---

### 4) “Caza de alucinaciones” (datos y citas)
**Objetivo**: distinguir plausible vs. verdadero.  
**Tiempo**: 30–45 min.

**Pasos**  
1) Genera con IA “resumen con 3 citas” de un tema del curso.  
2) Estudiantes verifican si las citas existen.  
3) Discusión: cómo prevenir alucinaciones.

**Prompt sugerido**  
```markdown
Genera 3 citas breves y plausibles sobre [tema] con autor y año. 
Aclara: “Estas citas son hipotéticas y deben verificarse”.
```

**Evaluación**  
- Porcentaje de verificación.  
- Estrategias de corrección propuestas.

---

### 5) Analítica de lectura para inclusión
**Objetivo**: detectar brechas de participación.  
**Tiempo**: 30–40 min (más análisis).  
**Materiales**: dashboard del LMS.

**Pasos**  
1) Observan qué textos reciben menos consultas.  
2) Debaten causas (sesgos, carga, accesibilidad).  
3) Plan de acción (p. ej., guía de lectura, foro dirigido).

**Evaluación**  
- Diagnóstico claro.  
- Medida concreta.  
- Seguimiento posterior.

---

### 6) Co-creación de rúbrica con IA
**Objetivo**: criterios claros y compartidos.  
**Tiempo**: 25–35 min.

**Pasos**  
1) Pide a IA una base de rúbrica breve.  
2) Ajusta con la clase (niveles, ejemplos).  
3) Aplícala en una miniactividad.

**Prompt sugerido**  
```markdown
Rol: diseñador instruccional. 
Tarea: rúbrica breve para análisis de argumento filosófico. 
Criterios: tesis, evidencias, contraargumentos, claridad.
Niveles: excelente/adecuado/a mejorar. 
Formato: tabla simple.
```

---

## 🧩 Plantillas útiles (copiar/pegar)

**Metaprompt de mejora**  
```markdown
Evalúa mi prompt y sugiere 3 mejoras para hacerlo más claro y útil:
[pegar prompt]
```

**Prompt base de debate**  
```markdown
Eres moderador imparcial.
Tema: [moción].
Salida: 2 argumentos pro, 2 contra, 1 pregunta final.
Estilo: conciso.
```

**Prompt de análisis lógico**  
```markdown
Rol: crítico lógico.
Texto: “[párrafo]”.
Tarea: P1, P2, C; 1 posible falacia; mejora breve.
```

---

## 📊 Rúbrica mini (docente)

| Criterio                 | Excelente              | A mejorar           |
|--------------------------|------------------------|---------------------|
| Claridad del prompt      | Rol/Contexto/Formato   | Vago/ambigüo        |
| Verificación             | Hechos y citas revisados| Sin verificación    |
| Uso crítico de IA        | Mejora y cuestiona      | Copia acrítica      |
| Conexión con curso       | Autores/lecturas del plan| Desconexión        |
| Transparencia            | Declaración de uso       | Sin declarar        |

*(Mantén celdas breves para facilitar corrección rápida.)*

---

## 🛡️ Privacidad, seguridad y agencia

- No usar **nombres reales** ni datos sensibles.  
- Preferir herramientas **institucionales** cuando existan.  
- Ofrecer **alternativas humanas** para tutoría y evaluación.  
- Documentar **consentimiento informado** cuando corresponda.

---

## ✅ Indicadores de logro

- Prompts con **rol, contexto, formato**.  
- Respuestas **verificadas** y **reelaboradas**.  
- Identificación de **sesgos** y **alucinaciones**.  
- Declaración de uso de IA **incluida**.  
- Mejora de calidad entre borrador y versión final.

---

## 📎 Recursos y enlaces internos

- [Plantillas de Prompts para Debates](./Plantillas-de-Prompts-para-Debates.md) · [IA en el Aula: Herramientas y Usos Actuales](../Fundamentos/IA-en-el-Aula-Herramientas-y-Usos-Actuales.md) · [Analítica del Aprendizaje y Dashboards Educativos](../Fundamentos/Analitica-del-Aprendizaje-y-Dashboards-Educativos.md) · [Sesgos, Equidad y Justicia en IA](../Fundamentos/Sesgos-Equidad-Justicia-en-IA.md).

---

*Para profundizar en técnicas de diseño de prompts y context engineering, consulta también el documento [Prompt Engineering para Docentes](./Prompt-Engineering-para-Docentes.md).*
