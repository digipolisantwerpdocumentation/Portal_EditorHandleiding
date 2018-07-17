# ACPaaS Portal - Gebruikershandleiding
_____________________________________

## Aanpassen footer 

* Aanpassen logo, description, product categories titel, copyright en terms & conditions

* Linker menu item Content

* Edit content met NAME “Footer” (in Content type “Footer”)

* Pas Logo, Description, Title, Copyright en Terms & Conditions URL en Description aan

* Save as published


## Aanpassen social media links

* Creëer of editeer social media links (zie afzonderlijke sectie)

* Linker menu item Content

* Edit content met NAME “Footer” (in Content type “Footer”)

* Selecteer de juiste social media links onder Social Media

* Save as published


## Aanpassen product categories

* Linker menu item Views

* Edit view met NAME “Product categories”

* Pas view aan

* Save view


## Aanpassen links in 2 rechter kolommen

* Linker menu item Menu

* Edit menu met TITLE “Footer”

* Editeer de structuur via Structure:

> Titels kunnen aangepast worden via het Title attribuut van items op niveau 2

> Toegankelijkheid links kan aangepast worden via Taxonomy van items op niveau 3 

* Links naar basic pages: type “External Content”, URL “docs/<slug>” met slug van de basic page dewelke als custom of hidden item moet zijn toegevoegd aan de main documentation 

* Save Menu


## Aanpassen home page banner

* Linker menu item Content

* Edit content met NAME “Home Page” (in Content type “Home”)

* Pas Title, Intro en Banner aan

* Save as published

> Opmerking: Niet als draft bewaren. WCM V3 werkt niet met historiek en content heeft enkel een attribuut om aan te geven of het draft dan wel published is. ACPaaS Portal V3 toont enkel de banner enkel indien deze published is, dus als je als draft bewaard dan verdwijnt de banner.


## Aanpassen labels via PO files

* Linker menu item Consumer Translations

* Edit consumer translation group met NAME “frontend”

* Download po file van language met NAME “nl”

* Editeer po file met tekst editor

* Upload nieuwe versie po file via Choose a .po file or drag it here

> Opmerking: Nieuwe waarden na browser refresh ACPAAS Portal V3 zichtbaar


## Aanpassen main documentation


* Linker menu item 'Content' selecteren
* Edit content met NAME “Algemene Documentatie” (in Content type “Main documentation”)
* Pas Title, About en Getting started aan
* Pas linker menu aan via Custom items

### Submenu’s

> Het linker menu van de main documentation ondersteunt geen sub menu’s. Een workaround is om de hoofdpagina basic page toe te voegen aan de main documentation Custom items. Subpagina basic pages dienen toegevoegd te worden aan de main documentation onder Hidden items. In de hoofdpagina basic page kan dan in de Body een link naar de subpagina gelegd worden met Link Type “URL”, Protocol “<other>” en URL “docs/<slug>” met slug van de basic page dewelke als hidden item moet zijn toegevoegd aan de main documentation. 

## Aanpassen product

* Slack channel: Slack channel van het product zonder “#” prefix zoals aangegeven in kolom C van spreadsheet 

* Contact Email: email adres van het product zoals aangegeven in kolom D van spreadsheet 


## Naming conventions (suggestie)

### Contact Person

Administration name: <“CO” of “PO” of “TA”> || “ “ || First Name || “ “ || Last Name

### Function: 
* “Co-ouder” of “Product Owner” of “Technisch Architect”

> (Motivatie voor bovenstaande is dat dit de selectie van het timeline item in de Contact Person sectie van het product vergemakkelijkt)

### API

* Administration name: ‘API ‘ || naam API || ‘ ‘ || ‘v’ || version API

* Slug: default die wordt voorgesteld behouden (dus api-naam-vx)

### Product Doc Version

* Administration name: naam product || ‘ ‘ || v<Version Major>.<Version Minor>.<Version Patch>

* Slug: default die wordt voorgesteld behouden

> (Motivatie voor bovenstaande is dat de version bumper dezelfde naamgeving toepast)

### Timeline Item

* Administration name: naam product || ‘ <version> ‘

> (Motivatie voor bovenstaande is dat dit de selectie van het timeline item in de Roadmap sectie van het product vergemakkelijkt)
