# Nettside og webserver
Dette repositoryet viser koden til en relativt enkel nettside programmert hovedsaklig i PHP og HTML. Nettsiden ble brukt i prosjektoppgaven i IELS2001, og ble hostet på en Raspberry pi 3, ved hjelp av Apache. Mesteparten av koden er skrevet i texteditoren GNU Nano og formateringen er derfor litt rar enkelte steder, spesielt når det kommer til innrykk etc. 
## Forsiden:
![image](https://github.com/user-attachments/assets/30f0c1db-6dc2-4a36-b8bb-e66011f1d4c4)
Forsiden er relativt enkel, med et innloggingsfelt for å se brukersiden og en knapp som fører til ruteplanleggingssiden. 
## Ruteplanleggeren:
Ruteplanleggeren består av to felt og et svært enkelt kart. I feltene skal brukeren legge inn hvor brukeren befinner seg og hvor den skal. PHP-programmet sender da denne dataen til et python script som bruker en algoritme for å regne ut raskest rute til sluttpunktet avhengig av trafikken i nodene (Dijkstras algoritme).
![image](https://github.com/user-attachments/assets/30132479-cb70-4c82-a6d8-fa36195906a2)
## Brukersiden:
Brukersiden har et enkelt dashbord som viser en tabell over tidligere faktureriringer. Faktureringene blir sendt til det ene pythonprogrammet som regner ut en pris og deretter sender det videre til PHP. Tabellen oppdateres kontinuerlig ettersom nye faktureringer registreres. 
![image](https://github.com/user-attachments/assets/322ff53e-4fd6-4e7a-a65a-76bf72648e3e)
