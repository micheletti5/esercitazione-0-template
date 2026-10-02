# Osservazioni — Esercitazione 0

Gruppo: C-11

Componenti (nome, cognome e username GitHub di entrambi):

	   	  Nicole Micheletti micheletti5;
		  MariaGloria Morabito mariagloria-hub.

URL del repository condiviso:

    	https://github.com/micheletti5/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2:

       abbiamo lavorato da due computer separati.

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:

	   gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato:

	   ./hello
	   
	   risultato: stampa sul terminale di "Hello, computational physics!"

Che cosa ho capito su sorgente ed eseguibile:

hello.c è il file sorgente mentre hello è l'eseguibile. Se modifico il messaggio da sorgente e avvio l'eseguibile senza ricompilare, dal terminale osserverò ancora il messaggio scritto nel sorgente prima della modifica. 

Output richiesto e comportamento del programma prima della modifica:

L'output richiesto inizialmente è "Hello, computational physics!" da far stampare sul terminale.
Prima della modifica, tramite printf, richiedo al programma di stampare la frase richiesta e avvio l'eseguibile affinché avvengna la stampa
 

Esito dopo la modifica e spiegazione della correzione:

Dopo la modifica, avviando nuovamente l'eseguibile senza ricompilare il programma stampa ancora la vecchia richiesta. Nel momento in cui ricompilo e avvio hello viene stampato il nuovo messaggio(nel mio caso cambiato in "modifico messaggio!".

Viene richiesto inoltre di reindirizzare l'output avviando l'eseguibile e aggiungendo > output.txt.
Ciò che si può osservare esguendo ciò è che sul terminale non viene stampato più nulla ma viene creato un file di testo con scritta la stampa richiesta.

## Step 1 — Git

commit verificato da app confrontando con la stampa dal comando git log --online -5.

Quali file ho incluso nel commit e perché:

Come ho verificato che la versione provata sia presente su GitHub:

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:

Che cosa posso concludere:

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
