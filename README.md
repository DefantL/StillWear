# StillWear — Sustainable Streetwear E-Commerce

> *Stillness in a fast world.* Moda streetwear etica, prodotta in piccole tirature con cotone organico certificato GOTS e materiali riciclati.

Progetto realizzato dall'agenzia web **StillWear** (Classe 5ª Informatica) su commissione della **Prof.ssa Valentina Villani** e di **Miriam Sutera**[cite: 1].

---

## 1. Il Brand e la Visione Commerciale

**StillWear** nasce per contrastare il fast fashion unendo l'estetica urban/oversize alla sostenibilità ambientale[cite: 1]:

* **Materiali Certificati:** 100% cotone organico pettinato e inchiostri ad acqua atossici[cite: 1].
* **Drop Limitati:** Ogni capo è prodotto in quantità numerate per evitare sprechi di magazzino e garantire esclusività[cite: 1].
* **Trasparenza e Guida alle Taglie:** Schede prodotto dettagliate con vestibilità (*boxy fit*, *oversize*) e guida alle taglie integrata per ridurre i resi[cite: 1].

---

## 2. Stack Tecnologico e Architettura

Il progetto è sviluppato interamente in tecnologia **Vanilla Web** (nessun framework JS esterno)[cite: 1], puntando su prestazioni, pulizia del codice e compatibilità:

* **HTML5 Semantico:** Struttura accessibile (`<header>`, `<main>`, `<section>`, `<dialog>` / `<aside>` per modali e drawer).
* **CSS3 Moderno:**
  * **CSS Grid** per il catalogo prodotti responsive.
  * **Flexbox** per la barra di navigazione, i filtri e il layout interno del carrello.
  * **Custom Properties (Variabili CSS)** per gestire la palette colori organica (verde salvia, sabbia, antracite, bianco sporco).
* **JavaScript (ES6+):**
  * Caricamento dinamico del catalogo da struttura dati (`products.json` / array di oggetti)[cite: 1].
  * Motore di ricerca in tempo reale, filtro per categoria e ordinamento per prezzo[cite: 1].
  * Gestione dello stato del carrello con persistenza tramite `localStorage`.
  * Validazione lato client del form di checkout tramite Constraint Validation API e Regex[cite: 2].

---

## 3. Avvio del Progetto in Locale

*(Sezione richiesta dal capitolato: compilala non appena create i file base)*[cite: 2]

1. Clona il repository:
   ```bash
   git clone [https://github.com/DefantL/StillWear.git](https://github.com/DefantL/StillWear.git)
