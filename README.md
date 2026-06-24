# BPM

Strumento web 100% client-side: dal **BPM** ai **tempi di delay e riverbero** in millisecondi.
Gli stessi valori servono per delay, **pre-delay** e **coda del riverbero**. Note dritte, puntate e
terzine (1/1 → 1/64), con equivalente in Hz. Niente da installare, nessun dato esce dal dispositivo.

**Live:** https://simonecastellan.com/delay/

## Funzioni
- Inserimento BPM (campo, +/−, frecce tastiera).
- **Batti il tempo** (pulsante o barra spaziatrice) per ricavare il BPM a orecchio.
- Tabella note 1/1 → 1/32 × dritto / puntato / terzina.
- Toggle unità **ms / Hz**.
- Tocca un valore per copiarlo negli appunti.

## Formule
- `ms = (60000 / BPM) × (4 / denominatore)`
- puntato `× 1.5`, terzina `× 2/3`
- `Hz = 1000 / ms`

## Stile
Minimale monocromatico, coerente con [simonecastellan.com](https://simonecastellan.com).

Designed and built by Simone Castellan.
