# :leaves: Foot Print Calculator :leaves:

Il nostro progetto consente di tenere traccia del footprint di un prodotto a partire dalla materia prima del quale e composto e considerando la lavorazione necessaria alla sua produzione.

 ## Indice
 1. Come installare il programma;
 2. A cosa serve il programma;

## Come installare il programma

### Prerequisiti

- node.js
- Docker
- python


### NodeJS
Per prima cosa bisogna eseguire il download di NodeJS, cliccando sul seguente link:[Download NodeJS](https://nodejs.org/it/) e seguire poi le istruzioni dell'installer.


### Docker

Il nostro **foot print calculator** è davvero facile da installare ed utilizzare. Sfrutta docker per la gestione in locale dei nodi della blockchain.

Come prima cosa bisogna installare docker per fare ciò basta seguire le indicazioni riportate nel seguente link: [Come installare docker](https://docs.docker.com/desktop/windows/install/)  



### Python
Il programma per funzionare necessita di python, per istallarlo, seguire le istruzioni riportate nel seguente link: [download and install python](https://www.python.org/downloads/)

### Creazione ambiente virtuale con dipendenze
```sh
python venv <nome_ambiente>
cd <nome_ambiente>/Scripts/activate
pip install -r requirement.txt
```

### Far partire la BlockChain
Nella cartella scaricata da GitHub aprire il prompt ed eseguire i seguenti comandi:
```sh
cd 3-nodes-footprintBlockchain
docker compose up
 ```

### Eseguire il programma
```sh
python path/to/file/init_prod.py 
python main.py
```

<!--### Quorum-wizard

Per installare quorum-wizard basterà aprire il terminale di windows ed eseguire i seguenti comandi:

```sh
npx quorum-wizard 
```
E seguire le indicazioni, e quando viene richiesto di scegliere tra docker-compose e Kubernetes, scegliere **docker-compose**.

```sh
cd networks/<nome_network>/
start.cmd
```-->

## Autori
:computer: Margherita Galeazzi -> https://github.com/MargheritaGaleazzi

:computer: Chiara Amalia Caporusso -> https://github.com/ChiaraAmalia

:computer: Simone Scalella -> 

:computer: Zhang Yihang -> 

