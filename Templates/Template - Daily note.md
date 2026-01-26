---
created: <% tp.file.creation_date() %>
---
tags: [[Daily Notes]]

# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

<< [[Timestamps/<% tp.date.now("YYYY", -1) %>/<% tp.date.now("MM-MMMM", -1) %>/<% tp.date.now("YYYY-MM-DD-dddd", -1) %>|Yesterday]] | [[Timestamps/<% tp.date.now("YYYY", 1) %>/<% tp.date.now("MM-MMMM", 1) %>/<% tp.date.now("YYYY-MM-DD-dddd", 1) %>|Tomorrow]] >>

---
### 📅 Daily Questions
##### 🌜 Algo que pense anoche:
- 

##### 🙌 Algo que me emociona es:
- 


##### 👎 Algo con lo que estoy struggling:
- 

---
# [[🌅Morning pages]]
_(escribir sin filtro, sin corregir, sin releer)_





---

# 📝 Notes
- <% tp.file.cursor() %>


---

## 🌅 Check-in rápido
- **Cómo me siento (1 palabra):**
- **Nivel de energía:** 🔋▢▢▢▢▢
- **Clima interno:** (calmo / ansioso / disperso / enfocado / nublado)

---

## 🎯 Algo que me gustaría hacer hoy
_(realista, humano, no épico)_
 - [ ] 
---

## 🧠 Algo con lo que estoy struggling
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

## 🎯 UNA sola cosa (anti-overwhelm)
**Si hoy solo hiciera UNA cosa, sería:**

---

## 🏆 Logros del día 
- Algo que hice bien hoy:
- Algo que evité hacer y estuvo bien:

---

## 🎨 Chispa creativa (captura rápida)
- Imagen / escena:
- Sonido / textura / ruido:
- Frase suelta:
- Idea sin juzgar:

---

## 🎵 Registro creativo — Música & Sonido
_(no hace falta completar todo)_

- 🎧 **Sonido del día:**  
  (ambiente, ruido, textura, sample mental)
- 🧪 **Idea sonora:**  
  (procesamiento, efecto, cadena, concepto)
- 🎼 **Estado musical:**  
  (armónico / rítmico / atmosférico / caótico / minimal)
- 🧠 **Referencia que apareció:**  
  (tema, OST, artista, juego, película)
- 🛠️ **¿Probé algo técnico hoy?**  
  (plugin, mic, técnica, error interesante)

---

## 🎮 Registro creativo — Juegos / Mundos
- 🎮 **Juego de hoy:** 
- 🗺️ **Idea de mundo / escenario:**
- 👤 **Personaje que apareció hoy:**
- ⚔️ **Mecánica o interacción interesante:**
- 🎭 **Tono emocional del juego hoy:**  
  (opresivo / lúdico / melancólico / absurdo / tenso)
- 🔊 **Idea de sonido para gameplay:**  
  (ataque, UI, ambiente, feedback)

---
## 📚 Registro creativo — Libros
- 📕 **Libro de hoy:** 
- 🗺️ **Idea de mundo / escenario:**
- 👤 **Personaje de hoy:**
- ✍🏼 **Frase interesante:** 
- 🎭 **Tono emocional del libro hoy:**  
  (opresivo / lúdico / melancólico / absurdo / tenso)
- 📝 **Idea de plot:**  
  
---
## 🪞 Pregunta del día
_(elegir una o escribir otra)_
- ¿Qué estoy evitando mirar?
- ¿Esto es miedo o intuición?
- ¿Qué necesita mi parte creativa hoy?
- ¿Estoy creando o solo preparándome para crear?

---

## 🌙 Mini cierre
- Algo por lo que agradezco hoy:
- Algo que solté:
- Cómo me iría a dormir si hoy terminara acá:
- Pregunta que ronda en mi cabeza:

---

## 🧠 Meta-nota (Obsidian mode)
- ¿Esto conecta con algo más?  
  `[[proyecto]] [[idea]] [[bloqueo]]`
- ¿Alguna de estas ideas merece nota propia? ☐
- Tags suaves:  
  `#diaria #animo/ #creatividad/`

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