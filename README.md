# I miei primi passi in Git (italiano)

**Informazione: i segni <> e \ non devono essere messi, servono solo per informazione.**

## Configurazione di base

Inserire il tuo nome e cognome all'interno del comando seguente  
`$ git config --global user.name "nome cognome"`


Inserire il tuo indirizzo email all'interno del comando seguente  
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

Per "spingere" o "aggiornare" usare il comando:  
`$ git push origin main`

Per clonare la repository online usare: 
`$ git clone https://github.com/Ek6pr0/Hello_world.git` 

### Branch

#### Comandi base Branch

Per creare un nuovo Branch:  
`$ git branch <\nome Branch>`

Per scambiare da Branch a Branch:  
`$ git checkout <\nome Branch>`

Per rinominare un Branch:  
`$ git branch -m <\Nome attuale> <\nuovo nome>`

Per eliminare un Branch (safe mode):  
`$ git branch -d <\nome Branch>`

Per eliminare un Branch (force mode):  
`$ git branch -D <\nome Branch>`

#### Comandi avanzati Branch

##### Unire i Branch

1. Andare nel Branch in qui si vuole unire il resto.  
2. Eseguire il comando: `$ git merge <\nome del Branch che vuoi unire>`
3. (Facoltativo) Eliminare la cartella che hai appena unito.


# My first steps in GIT (english edition)

**Information: The signs <> and \ do not have to be insert too,they are only for information.**

## Base Configuration

Insert your first name and last name inside the following command:  
`$ git config --global user.name "First name and last name"`

Insert your E-mail adress inside the following command:  
`$ git config --global user.email "E-mail.adress@gmail.com"`

## Base commands

To inizialize a new Repository use the following command:  
`$ git init`

To check the commits status use the command:  
`$ git status`

To stage the files use the command:  
`$ git add <\file>`  
instead of <\file> insertuno of the following commands:  
- "." that add all the files
- "File name" that add the file with that name

To commit digit:  
`$ git commit -m <reason of the commit>`

To link your Repository to Github use:  
`$ git remote add origin <\link of Github>`

To clone a online Repository use:  
`$ git clone https://github.com/Ek6pr0/Hello_world.git`

### Branch

#### Base commands for Branch

To create a new Branch:  
`$ git branch <\Branch name>`

To switch from Branch to Branch:  
`$ git checkout <\Branch name>`

To delete one Branch (safe mode):  
`$ git branch -d <\branch name>`

To delete one Branch (Force mode):  
`$ git branch -D <\branch name>`

#### Advanced commands for Branch

##### Merge the Branches

1. Go inside the Branch you want to merge the others into.
2. Execute the command: `$ git merge<\Branch name that will merge>`
3. (Optional) Delete the Branch you just merged.


## Altro / Other

Credits: Erik Carina (RSI)

[Book git](https://git-scm.com/book/en/v2) (english)  
[RSI site](https://www.rsi.ch/)  
[Basic Syntax](https://www.markdownguide.org/basic-syntax/)
