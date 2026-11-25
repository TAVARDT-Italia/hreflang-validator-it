# Validatore di Tag Hreflang e SEO Internazionale

[![Validatore Hreflang](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/it/validatore-tag-hreflang/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Controllo di reciprocita dei link alternativi, mappatura geografica ISO, e configurazione di fallback x-default.

Sviluppato e mantenuto dalla divisione di ingegneria di ricerca internazionale e standard web di **TAVARDT**.

***

## Vettori di Rischio e Impatto Operativo nel SEO Internazionale

Errori di sintassi nelle direttive hreflang causano spreco di crawl budget e declassamento nei motori di ricerca globali. Quando i link linguistici alternativi non sono reciproci, gli algoritmi di indicizzazione scartano le annotazioni regionali.

Questa vulnerabilita espone le piattaforme italiane a cannibalizzazione dei contenuti ed instradamento errato dei visitatori nazionali. Il collaudo continuo garantisce che ciascun mercato acceda alla pagina corretta con integrita architetturale.

***

## Funzionalita Centrali di Audit Tecnico

* **Verifica Tag Autoreferenziale**: Controllo automatico dell inclusione dell URL esaminato per garantire conformita ai requisiti di scansione.
* **Ispezione Fallback x-default**: Validazione della destinazione predefinita per utenti al di fuori delle regioni geografiche target.
* **Validazione Sintassi ISO 639-1 e ISO 3166-1**: Controllo rigoroso delle combinazioni di codice lingua e paese per evitare errori di configurazione.
* **Rilevamento Conflitti Canonical**: Identificazione immediata di discrepanze tra URL canonico e annotazioni linguistiche dichiarate.
* **Analisi a Doppia Sorgente**: Estrazione completa delle direttive da intestazioni HTTP Link ed elementi HTML `<head>`.
* **Indice di Qualita Internazionale**: Metrica tecnica da 0 a 100 con suddivisione in COMPLIANT, WARNING e CRITICAL.

***

## Installazione ed Esecuzione

Richiede Python 3.8 o superiore senza dipendenze esterne.

```bash
git clone https://github.com/TAVARDT-Italia/hreflang-validator-it.git
cd hreflang-validator-it
python hreflang_validator.py https://azienda.it
```

Per produrre l output in formato JSON strutturato in pipeline automatiche:

```bash
python hreflang_validator.py https://azienda.it -j
```

***

## Domande Frequenti (FAQ Tecnico)

### 1. Per quale motivo i motori di ricerca ignorano le direttive hreflang?
La mancanza di collegamenti reciproci di ritorno e l omissione del tag autoreferenziale inducono Googlebot a invalidare le annotazioni. Questo strumento intercetta le asimmetrie prima che compromettano il posizionamento organico internazionale.

### 2. Quale ruolo riveste la dichiarazione x-default in un architettura globale?
La dichiarazione x-default agisce come destinazione predefinita per gli utenti provenienti da regioni prive di versione linguistica mirata. L assenza di questo fallback comporta scelte di instradamento arbitrarie che riducono le conversioni.

### 3. In che modo il validatore rileva i conflitti tra link canonico e hreflang?
Il motore estrae sia l indicazione canonical sia i link alternate per accertarne l allineamento perfetto. Qualsiasi divergenza genera una segnalazione critica e decurta il punteggio complessivo di 20 punti.

### 4. Lo strumento analizza anche le intestazioni HTTP Link oltre al codice HTML?
Si, il sistema analizza sia le dichiarazioni presenti nell head HTML sia quelle trasmesse tramite intestazione HTTP Link. Cio rende possibile il controllo di risorse prive di interfaccia grafica come file PDF o risposte API.

### 5. Quali standard internazionali regolano i codici di lingua e regione?
Viene verificata la conformita allo standard ISO 639-1 per le lingue a due caratteri e allo standard ISO 3166-1 alpha-2 per i paesi. Codici non validi o invertiti comportano penalizzazioni immediate nell indice di qualita.

***

## Consulenza in SEO Internazionale e Architettura Web

Per l ottimizzazione di piattaforme multilingua e l allineamento agli standard W3C, consultare il team di **TAVARDT**.

***

## Collegamenti Utili

* **Portale Aziendale:** https://ag.tavardt.com/it/
* **Suite di Diagnostica:** https://tools.tavardt.com/it/
* **Contatto Tecnico:** https://ag.tavardt.com/it/contatto/

***

### Licenza
Distribuito con Licenza MIT. Consultare il file LICENSE per i dettagli completi.

***

© 2026 TAVARDT. Tutti i diritti riservati.
