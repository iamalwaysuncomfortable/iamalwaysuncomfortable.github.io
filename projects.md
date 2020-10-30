---
layout: page
title: "Past Projects"
permalink: /projects/
---

Below are a collection of selected projects I've executed 
(and am legally permitted to show)

## Machine Learning and Analytics

### Natural Language Understanding from Medical Data in Mobile Health App
----

**Client:** Scripd Inc.

![medical_app]({{site.baseurl}}/images/medical.png)

**Years:** 2020

**Description:**

Created a semi-supervised neural network nodel incorporating a transformer based Named Entity Recognition (NER) model
that takes text data from a mobile OCR scan of prescription data and automatically classifies
import medical information on the prescription (such as dosage, frequency of use, quantity, and drug interactions)
that is incorporated into reminders for patients.

The Model is run on the edge within the app to avoid having to make outbound API calls and is automatically updated
in the background when a new model is published.

<br>


### In-Game Recommendation Engine
----

**Client:** Undisclosed Game Industry Client

![game]({{site.baseurl}}/images/game.png)

**Years:** 2017-2018

**Description:**

Analytics service that runs alongside the main Amazon Gamelift backend.
The service is a lightweight collection of microservices in containers that collects data on
player in-game actions data into a MongoDB database. 

Collected data is consumed by a clustering algorithm
 to create player classifcations based upon groups of related behaviors. 
 From those classifications, a set of customized actions is recommended to each player group
to help maximize their engagement in-game. Collected data was also used to create a dashboard (using DASH)
to visualize player metrics.

<br>

### Inbound Client Classification
----

**Client:** Loggly

![loggly]({{site.baseurl}}/images/loggly.png)

**Years:** 2014-2015

**Description:**

Development and personal execution of a 3-fold technical marketing strategy focused on gaining more game industry clients

1. Generated game industry focused ads and viral content. Paired with a running statistical evaluation of the effectiveness of traffic sources
2. Deployed an ensemble classifier within salesforce that analyzed the message content, company info, interactions with the logging software, and other related variables to classify the potential value of client and route it to the correct sales rep
3. Developed loggly logging plugins for key game development tools

**Links to Work:** 

* [Logging in the Corona Game Engine](https://www.loggly.com/blog/logging-from-game-engines-part-two-logging-in-the-corona-sdk/)

* [Inbound marketing example](http://www.gamesauce.biz/2014/09/10/a-comprehensive-analysis-of-the-tools-that-support-mobile-game-development-part-1/)

<br>

### Analytics Dashboard for Social Network Games
----

![dash]({{site.baseurl}}/images/research.gif)

**Client:** Bitfold Internal Games & Several Bitfold Clients

**Years:** 2010-2013

**Description:**

A service tied to Bitfold's social network games which measured 
 interactions of players with the game's interface and 
warehoused these measurements into a Postgres database. An EC2 based web-service
then calculated a variety of metrics and statiscal analyses every 60 seconds
and cached them where they could be read & displayed by the web-front end.

Several Bitfold Clients chose to have us implement this dashboard system into their games.

**Links to Work**

The service isn't operational anymore, but the following articles explain our thinking

* [Overview of the Social Game Industry](https://www.slideshare.net/Bitfold/social-facebook-game-space-at-a-glance)

* [Breaking into Social Game Development](https://www.adweek.com/digital/breaking-into-social-gaming-a-must-read-guide-to-entering-the-facebook-game-space/)

<br>

## Blockchain

### BlockUSign: Document Signing via Ethereum Blockchain
----

![dash]({{site.baseurl}}/images/blockchain.png)


**Years:** 2018-2019

**Description:**

Demonstration project for a client who wanted to build a blockchain 
based identity system for validating licensing and registrations for businesses. 

Blockusign takes an MD5 hash of an uploaded document and stores it on 
the public Ethereum blockchain. Any other user can validate that document later.
If the user is signed in with their ethereum account, 
the associated documents with their account will appear, proving document authorship.


**Links to Work:**

* [Blockusign](https://iamalwaysuncomfortable.github.io/dapp_testing_range/)
