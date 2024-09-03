# I miei primi passi in Git

**Informazione: i segni <\> non devono essere messi, servono solo per informazione.**

## Configurazione di base

inserire il tuo nome e cognome all'interno del comando seguente  
`$ git config --global user.name "nome cognome"`


inserire il tuo indirizzo email all'interno del comando seguente  
`$ git config --global user.email "indirizzo.email@gmail.com"`

## Comandi di base

Per inizializzare la Ripository usare il comando:  
`% git init`
 
Per controllare lo stato dei commits usare il comando:  
`$ git status`

Per fare lo "stage changes" usare il comando:  `% git add <\file>`  
Al posto di "<\file>" inserire uno dei seguenti comandi:  
- "." che aggiunge tutti i file
- "Nome del file" che aggiunge il file con il nome inserito

Per committare digitare:  `$ git commit -m '<Motivo del commit>`

Per collegare il tuo Git a Github usare:  
`$ git remote add origin <\link del Github>`

### Branch

#### Comandi base Branch

Per creare un nuovo Branch:  
`$ git branch <\nome Branch>`

per scambiare da Branch a Branch:  
`$ git checkout <\nome Branch>`

per eliminare un Branch (safe mode):  
`$ git branch -d <\nome Branch>`

per eliminare un Branch (force mode):  
`$ git branch -D <\nome Branch>`

#### Comandi avanzati Branch

##### Unire i Branch

1. Andare nel Branch in qui si vuole unire il resto.  
2. Eseguire il comando: `$ git merge <\nome del Branch che vuoi unire>`
3. (facoltativo) Eliminare la cartella che hai appena unito.

## Altro

Crediti: Erik Carina (RSI)

[Book git](https://git-scm.com/book/en/v2) (english)  
[RSI](https://www.rsi.ch/)
[Basic Syntax](https://www.markdownguide.org/basic-syntax/)