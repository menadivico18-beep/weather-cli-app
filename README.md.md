**# weather-cli-app**

**# 🌦️ Weather App – Open-Meteo API**



**## Project Overview**



Weather App è un'applicazione web che consente agli utenti di visualizzare le condizioni meteo attuali di qualsiasi città inserita nella barra di ricerca.



L’app utilizza:



\- \*\*Open-Meteo Geocoding API\*\* per ottenere le coordinate geografiche della città

\- \*\*Open-Meteo Weather Forecast API\*\* per recuperare i dati meteo aggiornati



Il progetto dimostra l'integrazione tra API esterne e JavaScript per la gestione di richieste asincrone e manipolazione del DOM.



---



**## Main Features**



\- Campo di ricerca per inserire il nome di una città

\- Visualizzazione di:

&nbsp; - Temperatura attuale

&nbsp; - Velocità del vento

&nbsp; - Descrizione delle condizioni meteo

\- Messaggio di errore se la città non viene trovata

\- Possibilità di effettuare ricerche multiple



---



\## Project Structure



---



\#**# How to Run the Project**



1\. Clona il repository:



```bash

git clone https://github.com/menadivico18-beep/weather-cli-app



2.Accedi alla cartella del progetto:



cd weather-app-open-meteo



3.Apri il file src/index.html direttamente nel browser.



Non sono richieste installazioni o dipendenze aggiuntive.



**## Screenshot**



\### Esempio di esecuzione



!\[Output Terminale](assets/screenshot 1.jpg)



\### Interfaccia applicazione



!\[Esempio App](assets/screenshot 2.jpg)



**What I Learned**



* Utilizzo di API REST in JavaScript
* 
* Gestione di richieste asincrone con fetch
* 
* Manipolazione del DOM
* 
* Gestione degli errori e feedback all’utente
* 
* Organizzazione di un progetto frontend



**Challenges**



La parte più complessa è stata gestire correttamente le risposte delle API e concatenare le richieste asincrone (prima geocoding, poi meteo) mantenendo il codice pulito e leggibile.



**Future Improvements**



* Integrazione di icone meteo dinamiche
* 
* Miglioramento del design UI
* 
* Salvataggio della cronologia delle ricerche



---



Se vuoi, posso adattarlo in una versione più tecnica (portfolio-ready) oppure più sintetica per GitHub.

* Aggiunta di previsioni per più giorni
