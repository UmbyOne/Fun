# F1 Pong Grand Prix

Gioco "F1 Pong Grand Prix" — una versione stilizzata di Pong con monoposto F1, realizzata in un singolo file HTML (canvas + JS + CSS).

### Cosa ho aggiunto
- Canvas responsivo con supporto ad alta densità di pixel (DPR).
- Controlli touch: tocca/trascina sul lato sinistro o destro del canvas per muovere le rispettive monoposto su dispositivi touch.
- Pulsanti HUD: Pausa / Riavvia.
- Selettore difficoltà CPU (Facile / Normale / Difficile).
- Suoni semplici via WebAudio (effetti su rimbalzo, colpo, punto e vittoria).
- Salvato vittorie totali in `localStorage`.
- Corretto posizionamento del canvas per evitare che venga coperto dal tabellone e per prevenire ritagli su schermi piccoli.
- Sostituito l'uso di alert() con una finestra modale personalizzata per rimuovere la dicitura del browser.

### Problemi risolti
- Canvas tagliato su alcuni schermi: ora la pagina scorre se necessario e il canvas è centrato.
- Audio su iOS: introduzione di un 'unlock' audio su primo gesto utente (click/touch), richiesto da iOS per attivare WebAudio.
- Messaggi fine partita: rimpiazzati con modal interno (nessun "umbyone.github.io says").

### Controlli
- Giocatore sinistro (TEAM ROSSO): `W` (su) / `S` (giù) oppure tocca il lato sinistro sul touch.
- Giocatore destro (TEAM ORANGE): Freccia Su / Freccia Giù oppure tocca il lato destro (se non si usa la CPU).
- Seleziona "Umano vs Computer" dal menu per far giocare la CPU sul lato destro.
- Usa il menu in basso a destra per mettere in pausa o riavviare la partita e per cambiare difficoltà della CPU.

### Eseguire il gioco
1. Apri `index.html` in un browser moderno.
2. Se vuoi condividerlo pubblicamente, puoi abilitare GitHub Pages sulla branch `main` (Settings → Pages) e selezionare la root `/`.

### Prossimi miglioramenti possibili
- Aggiungere audio/FX su file esterni + mute toggle.
- Migliorare la rete / modalità multiplayer online.
- Migliorare accessibilità (contrasto, istruzioni visibili, focus keyboard).
- Inserire assets (sprite, icon) e ottimizzare le risorse.

Buon divertimento!