DESCRIZIONE
Ci ispiriamo al sito di Zalando per riprodurre il layout nello screenshot.
L'header è in posizione fixed.
Per ogni prodotto sono fornite 2 immagini: la prima sarà visualizzata all'apertura della pagina, la seconda sarà visualizzata al posto della prima, quando il cursore del mouse va in hover sulla card.
HOVER
Per funzionare avrete bisogno di:
Avere entrambe le immagini sovrapposte, nello stesso punto. Di base sarà visibile la prima.
All'hover della CARD sarà visibile la seconda IMMAGINE, giocando sul suo z-index o sull'opacity.
L'hover andrà gestito con un selettore che all'hover della card, alteri un secondo elemento (l'immagine). Suona pressapoco così: card:hover img { ... }CONSIGLI
Analizzate prima il layout solo con i commenti, poi passate ai blocchi colorati.
Solo se i blocchi colorati funzionano passiamo al particolare.
Usate tutte le regole che conosciamo. Non solo position e z-index, unite insieme quanto visto fino ad oggi.
Per l'header fixed avrete bisogno di tenere conto della sua height quando dovrete spaziare i contenuti. Date un'occhiata alla correzione discord .
BONUS
All'hover sul cuoricino, questo diventa rosso.