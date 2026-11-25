# Validatore di Tag Hreflang e SEO Internazionale

[![Validatore Hreflang](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/it/validatore-tag-hreflang/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Controllo di reciprocita dei link alternativi, mappatura geografica ISO, e configurazione di fallback x-default.

Sviluppato e mantenuto dalla divisione di ingegneria di ricerca internazionale e standard web di **TAVARDT**.

***

## Funzionalita di Audit Hreflang e SEO Internazionale

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

## Diagnostica Completa sul Web

Per verifiche approfondite ed analisi visiva delle annotazioni internazionali:

* [Validatore Hreflang](https://tools.tavardt.com/it/validatore-tag-hreflang/)
* [Portale Aziendale](https://ag.tavardt.com/it/)

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
