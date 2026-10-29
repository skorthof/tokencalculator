Byner AI Usage Calculator v2

index.html: gebruikerscalculator (zes onderdelen, 0-200 per onderdeel)
pricing.json: centraal beheerde tarieven
admin.html: lokaal beheerscherm voor het EXPORTEREN van pricing.json

Publiceren: plaats index.html en pricing.json samen op een webserver; publiceer admin.html NIET. Wijzig prijzen lokaal via admin.html, download de nieuwe pricing.json en vervang het serverbestand. Een statische website heeft geen beveiligde adminlogin; voor online wijzigingen door beheerders is serverauthenticatie nodig. Bij dubbelklikken op index.html werkt een offline standaardprijs als fallback omdat browsers fetch van lokale JSON kunnen blokkeren.

Versie 2.1: Parse Interview Notes toegevoegd als een gebruikersactie met twee API-calls (input 5853, output 1144).
