# Portfolio

## [Project 1: Estrapolatore dati IMDb](https://github.com/SimonCamba/SimonCamba.github.io-IMDbAnalyser)
* Programma che legge, tramite Funzione, un file CSV contenente un database di IMDb con le seguenti informazioni relative ai film: Posizione in classifica; Genere; Desscrizione; Regista; Attori; Anno di uscita nelle sale; Minutaggio; Valutazione; Incassi.
* Una volta letto il file e memorizzato localmente il contenuto mediante una variabile; il programma identifica il film con la valutazione più alta, servendosi del ciclo For e della sintassi If
* Il programma identifica inoltre l'attore che ha partecipato al maggior numero di film, servendosi di un Dizionario avente come chiavi i nomi degli attori e come valori l'occorrenza di ciascun attore nei vari cast. Tali valori sono ottenuti mediante una scansione progressiva del file, tramite ciclo For e sintassi If.
* In ultimo, servendosi di una Funzione, del ciclo For e della sintassi If, il programma crea un nuovo file CSV he associa ad ogni regista, i film che ha prodotto, e il rating medio tra i fil che a prodotto.
  

## [Project 2: Gestore di Voli](https://github.com/SimonCamba/SimonCamba.github.io-GestoreVoli)
* Programma che legge, tramite Funzione, un file CSV contenente tutti i voli transitanti all'aeroporto di Cagliari in un dato periodo e ne acquisisce i contenuti in forma di lista di Liste.
* Assegnata a una nuova Variabile il contenuto del file, a titolo dimostrativo ed esimplificativo, estrapola i dati dei voli operativi il GIOVEDI' e li salva in un nuovo file dal nome "voli_operativi_GIOVEDI.csv"
* Il programma si presta ad essere adattato per estrapolare i dati secondo vari altri criteri di ricerca, per citarne alcuni:
     * Compagnia Aerea
     * Aeroporto di Partenza
     * Data
     * Orario di Partenza
     * Durata del volo

## [Project 3: Funzione Trova Parola](https://github.com/SimonCamba/SimonCamba.github.io-TrovaParola)
* Definita una funzione trova_parola(file, parola) che preso in ingresso un file e una parola
* restituisca un dizionario che ha come chiavi il numeri della riga e come valore il numero di occorrenza della parola stessa nella riga, se presente.
* A titolo di esempio dimostrativo, ho preso un file .txt contenente un estratto da "I Promessi Sposi" e ho impostato , come termine da ricercare, la parola "ma"

## [Project 4: Calcolatore di Somma Algebrica](https://github.com/SimonCamba/SimonCamba.github.io-CalcolatoreSommaAlgebrica) 
* Permette di eseguire la somma algebrica di numeri inseriti da input in maniera continua mediante un ciclo While.
* La variabile "numero" definita internamente al ciclo While viene addizionata alla variabile "somma" definita in principio ad ogni conclusione del ciclo.
* L'inserimento del carattere "x" o "X" sotto condizione If pone fine al ciclo While e, contestualmente, all'inserimento dei valori da parte dell'utente. Viene quindi stampata la variabile "somma"

