
![JS ES6](assets/js-book.png)

Benvenuti a ES6 In Depth! Questa è una serie di articoli settimanali, che rappresentano la traduzione italiana degli stessi postati da Mozilla su [hacks.mozilla.org](https://hacks.mozilla.org) che rappresenta una delle migliori risorse per tutti coloro che sono ogni giorno impegnati nello sviluppo web e che vogliono approfondire le proprie conoscenze. In questa serie di articoli affronteremo ECMAScript 6 o ES6, oggi noto anche come ES2015, la nuova versione del linguaggio JavaScript a cui sono state aggiunte nuove features che lo rendono più flessibile ed espressivo soprattutto per coloro che provengono da altri linguaggi quali Java o C#.

Al momento della stesura di questo articolo ES6 è già uno standard identificato con il nome di ECMAScript 2015 che potete consultare al segunete indirizzo: [ecma-262](http://www.ecma-international.org/ecma-262/6.0/).

##Il nuovo standard

Questa estate è stato ratificato il nuovo standard per il core del linguaggio di programmazione JavaScript, una grande news se si pensa che l’ultimo aggiornamento risale al 2009 quando è stato introdotto ES5. ES6 è il più massivo aggiornamento di sempre, ma non rompe con il passato, questo vuol dire che tutte le applicazioni scritte in ES5 continueranno a funzionare e che in più potranno essere usate le nuove features messe a disposizione del nuovo standard. **ES6 agli occhi di un JavaScript engine appare come un’estensione di ES5**.

##Perchè ES6?

Le precedenti versioni di ECMAScript sono state numerate 1,2,3 e poi si è passati direttamente alla 5, come mai e cosa è successo alla 4?

In realtà si è lavorato molto sulla versione 4, ma le modifiche da apportare erano davvero tante e abbastanza sofisticate, come ad esempio l’introduzione di tipi statici e di interfacce e ciò ha spinto i membri della commissione a pubblicare un modesto aggiornamento di JavaScript oggi conosciuto come ES5. Nel frattempo si è lavorato molto duramente per modernizzare e introdurre nuove funzionalità al linguaggio processo frutto di negoziazione tra i membri della commissione e di suggerimenti proveniente direttamente dal mondo delle aziende che fanno uso di questo linguaggio nei loro prodotti.

##Le promesse sono state mantenute

ES5 nel 2009 ha introdotte le seguenti features [Object.create()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create), [Object.defineProperty()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty), [getters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get), [setters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set), [strict mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode) e i [JSON object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON). In un modo o nell’altro chiunque abbia usato JavaScript si è trovato ad usare queste features, che pur essendo delle innovazioni hanno un impatto decisivo sull’editing del codice sorgente. **ES6 è differente** anche perhè è il frutto di molti anni di lavoro e ricerca in effetti è il maggior update di sempre e include features che aiutano il programmatore ad evitare le verbosità nel proprio codice come le arrow functions e le string interpolation o ancora nuovi concetti come quelli di proxies e generators. In modo particolare ES6 cambierà anche il modo in cui viene scritto il codice rendendolo più leggibile.

Questa serie di articoli ha lo scopo di mettere in luce le nuove funzionalità di ES6 , partendo da quelle che molti programmatori sono stati ansiosi di vedere da tempo e che mancavano.

L’articolo originare potete trovarlo qui: https://hacks.mozilla.org/2015/04/es6-in-depth-an-introduction/
