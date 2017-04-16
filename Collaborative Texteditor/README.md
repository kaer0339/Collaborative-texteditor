# Project MUTE

Collaborative texteditor based on a Conflict free replicated datatype(CRDT) with a NodeJS client/server

OSPP (1DT096) 2016 - Grupp 04

Projektarbete på kursen Operativsystem och processorienterad
programmering (1DT096) våren 2016, Uppsala universitet.

Detta är ett projekt för att skapa en kollaborativ text-editor (Multi-User Text Editor).

> Denna fil är skrivet i formatet Markdown, läs mer här:
>
> - https://help.github.com/articles/markdown-basics/

> Det går att redigera, förhandsvisa och spara (commit) sidan direkt i
> en webläsare via [projektsidan på github.com](./README.md).

## Nödvändigheter
###Nodejs
**Nodejs** och **npm** (nodejs package manager) behövs för att starta programmet.

För att installera **nodejs**  och **npm** på t.ex ubuntu använd dessa kommandon:

*sudo apt-get update*

*sudo apt-get install nodejs*

*sudo apt-get install npm*

När du har installerat **nodejs** och **npm** så kör du nedanstående kommando från samma mapp som detta dokument ligger i:

*npm install*

Nu ska paketen som används i programmet vara installerade.

## Kompilera

> Kortfattade instruktioner för hur projektet kompileras.

## Testa

För att testa programmet krävs att du har paketen **mocha** och **chai**.
Såhär kan du hämta dessa paket, förutsatt att du har installerat **nodejs** och **npm**:

*npm install -g mocha*

*npm install chai*

Sedan kan du köra testerna genom att skriva:

*npm test*

## Starta systemet

*npm start*

Klienten skall nu vara tillgänglig på följande URL:

[http://localhost:8888/](http://localhost:8888/)

## Struktur

Projektet består av följande kataloger.

### doc

Dokumentation, projektrapporter och andra viktiga dokument.

### bin


### meta

- Presentation av gruppens medlemmar.
- Gruppkontrakt.
- Projektdagböcker.
- Reflektioner på gruppens arbete.

### src

All källkod.

## Fler rubriker

> Lägg till mer information allt eftersom.