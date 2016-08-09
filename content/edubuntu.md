---
date: 2016-06-14T22:37:50+02:00
title: Edubuntu
menu:
  mainnav:
    parent: afgeleiden
    weight: 20
    identifier: edubuntu
    name: Edubuntu
aliases:
  - /afgeleiden/edubuntu
  - /node/83
---

# Edubuntu
Het primaire doel van Edubuntu is het mogelijk maken dat een docent of ouder met beperkte technische kennis in staat is om een computerlab of een online leeromgeving in minder dan een uur op te zetten, en om die omgeving eenvoudig te kunnen beheren. Deze distributie is gemaakt met het oog op educatie en overzicht(?); de docent of ouder kan zelf bepalen welke websites bezocht mogen worden en welke programma's de kinderen mogen openen.

Edubuntu is geschikt voor gebruikers van 6 tot 18 jaar en bevat een groot aantal educatieve programma's. Voor de ouder of docent is er een centraal beheer van configuratie, gebruikers en processen opgezet. Ook zijn er samenwerkmogelijkheden in een klassikale omgeving en ondersteunt Edubuntu een LTSP-thin-client-architectuur die het mogelijk maakt om gebruik te maken van relatief goedkope en energiezuinige gebruikerscomputers die worden aangesloten op een centrale server.

Voor een visuele indruk kunt u de schermafbeeldingen op de officiële [Edubuntu website bekijken](https://www.edubuntu.org/screenshots).

## Systeemeisen
Voor de meest recente versie van Edubuntu, versie 14.04.4 LTS, gelden de volgende systeemeisen:

- **Standalone installatie:**
  - Processor: 1GHz of sneller
  - Werkgeheugen: 512MB RAM om het te laten draaien, 1GB aan RAM om het soepel te laten draaien.
  - Opslag: Afhankelijk van de gekozen opties; 20GB is aan te raden.
  - Videokaart: Als de netbook interface gebruikt wordt, is een 3D-ondersteunende videokaart benodigd. Echter zijn de meeste netbooks goed ondersteund, dus dat zou geen probleem moeten opleveren.

- **LTSP Server:**
	- Processor: Minimaal aangeraden zijn een Core 2 Duo of een Core 2 Quad, sneller is aangeraden. Trager kan, maar dat zal ten koste gaan van de snelheid van het systeem.
	- Werkgeheugen: 512MB voor de server zelf en tussen de 256MB en 768MB RAM per thin-client, afhankelijk van hoe de thin-clients gebruikt worden. 4GB RAM voor 20 LTSP gebruikers is het absolute minimum, ideaal is minimaal 8GB. Overigens is het ook mogelijk locale applicaties (local apps genoemd) te gebruiken om wat RAM gebruik over te brengen naar de thin-client.
	- Opslag: Minstens 20GB, afhankelijk van opties. Aangeraden is het plaatsen van de /home partitie op een snelle schijf voor optimale prestaties. Voor meer informatie over het installeren van Edubuntu in een RAID configuratie, kunt u het beste de [officiële Edubuntu installatie-gids (Engels)](https://www.edubuntu.org/documentation/12.04/installation-guide) raadplegen.
	- Netwerk: LTSP kan erg veeleisend zijn van locale netwerken en het is daarom aan te raden om minimaal 1 gigabit connectie naar de server te hebben per 15 thin-clients, en minimaal 100mbit connecties naar de thin-clients vanaf de switches.

- **LTSP Thin Clients:**
	- Processor: Een Intel i686 compatible processor. De meeste processoren zullen prima werken. Geode en oudere Via processoren worden niet ondersteund.
	- Werkgeheugen: Minimaal 128MB, meer RAM is nodig voor het draaien van locale applicaties.
	- Netwerk: Een 100mbps netwerk connectie met PXE of vergelijkbare ondersteuning voor netwerk booting.

Specificaties zijn een vertaling van de [officiële Edubuntu installatie-gids (Engels)](https://www.edubuntu.org/documentation/12.04/installation-guide).

{{< button url="/download" text="Klik hier om naar de downloadpagina te gaan" >}}
