# Esame in itinere back-end

### Parte 1 MODULO NPM

##### Implementare un modulo NPM e pubblicarlo su npm.js che gestisca una ToDo List, ovvero una lista delle cose da fare, ogni elemento della ToDo List sarà cosi composto:

```javascript
	{ 
    	name: 'A simple To Do',
        description: 'To do my exam',
        completed: false,
        assignedTo: 'Caio'
    }
    
```

##### Le operazioni da poter compiere sono:

1. Creare e resettare una lista di ToDo
2. Aggiungere un ToDo
3. Eliminare un ToDo
4. Cambiare lo stato di completed da false a true e viceversa
5. Inoltre creare una lista statica di users, a cui è possibile assegnare un todo, tale lista deve essere leggibile da chi importa il pacchetto tramite una funzione
6. Non sarà possibile inoltre creare un toDo per utenti non presenti nella lista degli user.
7. Leggere la lista dei toDo in base ad uno specifico utente
8. Leggere la lista dei Todo in base al fatto che siano completati o meno, indipendentemente dall'utente


##### Eseguire i test per il pacchetto
##### Pubblicare il pacchetto su NPM e GIT

### Parte 2 SERVER API

##### Implementare un Server Api Node utilizzando il framework express che esponga le seguenti API

1. POST Di Creazione ToDo 
2. POST Di Cancellazione in base all'ID ToDo 
3. PUT di modifica di ToDo in base all'id 
4. GET lettura di tutti i ToDo filtrata per utente 
5. GET lettura di tutti gli utenti disponibili
6. GET lettura di tutti i ToDo filtrata per stato di completamento 
7. DELELTE Cancellazione di un ToDo

##### Eseguire i test per il server
##### Pubblicare su GIT