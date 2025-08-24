#Pleyade Overdrachten Generator

Welkom bij de Pleyade Overdrachten Generator, een webapplicatie die speciaal is ontworpen om fysiotherapeuten te ondersteunen bij het efficiënt en consistent opstellen van overdrachtsdocumenten.

Deze applicatie is volledig client-side gebouwd en stelt je in staat om via spraakinput de benodigde gegevens in te voeren. Deze worden vervolgens automatisch omgezet in een professioneel overdrachtsdocument in Microsoft Word-formaat.

Belangrijkste Functies
Spraak-naar-tekst: Voer informatie in door te spreken in plaats van te typen.

Gestructureerde output: De ingesproken informatie wordt automatisch georganiseerd in een gestandaardiseerd en professioneel overdrachtsdocument.

Consistentie: Zorgt voor een uniforme structuur en terminologie in alle gegenereerde documenten.

Gebruiksvriendelijk: De interface is intuïtief, volledig in het Nederlands en sluit aan bij de huisstijl van Pleyade.

Word-export: Genereert direct een downloadbaar .docx-bestand.

Hoe het werkt
De applicatie maakt gebruik van de volgende externe API's voor de verwerking van je input:

AssemblyAI: Verantwoordelijk voor het omzetten van gesproken audio naar tekst (transcriptie).

OpenAI: Structureert de getranscribeerde tekst en zet deze om in een professioneel medisch rapport.

docx.js (of vergelijkbaar): Een library die de gestructureerde tekst omzet in een downloadbaar Microsoft Word-document (.docx).

Gebruiksaanwijzing
Open de applicatie: Klik op het meegeleverde HTML-bestand om de applicatie te openen in je browser.

Spreek de velden in: Klik op de opnameknop naast elk invoerveld om je gesproken informatie vast te leggen.

Controleer en bewerk: De getranscribeerde tekst verschijnt in het veld. Je kunt deze handmatig aanpassen of corrigeren indien nodig.

Genereer het document: Klik op de knop 'Downloaden' onderaan de pagina. De applicatie verwerkt nu alle informatie.

Downloaden: Het Word-document wordt automatisch gegenereerd en aangeboden als een download in je browser.

Technische Details
Front-end: HTML, CSS, JavaScript (Single-Page Application).

Externe API's: AssemblyAI voor transcriptie, OpenAI voor tekstopmaak.

Architectuur: Geheel client-side; er is geen back-end server nodig.

Security: Let op: in een productieomgeving moeten de API-sleutels beveiligd worden opgeslagen en mogen ze niet direct in de client-side code staan.

Deze applicatie is ontworpen om je werk te versnellen en te vereenvoudigen. Voor vragen of feedback kun je contact opnemen met het ontwikkelteam.
