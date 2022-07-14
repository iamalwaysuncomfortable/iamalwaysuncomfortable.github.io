---
layout: page
title: "Projects"
permalink: /projects/
---

### Forest Framework

#### Private Applications In Signal Messenger
----

![signal_app]({{site.baseurl}}/images/signal_app.jpeg)

**Years:** 2021-2022

**Description**

Commerce enabled app framework built to enable private applications to be built within the Signal app. 

The framework is built from:

1. [Auxin](https://github.com/mobilecoinofficial/auxin) - A Rust based server-side Signal client which allows applications to communicate with humans through Signal. Built using Signal's [libsignal](https://github.com/signalapp/libsignal) which exposes the cryptographic primitives behind the Signal Protocol needed to build 3rd party signal clients

2. [Forest](https://github.com/mobilecoinofficial/forest) - An async Python based application logic framework that allows people to build automated chat applications with AI driven dialog flow & fiat + cryptocurrency payments

**Links to Work**

*Live Bots*

[Imogen](https://signal.group/#CjQKIBMsSPcIQYNjlSA1C1NqvapdjiZX31bdrCpH4ZI9BbwEEhAHOP7DVF1GjizAzYmOnDcY) - AI based art generator based on VQGAN/CLIP

[Forest Email](https://signal.me/#p/+16266690001) - Private email addresses

[Forest Contact](https://signal.me/#p/+447888866969) - Private phone numbers

*Github Links*

[Auxin](https://github.com/mobilecoinofficial/auxin)

[Forest](https://github.com/mobilecoinofficial/forest)

<br>

### Scripd

#### Automated Prescription Reminders Using NLP & Computer Vision
----

![medical_app]({{site.baseurl}}/images/medical_compressed.png)

**Client:** Scripd Inc.

**Years:** 2020-2021

**Description**

Scripd is a Flutter based app which uses which combines CNN based Optical Character Recognition (OCR) and transformer based Named Entity Recognition (NER) to enable users to scan their prescriptions and automatically populate prescription reminders.

Both the OCR & NER Models are run directly within the app to get high speed results and avoid the need for internet connectivity. Updates to the models are bootstrapped in the background when the users are connected to wifi.

<br>

### BlockUSign

#### Document Signing via Ethereum Blockchain
----

![dash]({{site.baseurl}}/images/blockchain.png)

**Years:** 2018-2019

**Description**

Proof of concept for a client who wanted to build a blockchain 
based identity system for validating licensing and registrations for businesses. 

Blockusign takes a SHA256 hash of an uploaded document and stores it on 
the public Ethereum blockchain. Any other user can validate that document later.
If the user is signed in with their ethereum account, 
the associated documents with their account will appear, proving document authorship.


**Links to Work**

* [Blockusign](https://iamalwaysuncomfortable.github.io/dapp_testing_range/) (requires metamask)

### Inbound Client Classification Engine

#### Classifying Support Requests + Building Useful Integrations
----

![loggly]({{site.baseurl}}/images/loggly.png)

**Client:** Loggly

**Years:** 2014-2015

**Description**

1. Developed an ensemble classifier within salesforce that analyzed email & chatbot message content, company info & other related variables to classify the potential value of prospective clients and route them to support reps with specific recommendations

2. Developed plugins to enable log collection/shipping to Loggly for popular languages & software. The inbound classifier would automatically recommend specific integration code based on the text in client requests

**Links to Work** 

* [Logging in the Corona Game Engine](https://www.loggly.com/blog/logging-from-game-engines-part-two-logging-in-the-corona-sdk/)

* [Customer vertical targeting](http://www.gamesauce.biz/2014/09/10/a-comprehensive-analysis-of-the-tools-that-support-mobile-game-development-part-1/)

<br>

### Analytics Dashboard for Social Network Games
----

![dash]({{site.baseurl}}/images/research.gif)

**Client:** Game Titles Developed by Bitfold

**Years:** 2011-2013

**Description**

Analytics service for Bitfold's social network games which measured interactions of players with the game's interface & warehoused measurements into an isolated Postgres analytics database using stored procedures. An EC2 based web-service calculated metrics & statiscal analyses on collected data regularly

Several Bitfold Clients chose to integrate the dashboard into their games

**Links to Work**

The service isn't operational anymore, but the following articles explain our thinking

* [Overview of the Social Game Industry](https://www.slideshare.net/Bitfold/social-facebook-game-space-at-a-glance)

* [Breaking into Social Game Development](https://www.adweek.com/digital/breaking-into-social-gaming-a-must-read-guide-to-entering-the-facebook-game-space/)

<br>
