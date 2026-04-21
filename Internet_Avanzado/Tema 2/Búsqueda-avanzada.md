# 🌐 Tema: Búsquedas avanzadas en Internet y qué es el Google Dorking

## 1. ¿Qué es una búsqueda avanzada?
Las búsquedas avanzadas son **herramientas para encontrar mejor**.  

Cuando usamos un buscador como Google, normalmente escribimos una palabra o frase y esperamos que aparezcan resultados útiles. Sin embargo, **podemos mejorar mucho la precisión** de lo que encontramos si usamos **operadores de búsqueda avanzada**.

Los operadores son **símbolos o palabras especiales** que ayudan a Google a entender exactamente qué queremos.

---

## 🔎 2. Operadores básicos de búsqueda avanzada

### **a) Buscar una frase exacta**
- **Operador:** comillas `" "`
- **Ejemplo:**  
  `"cómo plantar tomates"`  
  Google solo mostrará páginas donde aparezca esa frase exacta.

### **b) Excluir palabras**
- **Operador:** guion `-`
- **Ejemplo:**  
  `manzanas -recetas`  
  Buscará información sobre manzanas, pero **sin** resultados de recetas.

### **c) Buscar dentro de una web concreta**
- **Operador:** `site:`
- **Ejemplo:**  
  `site:unicef.org educación`  
  Muestra solo resultados de la web de UNICEF relacionados con educación.

### **d) Buscar un tipo de archivo**
- **Operador:** `filetype:`
- **Ejemplo:**  
  `huerto escolar filetype:pdf`  
  Google mostrará únicamente documentos PDF sobre huertos escolares.

### **e) Buscar palabras obligatorias**
- **Operador:** `+`
- **Ejemplo:**  
  `reciclaje +plástico`  
  Asegura que la palabra “plástico” aparezca en los resultados.

### **f) Buscar sin recordar el nombre exacto**
- **Operador:** asterisco `*` (comodín)
- **Ejemplo:**  
  `"plantar * en primavera"`  
  Google completará el asterisco con distintas opciones.

---

## 🧭 3. Combinación de operadores
Los operadores se pueden mezclar para hacer búsquedas muy precisas.

Ejemplo:
```
"cultivo ecológico" filetype:pdf site:edu
```
Esto busca **PDF educativos** que contengan la frase “cultivo ecológico”.

---

## ⚠️ 4. ¿Qué es el Google Dorking?

El Google Dorking es **una técnica que demuestra que Google encuentra más de lo que imaginamos**, por lo que debemos ser cuidadosos con lo que publicamos.

El **Google Dorking** (también llamado *Google Hacking*) es una técnica que utiliza **operadores avanzados** para encontrar información muy específica que, en ocasiones, **no debería ser pública**.

Es importante explicarlo **solo desde un punto de vista educativo y de ciberseguridad**, nunca para usos indebidos.

### ¿En qué consiste?
Consiste en usar operadores como:
- `site:`
- `filetype:`
- `"texto exacto"`
- `intitle:` (buscar en el título)
- `inurl:` (buscar en la dirección web)

…para localizar información que está accesible en Internet, pero que **no siempre ha sido configurada correctamente** por los administradores de una web.

### ¿Para qué se explica en cursos de informática?
- Para **concienciar** sobre la importancia de proteger bien la información.
- Para entender que **todo lo que se publica en Internet puede ser encontrado**.
- Para aprender a **configurar correctamente** páginas, documentos y servicios.

### Ejemplo educativo (seguro y ético)
```
intitle:"index of" recetas
```
Esto muestra listados públicos de carpetas que contienen la palabra “recetas”.  
Es un ejemplo inocuo que sirve para explicar cómo funciona la técnica.

### Importante
El Google Dorking **no es ilegal por sí mismo**, pero **puede usarse de forma indebida** si se buscan datos privados o mal protegidos. Por eso, en educación se enseña **solo para aprender a protegerse**, nunca para acceder a información sensible.

---
