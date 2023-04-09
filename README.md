# Esercitazioni-JavaScript-3
### Alcuni semplici esercizi per apprendere JavaScript

## Esercizio 1:
Realizzare una pagina web che presenta all’utente la domanda a risposta multipla di un quiz, e controlla la correttezza della risposta, inviando un messaggio di “errore” o di “conferma”.

### Suggerimenti:
- Utilizzare un modulo (form) e tramite l’oggetto INPUT TYPE=”RADIO” inserire le “domande” al quiz...
- Associare ad ogni pulsante “radioButton” l’evento onClick che attiverà la function RispEsatta o RispErrata (a seconda della scelta fatta): tale funzione invierà il messaggio (ESATTO / ERRATO) all’utente (ad esempio tramite alert(...))

### Esempio:
<img src="readmeSrc\1.png" alt="1" width="50%" height="50%" style="margin: 1;">

## Esercizio 2:
Una stringa di caratteri contiene un insieme di cifre di cui si desidera calcolare la somma ridotta ad un numero composto “da una sola cifra <= 9”.
<br> Ad esempio se la stringa contenesse:
<br> 87509136833579541
<br> Il risultato sarebbe:
<br> 8+7+5+0+9+1+3+6+8+3+3+5+7+9+5+4+1 = 84
<br> Il risultato è un numero a “due cifre”: queste poi vanno “sommate” 8+4 = 12
<br> Le “due cifre” vanno ancora sommate e si ottiene 1+2 = 3: il numero a “una cifra”

### Lo script deve:
- Caricare il numero sotto forma di stringa, quindi procedere con un ciclo iterativo al calcolo ....

#### Nota:
- La funzione "eval(stringa)", converte la stringa passata come argomento, in un numero.
- La funzione (metodo) "numero.toString()", converte il valore numerico contenuto nella variabile “numero” in stringa.

## Esercizio 3:
### "Array"
### 1.
Si scriva un programma che legge in input K numeri interi (K valore da richiedere in input con Javascript) e li memorizza in un array “numeri” di lunghezza K.
<br> Successivamente legge in input un intero X (X valore da richiedere in input con Javascript) e stampa il numero di occorrenze di X in “numeri” (quante volte il valore X è presente nell’array “numeri”).

### 2.
Si scriva un programma JavaScript che legge in input K numeri interi (K valore da richiedere in input con Javascript) e li memorizza in una array “valori” di lunghezza K.
<br> Dichiara un secondo array “valori_copia” di lunghezza K e copia tutti gli elementi di “valori” in “valori_copia”. 
<br> Quindi visualizza in output entrambi gli array.

### 3.
Si scriva un programma JavaScript che legge in input K numeri (K valore da richiedere in input con Javascript) e li memorizza in una array “dati” di lunghezza k.
<br> Quindi legge un valore X intero e controlla se la somma di tutti gli elementi di indice pari sia minore o uguale ad X, e visualizza in output un messaggio: “Condizione ESERCIZIO 2 verificata” oppure “Condizione ESERCIZIO 2 non verificata”.

## Esercizio 4:
### "Piccolo calendario perpetuo"

Realizzare una pagina HTML che, mediante script in linguaggio JavaScript, consenta la realizzazione di un calendario perpetuo con un range di almeno 12 anni (es.: dal 2010 al 2022).
<br> All’utente deve essere consentito di selezionare l’anno ed il mese da visualizzare (possibilmente in una finestra distinta, da aprire al momento), magari selezionandoli da “liste” proposte a video (utilizzando gli elenchi a “tendina” dell’elemento Select dei Form HTML).

### Esempio: 
<img src="readmeSrc\4.png" alt="4" width="50%" height="50%" style="margin: 1;">
