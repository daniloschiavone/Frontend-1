# Istruzioni Portfolio - GitHub Copilot

> File di istruzioni per lo sviluppo del portfolio personale
> Junior System Administrator / Fullstack Developer

---
# !!MUST!! 
## STYLING RULE [PRIORITY: CRITICAL]:

Utilizza esclusivamente Bootstrap per tutto il CSS e il layout.

È severamente vietato scrivere CSS custom (fogli di stile esterni o tag <style>) a meno che non sia strettamente necessario per sovrascrivere comportamenti di Bootstrap non configurabili.

Usa le utility class di Bootstrap (es. d-flex, mt-5, text-center) per ogni modifica stilistica.

Framework: Bootstrap (Ultima versione stabile).

Implementation: Includi sempre i link CDN di Bootstrap nel <head> e prima della chiusura del <body>.

Constraint: Non generare codice che richieda file CSS aggiuntivi. Se una proprietà esiste in Bootstrap, usa quella.



## 🎯 Obiettivo del Progetto

Creare un portfolio professionale che mostri competenze in:
- Sviluppo fullstack
- System administration
- Hardware repair & troubleshooting
- Scripting e automazione

---

## 📐 Struttura del Portfolio

### 1. Home

**Sezione di ingresso con identità professionale**

Contenuti:
- Nome e ruolo: **Junior System Administrator / Fullstack Developer**
- Breve presentazione (3–4 righe)
- Competenze chiave
- Pulsanti rapidi:
  - Progetti
  - Competenze
  - Contatti
- Eventuale immagine o illustrazione tecnica

**Elementi utili:**
- Tagline tipo: *"Troubleshooting, scripting e infrastrutture IT."*

---

### 2. Chi Sono (About)

**Racconto tecnico del tuo percorso**

Contenuti possibili:
- Come è nata la passione per l'informatica
- Esperienza con hardware e troubleshooting
- Interesse per:
  - Scripting
  - Virtualizzazione
  - Database
  - Sviluppo web
- Formazione attuale
- Obiettivi professionali

**Sezioni interne:**

#### Background tecnico
- Assemblaggio PC
- Riparazione hardware
- Installazione sistemi operativi

#### Filosofia di lavoro
Esempio:
1. Analisi del problema
2. Debugging
3. Soluzione documentata

---

### 3. Competenze Tecniche

**Dividere per categorie**

#### Sviluppo Software
- HTML
- CSS
- JavaScript
- Database SQL
- Logica di programmazione
- Sviluppo full-stack (in formazione)

#### Sistemi e Infrastruttura
- Linux server
- Windows
- Virtualizzazione
- Gestione VM
- Networking base

#### Dev / Automation
- Scripting
- Automazione task
- Debugging
- Analisi log

#### Hardware & Repair
- Assemblaggio PC
- Upgrade componenti
- Troubleshooting hardware
- Riparazione smartphone
- Sostituzione componenti

---

### 4. Progetti

**⚠️ Parte più importante del portfolio**

#### Struttura per ogni progetto:
- Nome progetto
- Descrizione
- Problema risolto
- Tecnologie usate
- Screenshot
- Link GitHub (se presente)

#### Esempi di progetti da inserire:

**Portfolio Website**
- Il sito stesso come progetto

**Script di automazione**
- Script per:
  - Gestione server
  - Backup
  - Manutenzione

**Database Project**
- Applicazione con database:
  - Gestione utenti
  - CRUD operations

**Sistema virtualizzato**
- Ambiente con VM:
  - Linux server
  - Servizi configurati

**Progetto logistico**
- Il progetto fatto nel corso

---

### 5. Laboratorio Tecnico / Repair

**Questa sezione ti differenzia dagli sviluppatori puri**

#### Riparazioni PC
- Sostituzione SSD
- Upgrade RAM
- Reinstallazione OS
- Diagnosi hardware

#### Riparazioni smartphone
- Sostituzione batteria
- Display
- Recovery software

#### Troubleshooting
Esempi di problemi risolti:
- Boot failure
- Corruzione sistema
- Recupero dati

---

### 6. Stack Tecnologico

**Pagina con le tecnologie usate**

#### Frontend
- HTML
- CSS
- JavaScript

#### Backend
- Node.js / altri (se studiati)

#### Database
- SQL
- Supabase (se lo usi)

#### Infrastructure
- Linux
- Virtual machines
- Container (se li studierai)

---

### 7. Blog Tecnico (facoltativo ma molto potente)

**Articoli brevi tipo:**
- Come diagnosticare un PC che non avvia
- Come creare una VM Linux
- Troubleshooting di rete
- Come funziona un database semplice

**Vantaggi:**
- Migliora SEO
- Aumenta autorevolezza tecnica
- Dimostra capacità di documentazione

---

### 8. GitHub / Codice

**Pagina che mostra:**
- Repository
- Snippet
- Contributi

**Contenuti:**
- Link GitHub
- Progetti open source
- Esercizi di codice

---

### 9. Curriculum

**Download del CV**

Contenuti:
- Esperienza
- Formazione
- Competenze
- Certificazioni

---

### 10. Contatti

**Metodi per contattarti**

- Email
- GitHub
- LinkedIn
- Eventuale form contatti

---

## 🎨 Design System

### Tema "Developer / Terminal" (consigliato)

Richiama ambienti Linux e sviluppo

#### Colori Principali

```css
/* Background */
--bg-primary: #0f172a;
--bg-secondary: #1e293b;
--bg-card: #111827;

/* Text */
--text-primary: #e5e7eb;
--text-secondary: #94a3b8;

/* Actions */
--color-primary: #22c55e;
--color-primary-hover: #16a34a;

/* Accents */
--accent-blue: #38bdf8;
--accent-orange: #f59e0b;
```

#### Struttura cromatica delle componenti

| Componente | Colore |
|------------|--------|
| Navbar | `#0f172a` |
| Sezioni | `#1e293b` |
| Cards progetti | `#111827` |
| Bottoni | `#22c55e` |
| Hover bottoni | `#16a34a` |

**Aspetto:**
Dark mode tecnico molto pulito

---

## 🔤 Typography

### Font ideali

#### Titoli (monospace per aspetto tecnico):
- **JetBrains Mono**
- **Fira Code**

#### Testo (sans-serif leggibile):
- **Inter**
- **Roboto**

#### Implementazione

```css
/* Titoli */
font-family: 'JetBrains Mono', 'Fira Code', monospace;

/* Testo corpo */
font-family: 'Inter', 'Roboto', sans-serif;
```

---

## ✨ Dettagli Estetici

**Elementi che migliorano molto il portfolio:**

### Effetti visivi
- ✅ Glow leggero sui pulsanti
- ✅ Griglia tecnica di sfondo
- ✅ Animazioni hover
- ✅ Icone tecniche

### Esempi CSS

```css
/* Glow sui bottoni */
.btn-primary {
  box-shadow: 0 0 20px rgba(34, 197, 94, 0.3);
  transition: all 0.3s ease;
}

.btn-primary:hover {
  box-shadow: 0 0 30px rgba(34, 197, 94, 0.5);
  transform: translateY(-2px);
}

/* Griglia tecnica di sfondo */
body::before {
  content: '';
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: 
    linear-gradient(rgba(34, 197, 94, 0.05) 1px, transparent 1px),
    linear-gradient(90deg, rgba(34, 197, 94, 0.05) 1px, transparent 1px);
  background-size: 50px 50px;
  pointer-events: none;
  z-index: -1;
}
```

---

## 📱 Responsive Design

### Breakpoints consigliati

```css
/* Mobile */
@media (max-width: 640px) { }

/* Tablet */
@media (min-width: 641px) and (max-width: 1024px) { }

/* Desktop */
@media (min-width: 1025px) { }
```

---

## 🚀 Tecnologie Consigliate

### Stack minimo
- HTML5
- CSS3 (o Tailwind CSS per velocità)
- JavaScript vanilla
- Git/GitHub

### Stack avanzato (opzionale)
- React / Vue / Svelte
- Tailwind CSS
- Vite / Webpack
- Netlify / Vercel (hosting)

---

## 📋 Checklist Sviluppo

### Fase 1: Setup
- [ ] Struttura cartelle progetto
- [ ] Setup Git repository
- [ ] Configurazione font (Google Fonts)
- [ ] Setup variabili CSS

### Fase 2: Componenti
- [ ] Navbar responsive
- [ ] Hero section (Home)
- [ ] Cards progetti
- [ ] Form contatti
- [ ] Footer

### Fase 3: Sezioni
- [ ] Home
- [ ] Chi Sono
- [ ] Competenze
- [ ] Progetti
- [ ] Laboratorio Tecnico
- [ ] Stack Tecnologico
- [ ] Contatti

### Fase 4: Ottimizzazione
- [ ] Responsive design
- [ ] Performance (lazy loading immagini)
- [ ] SEO (meta tags)
- [ ] Accessibilità (ARIA labels)

### Fase 5: Deploy
- [ ] Test cross-browser
- [ ] Deploy su Netlify/Vercel/GitHub Pages
- [ ] Google Analytics (opzionale)
- [ ] Custom domain (opzionale)

---

## 💡 Best Practices

### Codice
- Usa nomi semantici per classi CSS
- Commenta sezioni complesse
- Mantieni file CSS organizzati
- Usa variabili CSS per colori e spacing

### Contenuti
- Progetti con descrizioni chiare
- Screenshot di qualità
- Link funzionanti
- Testi senza errori

### Performance
- Ottimizza immagini (WebP, compressione)
- Minifica CSS/JS
- Lazy loading per immagini
- Usa CDN per font

---

## 🔗 Risorse Utili

### Icone
- [Lucide Icons](https://lucide.dev/) - Icone moderne e pulite
- [Font Awesome](https://fontawesome.com/) - Icone classiche
- [Heroicons](https://heroicons.com/) - Icone Tailwind

### Strumenti
- [GitHub Pages](https://pages.github.com/) - Hosting gratuito
- [Netlify](https://www.netlify.com/) - Deploy automatico
- [ColorHunt](https://colorhunt.co/) - Palette colori
- [CSS Grid Generator](https://cssgrid-generator.netlify.app/)

### Ispirazione
- [GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [DevFolio Templates](https://www.devfolio.co/)

---

## 📝 Note Aggiuntive

### SEO Base
```html
<meta name="description" content="Portfolio di [Nome] - Junior System Administrator e Fullstack Developer specializzato in troubleshooting, scripting e infrastrutture IT">
<meta name="keywords" content="system administrator, fullstack developer, troubleshooting, IT, hardware repair">
<meta property="og:title" content="[Nome] - System Admin & Developer">
<meta property="og:description" content="Portfolio tecnico con progetti di sviluppo, system administration e riparazione hardware">
```

### Accessibility
- Usa tag semantici (`<nav>`, `<main>`, `<section>`, `<article>`)
- Contrasto colori sufficiente (WCAG AA)
- Alt text per immagini
- Focus indicators visibili

---

## 🎯 Obiettivi Finali

**Il portfolio deve comunicare:**
1. ✅ Competenze tecniche variegate
2. ✅ Capacità problem-solving
3. ✅ Approccio pratico e concreto
4. ✅ Passione per la tecnologia
5. ✅ Professionalità

---

*Ultimo aggiornamento: Marzo 2026*
