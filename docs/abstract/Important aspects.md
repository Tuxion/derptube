# Decentralized Entertainment Releasing Protocol
(DerpTube)

This document will list the important aspects the design of this protocol should keep in mind as well as findings or solutions for each subject. You can consider it to be a requirements document, just more abstract. Keep in mind this is a live document.

## Contents

* 1) **Different content providers**
	- 1a) Personal providers
	- 1b) Small professional providers
	- 1c) Large professional providers
* 2) **Revenue**
	- 2a) Presenting services
	- 2b) Content creators
	- 2c) Hosting services
	- 2d) Sharing revenue
* 3) **Authenticating and identifying**
 	- 3a) Content creators
 	- 3b) Channels
 	- 3c) Media content
 	- 3d) Presenting services
 	- 3e) User comments
* 4) **Access control and filtering**
	- 4a) Content creators
	- 4b) Presenting services
	- 4c) User comments
	- 4d) Illegal content / violation of terms
	- 4e) Spam prevention


## Original notes

			## Important aspects
			### Covering the solution...
			Aspecten die de oplossing zou moeten dekken:
			* A protocol-coupled system which enables and ensures revenue for both the host and the presenters.
			* Authetication for the content host.
			* Focus on user-friendlyness and accessibility: Anyone should easily be able to become a host of their own video content via any operating system and without prior knowledge or experience.
			    - Verdiensten voor de "schil"
			    - Verdiensten voor de "autheur"
			    - De verhoudingen van de verdiensten
			    - Mogelijkheid voor de autheur om te bepalen wie de content mag "presenteren" en daarmee een mogelijkheid om content weer te verwijderen.
			    - Aansprakelijkheid voor de content
			    - Sterke authenticatie voor content-bron
			    - Propageren van de meta-data
			    - Het protocol moet simpel genoeg zijn om een [toekomstige] gebruikersvriendelijke implementatie mogelijk te maken.
			    - Capatiteit moet schaalbaar zijn.
			    - "Hoe houd je de kinderporno van je site?"
			    - "Hoe voorkom je misbruik als, content spamming?"
			    - Een mogelijkheid om snel op de hoogte te komen van ongewenste inhoud. Bijvoorbeeld een rapporteer-netwerk.
			## Potential technicallities...
			Technieken om in gedachten te houden:
			    - Bitcoin: voor snelle verdeling van inkomsten.
			    - DNS record: SRV, voor het aangeven van de benodigde poorten.
			    - XMPP: optie voor het propageren van de video meta-data.
			    - SSL: voor het controleren van de echtheid van de autheur. En om de drempel te verhogen voor spammers.
			    - Torrents: voor de gebruikers die geen geld voor een server hebben.
			Optioneel om over na te denken:
			    - Grote content-hosts kunnen mogelijk een verdienmodel opzetten voor het hosten van andermans content.