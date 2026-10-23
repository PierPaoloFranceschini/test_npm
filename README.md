## Comandi Utili

npm init -y : inizializza un progetto con node/npm

npm i nomelibreria : installa una libreria

npm uninstall nomelibreria : disinstalla libreria

## File del Progetto

Dopo aver inizializzato il progetto,
verranno aggiunti una cartella chiamata "node_modules" che conterrà le librerie del progetto, e un file chiamato "package.json", che sarà il file "ricetta" della nostra applicazione, dove saranno elencate le librerie (o dipendenze) del progetto

## Comandi da eseguire per fixare comportamenti anomali

npm install : reinstalla tutte le librerie

## Prima di pushare un progetto su Github

creare un file chiamato .gitignore dove indicare di non caricare la cartella delle librerie locali installate sul pc node_modules, altrimenti la repo avrà dimensioni eccessive per github ( e anche per convenzione )

questo sia per node_modules ma soprattutto per il file che conterrà le vostre password del file .env ->>> IMPORTANTISSIMO

## Eliminare npm da un progetto

Per riportare il progetto allo stato iniziale, si può cancellare la cartella node_modules e il file package-lock.json
