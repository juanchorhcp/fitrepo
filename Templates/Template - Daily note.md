# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

<< [[Timestamps/<% tp.date.now("YYYY", -1) %>/<% tp.date.now("MM-MMMM", -1) %>/<% tp.date.now("YYYY-MM-DD-dddd", -1) %>|Yesterday]] | [[Timestamps/<% tp.date.now("YYYY", 1) %>/<% tp.date.now("MM-MMMM", 1) %>/<% tp.date.now("YYYY-MM-DD-dddd", 1) %>|Tomorrow]] >>

---
# [[🌅Morning pages]]
_(escribir sin filtro, sin corregir, sin releer)_





---

# 📝 Nota rápida 
- <% tp.file.cursor() %>

---

## 🎯 Algo que me gustaría hacer hoy
_(realista, humano, no épico)_
- [ ] 

---

## 🧠 Algo con lo que estoy struggling
- ¿Qué es?
- ¿Qué lo hace difícil?
- ¿Qué emoción aparece primero?

---

## 💭 En qué está girando mi cabeza
- Pensamiento recurrente:
- Preocupación no invitada:
- Idea que apareció sin contexto:

---

## ✨ Algo que me emociona
_(aunque sea chiquito o a futuro)_

---

## 🧠 Algo que pensé ayer
_(rescate del día anterior)_
 
---

## 🏆 Logros del día 
- Algo que hice bien ayer/hoy:
- Algo que evité hacer y estuvo bien:

---

## 🎨 Chispa creativa (captura rápida)
- Imagen / escena:
- Sonido / textura / ruido:
- Frase:
- Idea sin juzgar:

---

## 🎵 Registro creativo — Música & Sonido
_(no hace falta completar todo)_

- 🎧 **Sonido del día:**  
  (ambiente, ruido, textura, sample mental)
- 🧪 **Idea sonora:**  
  (procesamiento, efecto, cadena, concepto)
- 🎼 **Canción del día:**
- 🧠 **Referencia que apareció:**  
  (tema, OST, artista, juego, película)
- 🛠️ **¿Probé algo técnico hoy?**  
  (plugin, mic, técnica, error interesante)

---

## 🎮 Registro creativo — Juegos / Mundos
- 🎮 **Juego de hoy:** 
- 🗺️ **Idea de mundo / escenario:**
- 👤 **Personaje:**
- ⚔️ **Mecánica:**
- 🎭 **Tono emocional:**  
- 🔊 **Idea de sonido para gameplay:**  

---
## 📚 Registro creativo — Libros
- 📕 **Libro de hoy:** 
- 🗺️ **Idea de mundo / escenario:**
- 👤 **Personaje:**
- ✍🏼 **Frase interesante:** 
- 🎭 **Tono emocional:**  
- 📝 **Idea de plot:**  
  
---
## ❔ Pregunta del día
*Ej: ¿Qué estoy evitando mirar? ¿Esto es miedo o intuición? ¿Qué necesita mi parte creativa hoy? ¿Estoy creando o solo preparándome para crear?*

---

## 🌙 Mini cierre
- Pregunta que ronda en mi cabeza:
- Necesito ser guiado en:


*... por la mañana quizás escuche alguna respuesta*


---

#### 🧠 Conecta con:

#### 🏷Tags: [[Daily Notes]]
---
---
### Notes created today
```dataview
List FROM "" WHERE file.cday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.ctime asc
```

### Notes last touched today
```dataview
List FROM "" WHERE file.mday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.mtime asc
```