# MijnCBM templates

Spreadsheet ten behoeve van het invullen van data in MijnCBM. Met deze spreadsheet kun je ING transactie data labelen met de categorien die door [MijnCBM](https://www.rechtspraak.nl/onderwerpen/mijn-cbm) gebruikt worden. De sheet berekent dan de totalen per categorie.

## Stappen

1. Ga naar ING.nl en download een overzicht van de relevante transacties als CSV bestand. Kijk hier om te leren hoe dat moet: https://www.ing.nl/particulier/digitaal-bankieren/afschriften-downloaden
2. Open het CSV bestand in je spreadsheet editor (Excel, OpenOffice Calc, etc.). Waarschijnlijk krijg je dan een 'Import wizard', daar kun je selecteren dat het om comma-separated values gaat, zodat de kolommen en de waardes juist geinterpreteerd worden.
3. Als het bestand geopend is, kopieer dan de hele sheet.
4. Open het bestand [mijncbm-ing.fods](mijncbm-ing.fods). FODS is een spreadsheet bestandsformaat, net zoiets als XLS of XLSX.
5. Plak de inhoud van je clipboard in de eerste tab van `mijncbm-ing.fods`, "ING CSV Transacties"
6. Ga nu naar de middelste tab van `mijncbm-ing.fods`, "Transacties met labels". Je ziet daar de datum, de naam, en het bedrag van iedere transactie. Om transacties te labelen, ga naar kolom D en selecteer een item van het dropdown menu.
7. In de meeste rechtse tab van `mijncbm-ing.fods`, "Totalen per label" kun je zien wat de totale waarde van transacties met een gegeven label is.
