# F1 Pong Grand Prix

Gioco "F1 Pong Grand Prix" — una versione stilizzata di Pong con monoposto F1, realizzata in un singolo file HTML (canvas + JS + CSS).

### Cosa ho aggiunto
- Canvas responsivo con supporto ad alta densità di pixel (DPR).
- Controlli touch: tocca/trascina sul lato sinistro o destro del canvas per muovere le rispettive monoposto su dispositivi touch.
- Pulsanti HUD: Pausa / Riavvia.
- Selettore difficoltà CPU (Facile / Normale / Difficile).
- Suoni semplici via WebAudio (effetti su rimbalzo, colpo, punto e vittoria).
- Salvataggio punteggi totali (vittorie) in `localStorage`.

### Controlli
- Giocatore sinistro (TEAM ROSSO): `W` (su) / `S` (giù) oppure tocca il lato sinistro sul touch.
- Giocatore destro (TEAM ORANGE): Freccia Su / Freccia Giù oppure tocca il lato destro (se non si usa la CPU).
- Seleziona "Umano vs Computer" dal menu per far giocare la CPU sul lato destro.
- Usa il menu in basso a destra per mettere in pausa o riavviare la partita e per cambiare difficoltà della CPU.

### Eseguire il gioco
1. Apri `index.html` in un browser moderno.
2. Se vuoi condividerlo pubblicamente, puoi abilitare GitHub Pages sulla branch `main` (Settings → Pages) e selezionare la root `/`.

### Possibili miglioramenti futuri
- Aggiungere audio più ricco (file), musica di sottofondo e mute toggle.
- Migliorare la rete / modalità multiplayer online.
- Migliorare salvataggio dello stato per riprendere partite.
- Aggiungere effetti grafici avanzati (post-processing, shader) o sprite migliori.

Buon divertimento!