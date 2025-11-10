# MedConnect---Proiect-PHP-Activitatea-unui-spital

## Descriere
MedConnect este o aplicație web care organizează și gestionează activitatea unui spital. Aplicația centralizează datele despre pacienți, programări, fișe medicale, rețete, analize, plăți și notificări, oferind acces diferit în funcție de rol: administrator, medic, asistent, recepționist sau pacient.

Pagina principală oferă informații generale despre spital: logo, program, locație, secții și personal medical. După autentificare, fiecare rol are funcționalități specifice:
- **Administrator:** gestionează utilizatorii, secțiile, resursele și generează rapoarte și statistici.  
- **Medic:** vizualizează și actualizează fișele pacienților, emite rețete și verifică programul asistenților.  
- **Asistent:** completează fișele pacienților, adaugă analize și gestionează programările.  
- **Recepționist:** gestionează programările pacienților și trimite notificări.  
- **Pacient:** vizualizează propriile date medicale, istoricul vizitelor, analizele, tratamentele și plățile efectuate.

## Tehnologii
- PHP, MySQL pentru back-end și gestionarea bazei de date  
- HTML, CSS, JavaScript pentru interfață și funcționalități dinamice  

## Structura aplicației
- Pagina principală cu informații generale  
- Pagini dedicate fiecărui rol după autentificare  
- Gestionarea entităților: `utilizator`, `pacient`, `medic`, `asistent`, `receptionist`, `sectie`, `sala`, `programare`, `fisa_medicala`, `reteta`, `medicament`, `analiza`, `plata`, `notificare`, `raport`, `statistica`  

## Funcționalități principale
- Autentificare și acces diferențiat după rol  
- CRUD complet pentru pacienți, programări, fișe medicale, analize, rețete și plăți  
- Gestionarea programărilor și notificarea pacienților  
- Vizualizarea istoricului și a datelor medicale  
- Generarea rapoartelor și statisticilor pentru administratori  
