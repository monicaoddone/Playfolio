# Playfolio [ITA]
Un’alternativa “giocabile” al portfolio tradizionale

Panoramica

Playfolio è un tool sperimentale per la generazione di portfolio, progettato per un mondo in cui l’intelligenza artificiale è già una presenza diffusa e matura.

Invece di concentrarsi su ruoli, titoli o lunghe liste di competenze, Playfolio mira a rendere visibile la dimensione umana del lavoro:
come una persona pensa, prende decisioni, collabora, reagisce alla complessità e genera valore.

L’output non è un CV.
È una Playfolio Card — una rappresentazione dell’identità professionale ispirata alle carte da gioco e al linguaggio del play, ma radicata in contesti di lavoro reali.

Idea alla base

Hai raggiunto il successo nel tuo campo quando non sai più se quello che stai facendo è lavoro o gioco.
— Warren Beatty

Playfolio parte da questa intuizione e riformula il modo in cui raccontiamo il lavoro.

In un contesto in cui l’AI è già in grado di generare, ottimizzare ed eseguire, ciò che distingue davvero le persone è:

il giudizio

l’intenzione

i valori

il gusto

i pattern di comportamento

Playfolio è progettato per rendere questi elementi visibili, confrontabili e condivisibili.

Come funziona

Playfolio è implementato come un Master Prompt, utilizzabile in autonomia con qualsiasi Large Language Model (LLM), incluse le versioni gratuite di:

ChatGPT

Claude

Gemini

altri modelli compatibili

Il processo

L’utente incolla il Master Prompt nel modello AI che preferisce.

L’AI avvia una conversazione guidata ed empatica in italiano, ponendo una serie di domande strutturate.

L’AI sintetizza le informazioni raccolte.

L’output finale consiste in:

un breve blocco di istruzioni per l’utente

una Playfolio Card in HTML, pronta per essere copiata in Notion, in una pagina web o esportata come PDF/immagine tramite strumenti del browser.

Non sono necessarie API, automazioni o strumenti a pagamento.

Perché un Master Prompt (e non una piattaforma)

Il progetto evita intenzionalmente la creazione di una piattaforma proprietaria o di un servizio chiuso.

Scegliere un Master Prompt come artefatto principale garantisce:

accessibilità (funziona anche con piani gratuiti)

apertura (nessun vendor lock-in)

adattabilità (indipendente dal modello)

facilità di diffusione e riuso

Nel contesto dell’hackathon, questa scelta ha permesso di concentrarsi su concept, interaction design e qualità dell’output, invece che sull’infrastruttura tecnica.

Output: la Playfolio Card

Ogni Playfolio Card include:

Nome e archetipo professionale

Playground principale (ambito)

Parole chiave umane

Superpoteri (abilità sintetiche)

Vulnerabilità (solo etichetta)

Valori chiave

Signature move

Impatto dei progetti

Pattern osservati

Synergy score con altri profili professionali

La card è progettata per essere:

mobile-first

facilmente scansionabile

confrontabile con altre

collezionabile in una galleria condivisa

Archetipi

Playfolio utilizza un set fisso di archetipi professionali (es. Sensemaker, Builder, Strategist, Challenger, ecc.) per classificare i profili.

Gli archetipi:

sono definiti internamente nel Master Prompt

vengono inferiti dall’AI in base ai comportamenti, non ai ruoli dichiarati

bilanciano una dimensione giocosa con una analitica

La classificazione è intenzionalmente leggera e interpretativa, non deterministica.

Accessibilità e compatibilità con piani gratuiti

Un vincolo progettuale fondamentale di Playfolio è l’accessibilità.

Il Master Prompt è progettato per funzionare anche con:

account LLM gratuiti

limiti di messaggi

accesso parziale o assente a risorse esterne (link, PDF)

Se le risorse esterne non sono accessibili, l’AI è istruita a inferire i pattern esclusivamente dalle risposte fornite dall’utente, senza interrompere l’esperienza.

Questo rende Playfolio utilizzabile da giurati, partecipanti e utenti futuri senza necessità di abbonamenti o crediti a pagamento.

Limiti e sviluppi futuri
Coerenza del layout

Attualmente, il Master Prompt definisce:

una struttura semantica fissa della Playfolio Card

un ordine coerente delle sezioni

vincoli stringenti su lunghezza e formato dei contenuti

Tuttavia, i dettagli visivi (HTML/CSS) sono ancora interpretati dal modello.

Questo comporta che:

modelli diversi possano generare implementazioni leggermente differenti

le card siano coerenti nella struttura ma non perfettamente identiche nell’aspetto

Perché è una scelta accettabile (e intenzionale)

Nel contesto e nei tempi di un hackathon:

arrivare a un layout completamente rigido e pixel-perfect avrebbe richiesto un livello di iterazione e test molto elevato

il progetto ha invece sfruttato questa variabilità come opportunità di osservazione

Questo ha permesso di:

testare la robustezza del prompt

confrontare il comportamento di modelli diversi

capire come l’interpretazione influisce sull’output

Direzione futura

Un’evoluzione naturale di Playfolio potrebbe prevedere:

l’inclusione di un layout HTML/CSS completamente fisso direttamente nel prompt

oppure l’uso di un template condiviso per garantire uniformità visiva totale

Questo renderebbe le Playfolio Card perfettamente identiche tra modelli e ideali per una galleria su larga scala.

Contenuto della repository

Playfolio - Master Prompt
L’artefatto centrale del progetto.
Contiene tutte le istruzioni necessarie per utilizzare Playfolio con un LLM.

README.md
Documentazione del progetto e razionale progettuale.

Stato del progetto

Questo progetto è un prototipo concettuale e funzionale, sviluppato nel contesto di un hackathon.

È pensato come:

proof of concept

esplorazione di design

base per sviluppi futuri

Non come prodotto commerciale finito.

Licenza

Il progetto è condiviso per sperimentazione, apprendimento e adattamento.
Sentiti libero di forkare, remixare e iterare.

# Playfolio [ENG]
A playable alternative to the traditional portfolio

Overview

Playfolio is an experimental portfolio generation tool designed for a world where artificial intelligence is already ubiquitous.

Instead of focusing on roles, titles, or exhaustive lists of skills, Playfolio aims to surface the human dimension of work:
how a person thinks, decides, collaborates, reacts to complexity, and creates value.

The output is not a CV.
It is a Playfolio Card — a character-like, mobile-first representation of a professional identity, inspired by the language of games and playcards, but grounded in real work contexts.

Core idea

You’ve achieved success in your field when you don’t know whether what you’re doing is work or play.
— Warren Beatty

Playfolio starts from this assumption and reframes professional storytelling accordingly.

In a context where AI can already generate, optimize, and execute, the differentiating factor becomes:

judgment

intention

values

taste

patterns of behavior

Playfolio is designed to make these elements visible, comparable, and shareable.

How it works

Playfolio is implemented as a Master Prompt that can be used autonomously with any Large Language Model (LLM), including free-tier versions of:

ChatGPT

Claude

Gemini

other compatible models

The process

The user pastes the Master Prompt into their preferred LLM.

The AI conducts a guided, empathetic conversation in Italian, asking a series of structured questions.

The AI synthesizes the collected information.

The final output is:

a short set of usage instructions

a Playfolio Card in HTML, ready to be copied into Notion, a webpage, or exported as PDF/image via browser tools.

No APIs, no automations, no paid tools are required.

Why a Master Prompt (and not a platform)

This project intentionally avoids building a proprietary tool or gated platform.

Using a Master Prompt as the core artifact ensures:

accessibility (works with free plans)

openness (no vendor lock-in)

adaptability (model-agnostic)

ease of distribution and reuse

In the context of the hackathon, this choice allowed the project to focus on concept, interaction design, and output quality, rather than infrastructure.

Output: the Playfolio Card

Each Playfolio Card includes:

Name and professional archetype

Primary playground (domain)

Human keywords

Superpowers (short, named abilities)

Vulnerability (label only)

Core values (keywords)

Signature move

Project impact

Observed behavioral patterns

Synergy scores with other professional profiles

The card is designed to be:

mobile-first

visually scannable

comparable across profiles

suitable for collection in a shared gallery

Archetypes

Playfolio uses a fixed set of professional archetypes (e.g. Sensemaker, Builder, Strategist, Challenger, etc.) to classify profiles.

These archetypes are:

internally defined in the Master Prompt

inferred by the AI based on behavior, not self-declared roles

meant to balance playfulness with analytical rigor

The classification is intentionally lightweight and interpretative, not deterministic.

Accessibility and free-tier compatibility

A key design constraint of Playfolio is free access.

The Master Prompt is designed to function within the limits of:

free LLM accounts

limited message quotas

partial or unavailable access to external resources (links, PDFs)

If external resources cannot be accessed, the AI is instructed to infer patterns only from user-provided answers, without breaking the experience.

This makes Playfolio usable by judges, participants, and future users without requiring subscriptions or paid credits.

Limitations and future improvements
Fixed layout consistency

At the moment, the Master Prompt defines:

a fixed semantic structure for the Playfolio Card

a consistent order of sections

strict constraints on content length and format

However, the visual layout and CSS details are still interpreted by the model.

This means that:

different LLMs may generate slightly different HTML/CSS implementations

cards are structurally consistent but not perfectly identical in appearance

Why this is acceptable (and intentional)

Within the scope and time constraints of the hackathon:

defining a fully rigid, pixel-perfect layout for all models would have required extensive iteration and testing

the project instead uses this variability as an opportunity to observe how different models interpret the same Master Prompt

This has proven valuable in:

testing prompt robustness

comparing model behaviors

understanding how interpretation affects output

Future direction

A natural next step for Playfolio would be:

introducing an explicitly defined, fixed layout (HTML + CSS) embedded directly in the prompt

or providing a shared base template to ensure visual uniformity across all generated cards

This would make Playfolio Cards fully identical across models and ideal for large-scale galleries.

Repository contents

Playfolio - Master Prompt
The core artifact of the project.
Contains all instructions needed to run Playfolio with an LLM.

README.md
Project documentation and design rationale.

Status

This project is a conceptual and functional prototype, developed in the context of a hackathon.

It is intended as:

a proof of concept

a design exploration

a starting point for further development

Not as a finished commercial product.

License

This project is shared for experimentation, learning, and adaptation.
Feel free to fork, remix, and iterate.
