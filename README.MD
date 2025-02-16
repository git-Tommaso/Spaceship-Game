# Gioco Asteroidi

Questo è un semplice gioco di asteroidi sviluppato in Python utilizzando la libreria `pgzrun`.

## Requisiti

- Python 3.x
- Libreria `pgzrun`

## Installazione

1. Clona questo repository:
    ```sh
    git clone https://github.com/tuo-username/gioco-asteroidi.git
    ```
2. Installa la libreria `pgzrun`:
    ```sh
    pip install pgzero
    ```

## Esecuzione del Gioco

Per avviare il gioco, esegui il seguente comando nella directory del progetto:
```sh
python main.py
```

Controlli
Freccia su: Accelera la nave
Freccia sinistra: Ruota la nave a sinistra
Freccia destra: Ruota la nave a destra
Tasto S: Spara un proiettile
Descrizione del Gioco
Il gioco consiste nel controllare una nave spaziale e distruggere gli asteroidi che appaiono sullo schermo. La nave può sparare proiettili per distruggere gli asteroidi. Ogni asteroide distrutto si divide in asteroidi più piccoli fino a raggiungere la dimensione minima.

Struttura del Codice
main.py: Contiene il codice principale del gioco, inclusa la logica di aggiornamento e disegno degli oggetti di gioco.
Funzioni Principali
reset(): Reimposta lo stato del gioco.
update(dt): Aggiorna lo stato del gioco in base al tempo trascorso.
draw(): Disegna gli oggetti di gioco sullo schermo.
Autore
Il tuo nome
Licenza
Questo progetto è distribuito sotto la licenza MIT. Vedi il file LICENSE per maggiori dettagli.
