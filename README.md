# TESI

Questa repository è un progetto LaTeX utilizzato per scrivere una tesi in project management.

## Ambito della tesi

- Metodi tradizionali: PMBOK 8 e PRINCE2
- Agile
- Confronto tra approcci tradizionali e Agile, con analisi delle affinità
- Stato attuale delle aziende e dei loro approcci

## Struttura iniziale

- `/tesi.tex`: file unico di lavoro e compilazione della tesi
- `/chapters/frontespizio.tex`: documento separato del frontespizio, compilato in PDF e poi incluso in `tesi.tex`
- `/chapters/`: contenuto testuale esternalizzato in file numerati da `00-frontespizio-dedica.tex` a `10-ringraziamenti.tex`
- `/sources/`: contenitore delle fonti (link, PDF e altri materiali)

## Compilazione

1. Compila `/chapters/frontespizio.tex` per generare `frontespizio.pdf`.
2. Compila `/tesi.tex` per ottenere la tesi completa con il frontespizio concatenato all'inizio.
