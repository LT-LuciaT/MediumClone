# 🚀 Ricreazione della Homepage di Medium.com

## 📝 Descrizione
Questo progetto consiste nella **ricreazione fedele** della pagina principale di [Medium.com](https://medium.com) in versione desktop, utilizzando:

- **HTML5** per la struttura
- **CSS3** per stili e layout (Flexbox, Positioning)
- **JavaScript** per le interazioni

# 🎯 Funzionalità Implementate

✔ **Layout Responsivo** - Struttura della pagina ottimizzata per desktop, con l'uso di Flexbox e CSS Positioning.  
✔ **Navbar Animata**  
   - Cambia colore da giallo a bianco durante lo scroll  
   - Bottone principale che passa da nero a verde  
   - Animazione attivata poco prima che la navbar esca dalla sezione hero (gialla)  
✔ **Effetto Fade-in** - Animazione CSS per una transizione fluida degli elementi  
✔ **Gestione dello Scroll Event** - Utilizzo di JavaScript per attivare le animazioni al momento giusto  

## 🛠️ Tecnologie Utilizzate

- **HTML5** → Struttura della pagina  
- **CSS3** → Stile, animazioni e layout (Flexbox, Positioning)  
- **JavaScript** → Gestione degli eventi di scroll e interazioni dinamiche  

# 🚀 Dettagli Implementativi

## 🟡 Navbar Animata
- **Stato iniziale:**  
  - Sfondo giallo  
  - Bottone nero (quando nella sezione hero)
  
- **Durante lo scroll:**  
  - JavaScript rileva la posizione dello scroll e attiva la transizione  
  - La navbar diventa **bianca** e il bottone diventa **verde**  
  - Effetto smooth grazie a **CSS transitions**

---

## 🖼 Sezione Hero
- Sfondo giallo con **titolo** e **call-to-action**
- La navbar rimane gialla finché l’utente non scrolla oltre questa sezione

---

## ✨ Effetto Fade-in
- Alcuni elementi (come i **post suggeriti**) appaiono con un fade-in per migliorare l’esperienza utente

---

## 🎥 Demo Animata

![Funzionamento della navbar](assets/demo/demo.gif)

---

## 📌 Note
- Il progetto è ottimizzato per **desktop**
- Le animazioni sono state testate su **Chrome**, **Firefox** e **Edge**

---

## 👨‍💻 Autore
[Lucia Trombin] - [LT-LuciaT]
