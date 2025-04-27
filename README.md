DiveCenterManager

Opis sustava: DiveCenterManager je aplikacija za upravljanje lokacijama ronjenja i organizacijom izleta za ronilačke centre. Omogućuje korisnicima pregled dostupnih lokacija, rezervaciju izleta, te administratorima (ronilačkim centrima) upravljanje lokacijama, izletima i rezervacijama.

Glavne funkcionalnosti:

    Ronilački centar može dodavati nove lokacije s opisom i geografskom lokacijom.

    Ronilački centar može kreirati izlete povezane s postojećim lokacijama.

    Klijenti mogu pregledavati dostupne lokacije i izlete.

    Klijenti mogu rezervirati mjesto na izletima.

    Upravljanje korisnicima i autentikacija (planirano putem Email/Google prijave).

Kolekcije u bazi podataka:

    clijent — popis registriranih klijenata (ime, prezime, razina ronjenja, broj urona).

    ruts — popis organiziranih izleta (početak, kraj, lokacija).

    location — popis dostupnih lokacija za ronjenje (naziv, razina, geolokacija).

Tehnologije:

    Baza podataka: Cloud Firestore (NoSQL).

    Backend: Node.js (Express.js).

    REST API za dodavanje, ažuriranje, dohvaćanje i brisanje podataka.

    Firebase autentikacija i pravila sigurnosti baze (u planu).
