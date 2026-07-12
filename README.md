# Osservatorio Cold Email Italia — Benchmark per settore 2026

Dataset aperto sui reply rate delle campagne cold email B2B in Italia, pubblicato da [Clientium](https://clientium.it/osservatorio/).

## Cosa contiene

Benchmark di reply rate per 8 macro-settori, calcolati su **723 campagne reali** e **3.685.033 email inviate** (periodo 2024-2026), di cui 507 campagne / 2,63M email mappate con certezza a un macro-settore.

| File | Contenuto |
|---|---|
| `data/benchmark_settori_2026.json` | Benchmark completi con metadati e metodologia |
| `data/benchmark_settori_2026.csv` | Stessi dati in CSV (settore, campagne, clienti distinti, email inviate, risposte, reply rate %) |

## Numeri chiave del dataset completo

- Reply rate mediano per campagna: **1,71%**
- Top 10% delle campagne: oltre **3,79%**
- Campagne sotto l'1%: **24,1%**
- Bounce rate medio: 3,14%

## Metodologia

- Reply rate ponderato: somma risposte / somma email inviate per macro-settore.
- Settore attribuito con mappa esplicita dal nome cliente/campagna; le campagne non attribuibili con certezza sono state escluse, mai stimate.
- Soglie di inclusione: almeno 3 campagne e almeno 5.000 email inviate per settore.
- I dati sono aggregati a livello di macro-settore: nessun cliente è identificabile.

Analisi estese e aggiornamenti: [clientium.it/osservatorio](https://clientium.it/osservatorio/) — versione navigabile dei benchmark: [Reply rate per settore](https://clientium.it/osservatorio/reply-rate-per-settore/).

## Licenza

[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.it): puoi usare, citare e ripubblicare questi dati, anche a fini commerciali, citando la fonte:

> Clientium, Osservatorio Outbound Italia, https://clientium.it/osservatorio/

## Chi siamo

Clientium è un'agenzia italiana di acquisizione clienti B2B (cold email 1 a 1 e appointment setting pay per appointment) fondata da [Arnold Koci](https://arnoldkoci.com). Il dataset nasce dalle campagne gestite per i clienti dell'agenzia, in forma aggregata e anonima.

Contatti: info@clientium.it
