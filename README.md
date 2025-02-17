# 📚 Generador de Contenido Educativo con Gemini y Nightcafe  

Este proyecto utiliza **Gemini** para generar explicaciones educativas claras y concisas, y **Nightcafe** para convertir esas explicaciones en **imágenes visualmente explicativas**. La app está diseñada para **simplificar el aprendizaje**, presentando información compleja en un formato accesible y atractivo.  

---

## 🚀 Funcionalidades  

- **Generación de Texto Educativo**: Utiliza Gemini para responder preguntas de manera breve y fácil de entender.  
- **Imágenes Ilustrativas**: Convierte las respuestas generadas en imágenes educativas mediante Nightcafe.  
- **Ejemplos Concretos y Visuales**: Las respuestas son simples y contienen ejemplos fáciles de visualizar.  

---

## ⚙️ ¿Cómo Funciona?  

1. **Entrada de Pregunta**  
   - El usuario ingresa una **pregunta educativa**.  
     ```python
     pregunta = "¿Qué es una célula eucariota?"
     respuesta = respuesta_educacion(pregunta)
     print(respuesta)
     ```

2. **Generación de Texto con Gemini**  
   - La app utiliza **Gemini** para generar una **explicación breve y concisa**.  
   - La respuesta se presenta en **3 oraciones simples**, con ejemplos **concretos y visuales** para facilitar el entendimiento.  
   - Ejemplo de respuesta:  
     ```
     Una célula eucariota tiene un núcleo definido. Dentro, guarda su ADN en estructuras llamadas cromosomas. Un ejemplo son las células de los animales y plantas.
     ```

3. **Conversión de Texto a Imagen con Nightcafe**  
   - La explicación generada se copia y se pega manualmente en **Nightcafe** para crear una **imagen educativa** basada en el texto.  
   - La imagen resultante **ilustra el concepto explicado**, ayudando al usuario a visualizar la información.  

---

## 🛠️ Requisitos  

- Python 3.x  
- `google.generativeai` para el uso de Gemini  
- Cuenta en Nightcafe para la generación de imágenes

---

## ▶️ Uso  

1. Configura tu clave de API para Gemini:  
    ```python
    genai.configure(api_key="TU_CLAVE_DE_API")
    ```

2. Ingresa tu pregunta educativa en el código y ejecuta el script.  
3. Copia la respuesta generada y pégala en Nightcafe para generar la imagen correspondiente.  

---

## 📚 Ejemplos de Preguntas  

- ¿Qué es una célula eucariota?  
- ¿Cómo ocurre la fotosíntesis?  
- ¿Qué es la gravedad?  

---

## 📝 Notas  

- **Nightcafe** se utiliza manualmente para la generación de imágenes.  
- La app está optimizada para **respuestas educativas breves y visuales**.  

---
