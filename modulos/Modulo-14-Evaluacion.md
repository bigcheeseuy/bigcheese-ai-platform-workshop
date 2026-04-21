# 📝 Evaluación de Conocimientos

¡Felicitaciones por completar el workshop! Ahora es momento de evaluar lo que aprendiste sobre el Model Context Protocol (MCP).

---

## Instrucciones

Esta evaluación contiene **10 preguntas de opción múltiple** sobre los conceptos clave de MCP que cubrimos en el workshop. 

- Lee cada pregunta cuidadosamente
- Selecciona la respuesta que consideres correcta
- Al finalizar, podrás ver tu puntuación y las respuestas correctas

---

<div id="quiz-container">

### Pregunta 1
**¿Cuál es el propósito principal del Model Context Protocol (MCP)?**

<ul class="quiz-options">
<li><input type="radio" name="q1" value="A" id="q1a"><label for="q1a">A) Reemplazar completamente a los modelos de lenguaje</label></li>
<li><input type="radio" name="q1" value="B" id="q1b"><label for="q1b">B) Estandarizar cómo las aplicaciones proporcionan contexto a los LLMs</label></li>
<li><input type="radio" name="q1" value="C" id="q1c"><label for="q1c">C) Crear una nueva arquitectura de redes neuronales</label></li>
<li><input type="radio" name="q1" value="D" id="q1d"><label for="q1d">D) Optimizar el rendimiento de AWS Bedrock</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(1, 'B')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-1"></div>

---

### Pregunta 2
**¿Cuáles son las tres primitivas fundamentales de MCP?**

<ul class="quiz-options">
<li><input type="radio" name="q2" value="A" id="q2a"><label for="q2a">A) Tools, Resources, y Prompts</label></li>
<li><input type="radio" name="q2" value="B" id="q2b"><label for="q2b">B) Models, Clients, y Servers</label></li>
<li><input type="radio" name="q2" value="C" id="q2c"><label for="q2c">C) Input, Output, y Processing</label></li>
<li><input type="radio" name="q2" value="D" id="q2d"><label for="q2d">D) Request, Response, y Callback</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(2, 'A')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-2"></div>

---

### Pregunta 3
**¿Qué rol cumple el Cliente MCP en la arquitectura?**

<ul class="quiz-options">
<li><input type="radio" name="q3" value="A" id="q3a"><label for="q3a">A) Ejecuta las herramientas directamente</label></li>
<li><input type="radio" name="q3" value="B" id="q3b"><label for="q3b">B) Almacena los datos de la aplicación</label></li>
<li><input type="radio" name="q3" value="C" id="q3c"><label for="q3c">C) Orquesta la comunicación entre la aplicación y el servidor MCP</label></li>
<li><input type="radio" name="q3" value="D" id="q3d"><label for="q3d">D) Entrena el modelo de lenguaje</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(3, 'C')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-3"></div>

---

### Pregunta 4
**¿Qué es el MCP Inspector?**

<ul class="quiz-options">
<li><input type="radio" name="q4" value="A" id="q4a"><label for="q4a">A) Una herramienta de debugging para servidores MCP</label></li>
<li><input type="radio" name="q4" value="B" id="q4b"><label for="q4b">B) Un monitor de rendimiento para AWS Bedrock</label></li>
<li><input type="radio" name="q4" value="C" id="q4c"><label for="q4c">C) Un editor de código especializado</label></li>
<li><input type="radio" name="q4" value="D" id="q4d"><label for="q4d">D) Un sistema de logs centralizado</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(4, 'A')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-4"></div>

---

### Pregunta 5
**¿Cuál es la diferencia principal entre Tools y Resources en MCP?**

<ul class="quiz-options">
<li><input type="radio" name="q5" value="A" id="q5a"><label for="q5a">A) Tools son síncronos, Resources son asíncronos</label></li>
<li><input type="radio" name="q5" value="B" id="q5b"><label for="q5b">B) Tools son invocados por el modelo, Resources son leídos directamente por la aplicación</label></li>
<li><input type="radio" name="q5" value="C" id="q5c"><label for="q5c">C) Tools son más rápidos que Resources</label></li>
<li><input type="radio" name="q5" value="D" id="q5d"><label for="q5d">D) No hay diferencia, son sinónimos</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(5, 'B')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-5"></div>

---

### Pregunta 6
**¿Qué protocolo de transporte utiliza MCP para la comunicación?**

<ul class="quiz-options">
<li><input type="radio" name="q6" value="A" id="q6a"><label for="q6a">A) HTTP/REST exclusivamente</label></li>
<li><input type="radio" name="q6" value="B" id="q6b"><label for="q6b">B) WebSockets exclusivamente</label></li>
<li><input type="radio" name="q6" value="C" id="q6c"><label for="q6c">C) JSON-RPC sobre stdio o SSE</label></li>
<li><input type="radio" name="q6" value="D" id="q6d"><label for="q6d">D) gRPC</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(6, 'C')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-6"></div>

---

### Pregunta 7
**En el caso de XYZ S.A., ¿qué problema resolvió MCP?**

<ul class="quiz-options">
<li><input type="radio" name="q7" value="A" id="q7a"><label for="q7a">A) Reducir los costos de infraestructura</label></li>
<li><input type="radio" name="q7" value="B" id="q7b"><label for="q7b">B) Estandarizar el acceso a datos internos para el chatbot</label></li>
<li><input type="radio" name="q7" value="C" id="q7c"><label for="q7c">C) Mejorar la velocidad de respuesta del modelo</label></li>
<li><input type="radio" name="q7" value="D" id="q7d"><label for="q7d">D) Eliminar la necesidad de desarrolladores</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(7, 'B')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-7"></div>

---

### Pregunta 8
**¿Qué ventaja ofrece el uso de Prompts en MCP?**

<ul class="quiz-options">
<li><input type="radio" name="q8" value="A" id="q8a"><label for="q8a">A) Aumenta la velocidad de procesamiento del modelo</label></li>
<li><input type="radio" name="q8" value="B" id="q8b"><label for="q8b">B) Reduce el costo de las llamadas a la API</label></li>
<li><input type="radio" name="q8" value="C" id="q8c"><label for="q8c">C) Encapsula flujos de trabajo complejos en comandos simples</label></li>
<li><input type="radio" name="q8" value="D" id="q8d"><label for="q8d">D) Elimina la necesidad de herramientas</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(8, 'C')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-8"></div>

---

### Pregunta 9
**¿Cuál es el formato de URI para acceder a recursos en MCP?**

<ul class="quiz-options">
<li><input type="radio" name="q9" value="A" id="q9a"><label for="q9a">A) http://resource/name</label></li>
<li><input type="radio" name="q9" value="B" id="q9b"><label for="q9b">B) mcp://resource/name</label></li>
<li><input type="radio" name="q9" value="C" id="q9c"><label for="q9c">C) resource://name</label></li>
<li><input type="radio" name="q9" value="D" id="q9d"><label for="q9d">D) Depende de la implementación del servidor</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(9, 'D')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-9"></div>

---

### Pregunta 10
**¿Qué servicio de AWS se utilizó en el workshop para el modelo de lenguaje?**

<ul class="quiz-options">
<li><input type="radio" name="q10" value="A" id="q10a"><label for="q10a">A) Amazon SageMaker</label></li>
<li><input type="radio" name="q10" value="B" id="q10b"><label for="q10b">B) AWS Lambda</label></li>
<li><input type="radio" name="q10" value="C" id="q10c"><label for="q10c">C) Amazon Bedrock</label></li>
<li><input type="radio" name="q10" value="D" id="q10d"><label for="q10d">D) Amazon Comprehend</label></li>
</ul>

<button class="quiz-check-btn" onclick="checkAnswer(10, 'C')">Verificar Respuesta</button>

<div class="quiz-feedback" id="feedback-10"></div>

</div>

<script>
const explanations = {
  1: "MCP es un protocolo abierto que estandariza cómo las aplicaciones proporcionan contexto a los LLMs, permitiendo una integración más fluida entre sistemas y modelos.",
  2: "Las tres primitivas de MCP son: Tools (herramientas que el modelo puede invocar), Resources (datos que el modelo puede leer), y Prompts (plantillas de flujos de trabajo).",
  3: "El cliente MCP actúa como orquestador, conectando la aplicación host con uno o más servidores MCP y gestionando la comunicación bidireccional.",
  4: "El MCP Inspector es una herramienta visual que permite probar y debuggear servidores MCP sin necesidad de implementar un cliente completo.",
  5: "Tools son funciones que el modelo puede invocar para realizar acciones, mientras que Resources son datos que la aplicación puede leer directamente sin pasar por el modelo.",
  6: "MCP utiliza JSON-RPC 2.0 como protocolo de mensajería, que puede transportarse sobre stdio (standard input/output) o SSE (Server-Sent Events).",
  7: "MCP permitió a Santiago estandarizar cómo el chatbot accede a datos internos de XYZ (propuestas, CVs, etc.) sin tener que crear integraciones personalizadas para cada fuente de datos.",
  8: "Los Prompts en MCP permiten empaquetar flujos de trabajo complejos (con múltiples pasos y contexto específico) en comandos simples que los usuarios pueden invocar fácilmente.",
  9: "El formato de URI para recursos es definido por cada servidor MCP. Por ejemplo, en el workshop usamos URIs como 'proposal://bigcheese' o 'talent://all'.",
  10: "El workshop utilizó Amazon Bedrock, el servicio de AWS que proporciona acceso a modelos de lenguaje de última generación a través de una API unificada."
};

function checkAnswer(questionNum, correctAnswer) {
  const selected = document.querySelector(`input[name="q${questionNum}"]:checked`);
  const feedback = document.getElementById(`feedback-${questionNum}`);
  const button = event.target;
  
  if (!selected) {
    feedback.innerHTML = `<div class="feedback-warning">⚠️ Por favor selecciona una respuesta antes de verificar.</div>`;
    feedback.style.display = 'block';
    return;
  }
  
  // Deshabilitar el botón después de verificar
  button.disabled = true;
  button.style.opacity = '0.5';
  button.style.cursor = 'not-allowed';
  
  // Deshabilitar todos los radio buttons de esta pregunta
  document.querySelectorAll(`input[name="q${questionNum}"]`).forEach(input => {
    input.disabled = true;
  });
  
  const isCorrect = selected.value === correctAnswer;
  
  if (isCorrect) {
    feedback.innerHTML = `
      <div class="feedback-correct">
        <div class="feedback-icon">✅</div>
        <div class="feedback-content">
          <strong>¡Correcto!</strong><br>
          ${explanations[questionNum]}
        </div>
      </div>
    `;
    selected.parentElement.style.background = '#d4f4dd';
    selected.parentElement.style.borderColor = '#4caf50';
  } else {
    feedback.innerHTML = `
      <div class="feedback-incorrect">
        <div class="feedback-icon">❌</div>
        <div class="feedback-content">
          <strong>Incorrecto</strong><br>
          La respuesta correcta es: <strong>${correctAnswer}</strong><br>
          ${explanations[questionNum]}
        </div>
      </div>
    `;
    selected.parentElement.style.background = '#ffd4d4';
    selected.parentElement.style.borderColor = '#f44336';
    
    // Resaltar la respuesta correcta
    const correctOption = document.getElementById(`q${questionNum}${correctAnswer.toLowerCase()}`).parentElement;
    correctOption.style.background = '#d4f4dd';
    correctOption.style.borderColor = '#4caf50';
  }
  
  feedback.style.display = 'block';
}
</script>

---

## 🎯 Cómo Funciona

1. **Lee cada pregunta** y selecciona la opción que consideres correcta
2. **Haz clic en "Verificar Respuesta"** en cada pregunta para ver si acertaste
3. **Recibe feedback inmediato**: ✅ correcto o ❌ incorrecto con la explicación

Cada pregunta se valida individualmente para que puedas aprender mientras avanzas.

---

## 📚 Próximos Pasos

1. **Experimentá con el código**: Modificá el servidor y cliente para agregar nuevas funcionalidades
2. **Explorá la documentación oficial**: [MCP Documentation](https://modelcontextprotocol.io/)
3. **Compartí tu experiencia**: Contanos en el [canal de Slack](https://tinyurl.com/slack-bigcheese) qué te pareció el workshop
4. **Obtené tu voucher AWS**: Completá la [encuesta](https://tinyurl.com/encuesta-bigcheese) para recibir créditos de AWS

---

## 🎓 Certificado

¡Felicitaciones por completar el BigCheese MCP Workshop! Has aprendido a:

✅ Entender los fundamentos del Model Context Protocol  
✅ Implementar un servidor MCP con Tools, Resources y Prompts  
✅ Crear un cliente MCP integrado con AWS Bedrock  
✅ Construir aplicaciones inteligentes con contexto estandarizado  

**¡Gracias por participar!** 🎉

---

[← Módulo 13: Repaso](./Modulo-13-Repaso-Las-Tres-Primitivas.md) | [Volver al Inicio](../docs/index.html)
