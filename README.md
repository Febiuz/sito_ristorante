# 🏔️ Ristorante del Margaro - Website Project

![Preview del Sito](https://via.placeholder.com/1000x500?text=Inserisci+qui+uno+Screenshot+del+Sito)
> *Un'esperienza digitale che porta i sapori della tradizione alpina sul web.*

## 🌐 Live Demo
[**Clicca qui per vedere il sito online**](https://dark-sky-ee4c.fabiogrosso38.workers.dev/)

---

## 📋 Descrizione del Progetto

Questo progetto consiste nello sviluppo di un sito web multipagina per il "Ristorante del Margaro", un locale fittizio che fonde tradizione culinaria e modernità.

L'obiettivo principale era costruire un'interfaccia **completamente responsive** e visivamente accattivante utilizzando **puro HTML e CSS**, senza dipendere da framework esterni come Bootstrap. Questo mi ha permesso di avere il controllo totale sul layout e sulle performance.

Il sito comprende 4 pagine distinte:
1.  **Home:** Hero section d'impatto e storytelling del brand.
2.  **Menu:** Layout a card responsive per la visualizzazione dei piatti.
3.  **Gift Card:** Sezione dedicata all'acquisto di voucher.
4.  **Chi Siamo:** Pagina informativa sulla storia e filosofia del locale.

## 🛠️ Tecnologie Utilizzate

* **HTML5 Semantico:** Uso corretto dei tag (`<nav>`, `<section>`, `<footer>`) per migliorare la struttura e la SEO.
* **CSS3 Moderno:**
    * **Flexbox:** Utilizzato estensivamente per il layout delle card, la navbar e l'allineamento dei contenuti.
    * **Responsive Design:** 3 Breakpoints personalizzati (`1200px`, `900px`, `480px`) per garantire la leggibilità su ogni dispositivo.
    * **CSS Variables & Gradients:** Per la gestione coerente dei colori e degli overlay sulle immagini.
* **Font Awesome:** Per le icone dei social media.
* **Google Fonts:** Tipografia curata con il font *Cormorant SC*.

## ✨ Funzionalità e Sfide Tecniche

Durante lo sviluppo mi sono concentrato su diverse sfide tecniche per rendere il sito professionale:

### 1. Responsive "Mobile-First" approach
Ho gestito manualmente le media queries per adattare il layout.
* **Desktop:** Layout espanso con navigazione orizzontale.
* **Tablet/Mobile:** Adattamento delle dimensioni dei font (`rem`), riposizionamento della navbar e trasformazione delle griglie dei piatti in colonne singole per facilitare lo scroll.

### 2. Design delle Card (Menu & Gift)
Ho creato un sistema di card flessibile utilizzando:
```css
.card-piatto {
    flex: 1 1 300px; /* La card cresce e si restringe ma mantiene una base ideale */
    box-shadow: -10px 10px 20px rgba(0,0,0,0.5); /* Effetto profondità */
}
