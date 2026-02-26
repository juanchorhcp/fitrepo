# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

<< [[Timestamps/<% tp.date.now("YYYY", -1) %>/<% tp.date.now("MM-MMMM", -1) %>/<% tp.date.now("YYYY-MM-DD-dddd", -1) %>|Yesterday]] | [[Timestamps/<% tp.date.now("YYYY", 1) %>/<% tp.date.now("MM-MMMM", 1) %>/<% tp.date.now("YYYY-MM-DD-dddd", 1) %>|Tomorrow]] >>

---
# [[🌅Morning pages]]
_Escribir sin filtro, sin corregir, sin releer_


---
## ⌚ Daily log
*Poner horario y actividades*


---
## 🎯 Algo que me gustaría hacer hoy
*Realista, humano, no épico*


---
## 🧠 Algo con lo que estoy struggling
*¿Qué es? ¿Qué lo hace difícil? ¿Qué emoción aparece primero?*



---
## ✨ Algo que me emociona


---

## 🧠 Algo que pensé ayer

 
---

## 🏆 Logros del día 


---

## 🎵 Registro creativo — Música, juegos, libros



---

## 🌙 Mini cierre
*Pregunta que ronda en mi cabeza/Necesito ser guiado en*…
*…por la mañana quizás escuche alguna respuesta*



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