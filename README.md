# Validatore di Tag Hreflang e Architettura SEO Internazionale

[![Validatore Hreflang](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/it/validatore-tag-hreflang/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Verifica tecnica di reciprocita dei collegamenti alternativi, codici di lingua e regione e tag x-default.

Sviluppato e mantenuto dalla divisione di ingegneria semantica e SEO internazionale di **TAVARDT**.

***

## Funzionalita di Verifica Hreflang e SEO Internazionale

* **Verifica di Reciprocita dei Link**: Controlla che ogni pagina alternativa possieda un collegamento di ritorno verso la pagina analizzata.
* **Convalida Codici ISO 639-1 e ISO 3166-1**: Ispezione accurata dei codici di lingua e nazione (es: `it-IT`, `en-US`, `es-ES`).
* **Direttiva x-default**: Verifica della presenza della pagina di destinazione predefinita per utenti non targetizzati geograficamente.
* **Armonia con il Tag Canonical**: Rilevamento delle divergenze tra URL canonico e annotazione hreflang autoriferenziale.
* **Punteggio di Salute Multilingue**: Metrica da 0 a 100 con passaggi di ottimizzazione tecnica.

***

## Installazione ed Esecuzione

Richiede Python 3.8 o superiore, basato sulla libreria standard di Python.

```bash
git clone https://github.com/TAVARDT-Italia/hreflang-validator-it.git
cd hreflang-validator-it
python hreflang_validator.py https://azienda.it
```

Per generare il rapporto in formato strutturato JSON:

```bash
python hreflang_validator.py https://azienda.it -json
```

***

## Diagnostica Completa sul Web

Per verifiche estese di architetture web multilingue:

* **Validatore di Tag Hreflang Ufficiale**
* **[Portale Aziendale TAVARDT](https://ag.tavardt.com/it/)**

***

## Consulenza in SEO Internazionale e Architettura Web

Per progetti di internazionalizzazione conformi a Standard W3C e Linee Guida AgID, contattare il team di **TAVARDT**.

***

## Link Utili

* **Portale Aziendale:** https://ag.tavardt.com/it/
* **Suite di Diagnostica:** https://tools.tavardt.com/it/
* **Contatto Tecnico:** https://ag.tavardt.com/it/contatto/

***

### Licenza
Distribuito sotto Licenza MIT. Consultare il file [LICENSE](LICENSE) per maggiori informazioni.

***

© 2026 TAVARDT. Tutti i diritti riservati.
