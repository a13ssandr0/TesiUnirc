# Modello tesi di laurea dipartimenti DICEAM e DIIES

Per cominciare a lavorare seguire 
[la guida](https://github.com/a13ssandr0/TesiUnirc/wiki).

Se hai già seguito i passaggi per la configurazione dell'ambiente, 
per lavorare ad un nuovo progetto, 
[crea una nuova repository partendo da questo template](https://github.com/new?template_name=TesiUnirc&template_owner=a13ssandr0).


# Struttura
Il progetto è diviso in cartelle con all'interno i componenti del documento.

- `00_styles`contiene le definizioni degli stili del documento, nel file 
    `preamble.tex` è possibile impostare la lingua del documento
- `01_images` cartella con le immagini, è consigliabile dividerle per capitolo
- `02_frontmatter` contiene le configurazioni delle prime pagine del documento
    - `00_frontespizio.tex` va modificato con
        - nome del dipartimento
        - nome del corso di laurea
        - titolo della tesi
        - nome del candidato
        - nome del relatore (o dei relatori)
        - nome del correlatore (o dei correlatori)
        - _eventuale_ dedica
        - abstract
    - `01_acronimi` contiene l'elenco degli acronimi, vanno ordinati manualmente.
        per garantire una corretta formattazione della tabella indicare l'acronimo
        più lungo dove richiesto
- `03_chapters` cartella con i capitoli, sono già previsti quattro capitoli più
    introduzione e conclusioni
- `04_backmatter` contiene _eventuali_ ringraziamenti, la bibliografia ed _eventuali_ appendici

`main.tex` è il file principale in cui vengono inclusi tutti i file appena menzionati,
è il file da modificare per aggiungere o rimuovere parti del documento.
È possibile commentare eventuali sezioni non necessarie come 
indicato nei commmenti del file.

`main.pdf` documento risultante a seguito della compilazione

# Risoluzione dei problemi
A seguito di alcune modifiche strutturali, è molto probabile che la compilazione
non vada a buon fine.

Se ritentare la compilazione due volte non dà risultati,
molte volte è sufficiente cancellare la cartella `.out` e ritentare la compilazione.

