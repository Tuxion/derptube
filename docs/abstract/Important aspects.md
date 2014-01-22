# Decentralized Entertainment Releasing Protocol
(DerpTube)

This document will list the important aspects the design of this protocol should keep in mind as well as findings or solutions for each subject. You can consider it to be a requirements document, just more abstract. Keep in mind this is a live document.

## Contents

* 1) **Different content providers**
	- 1a) Private providers
	- 1b) Professional providers
	- 1c) Media platforms
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

## 1) Different content providers

We've identified different kinds of content providers that each have different requirements for a media sharing means to suit them. Since we want the protocol to be very widely usable we'll try to take them into account here.

### 1a) Private providers

This group of providers includes pretty much everyone on the planet. They are the "normal" users that just want to share a video or a song with their mother. They do not want to make money with their video's and as such don't want to spend too much on it either.

**This group requires:**

- Cheap / free hosting.
- Sharing and watching should be very user friendly.
- Any uploading / converting should not take long.
- Must not require technical knowledge.

**This group benefits from:**

-  Being able to watch before uploading is completed.
-  Not having to upload at all.
-  Viewers not being bothered by advertisements.
-  Viewers not being required to sign up.
-  A "private video" feature (access control).

**This group dislikes:**

- Expenses.
- Difficult applications.
- Having to take much time to configure / upload.
- Having to explain their mom where and how to open that video.

### 1b) Professional providers

This group has a different approach, since they want to make a living (directly or indirectly) with their content. They have more time and money to spend on making things work the way it works best for them, but it should be worth their while.

**This group requires:**

- Means to get direct revenue from content.
- Means to use the content as promotional for their product/service (indirect revenue).
- It must be worthwhile to invest in their method.
- Clear branding of their name.
- High availability of their content.
- Means to build up viewer loyalty.

**This group benefits from:**

- A large audience.
- Means to notify viewers of new content or promotions.
- Competitively priced hosting services.
- Configuration of revenue means.
- Reliable and detailed statistics.
- A community aspect (such as comments being distributed across presentations).
- Spam prevention.
- Strong authenticity.
- A reasonable guarantee that their content will be available for a long time.
- Extensive access control (across all levels).

**This group dislikes:**

- Wasting their investments (time or money).
- Poor content availability.
- ASCII penises and viruses being distributed right next to their content.
- Fakes who try to make money using their content or reputation.
- Having no control over how their content is presented.

### 1c) Media platforms

Another commercial group, just with a different scale in mind for their organisation. Think about publishers, news channels, music stations or associations of content creators. They will have a lot of high quality content to put out there and the resources to make it happen. But in the long run it's got to have the intended effects.

**This group requires:**

- Means for direct / indirect revenue, like the professional providers.
- Strong authenticity and clear branding of their name.
- High availability and high capacity for their content.
- Means to build up viewer loyalty.
- Reliable and detailed statistics.
- Configuration of revenue means.
- Extensive access control (across all levels).
- Good long term prospects for their approach.

**This group benefits from:**

- A large audience.
- Additional options to market/promote their content.
- Having control over the quality of the infrastructure.
- Means to notify viewers of new content or promotions.
- Spam prevention.
- Competitively priced hosting services.
- Strong means to ensure all parties keep to "their end of the deal".

**This group dislikes:**

- Having all this money to invest, but having nothing sensible to invest into.
- Their brand being stained.
- Having an unstable audience.
- Suffering from a lack of bandwidth.
- Not being able to drive a lot of traffic to their content.
- Having to settle for sub-optimal situations, because there's no alternative.

## 2) Revenue

For anything in the entertainment industry to not just blow over like a hype. It's got to have good business opportunities. So we'll go over some of the predictable ways to generate revenue for each party.

### 2a) Presenting services

Traditionally speaking, the presentation layer is where a significant part of the revenue was generated. Advertisements can be displayed alongside, before, after or in between the content. This is easy to reap profits of.

Another way is to provide premium services to your users. Ad-free watching, offline viewing, mobile access, etc. Since these are not 1:1 related to the amount of views, you will probably have to work out a model yourself which part of that is shared with content creators or kept as profits.

Since you do not possess the content, the content provider may demand that you share your income and have a presentable appearance and reasonable policy. But in return, you do not have to invest in the infrastructure to host the actual content.

In summary:

- Possible income from advertisements.
- Possible income from offering premium features.
- May have to share income with content providers.
- Low cost for running the website, because no infrastructure is required for the content hosting.

### 2b) Content creators

Similarly to traditional platforms, you will not be the one receiving revenue directly but rather you can be rewarded for opening up your content to other services. This time around however, you get to have more control over the terms under which you share your content. You will also encourage fair competition this way, which will hopefully leave everyone with a better deal.

There will be many different services involved that collectively make up your total revenue. Each service having their own policy. If you reject one (for example "evil.com" who changed their policy and will drown a kitten for every 10.000 views) it won't mean a 80% loss of your revenue. This will protect you from mega-corporations forcing their policy onto you (if you want to keep your business running that is) as well as open up the market to try out new business models.

In summary:

- Compensations for access to your content is the main revenue.
- You decide the terms and compensation rates under which your content will be shared.
- New business models yet to be discovered, based on available services.

### 2c) Hosting services

>TODO

### 2d) Sharing revenue

>TODO

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