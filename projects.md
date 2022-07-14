---
layout: page
title: "Projects"
permalink: /projects/
---

### Private Cryptocurrency Gifting

#### Implementing New Transaction Types
----

![mobilecoin]({{site.baseurl}}/images/rustcode.png)

**Client:** Mobilecoin Inc.

**Years:** 2021-2022

**Description**

Mobilecoin is a cryptocurrency which encrypts all data about transactions sent on its network.

Several app partners requested the ability to send gifts of Mobilecoin to users who did not yet own Mobilecoin wallets. Designed/implemented a crypto scheme that allowed existing Mobilecoin account holders to send Mobilecoin people who do not yet have Mobilecoin accounts

<br>

### Forest Framework

#### Private Applications in Signal Messenger
----

![signal_app]({{site.baseurl}}/images/signal_app.jpeg)

**Years:** 2021-2022

**Description**

Framework enabling private, commerce enabled applications to be built within Signal

The framework is built from:

1. [Auxin](https://github.com/mobilecoinofficial/auxin) - A server-side Signal client implemented in Rust which allows applications to communicate with humans through Signal. Built using Signal's [libsignal](https://github.com/signalapp/libsignal) which exposes the cryptographic primitives behind the Signal Protocol needed to build 3rd party signal clients

2. [Forest](https://github.com/mobilecoinofficial/forest) - An async Python based application framework that allows people to build automated chat applications with AI driven dialog flow & fiat + cryptocurrency payments

**Links to Work**

*Live Applications*

* [Imogen](https://signal.group/#CjQKIBMsSPcIQYNjlSA1C1NqvapdjiZX31bdrCpH4ZI9BbwEEhAHOP7DVF1GjizAzYmOnDcY) - AI based art generator based on VQGAN/CLIP

* [Forest Email](https://signal.me/#p/+16266690001) - Private email addresses

* [Forest Contact](https://signal.me/#p/+447888866969) - Private phone numbers

*Github Links*

* [Auxin](https://github.com/mobilecoinofficial/auxin)

* [Forest](https://github.com/mobilecoinofficial/forest)

<br>

### Scripd

#### Automated Prescription Reminders Using NLP & Computer Vision
----

![medical_app]({{site.baseurl}}/images/medical_compressed.png)

**Client:** Scripd Inc.

**Years:** 2020-2021

**Description**

Scripd is a Flutter based app which allows users to scan their prescriptions & automatically populate prescription reminders. Text is recognized using CNN based Optical Character Recognition (OCR) & prescription data is populated using transformer based Named Entity Recognition (NER) applied to the text recognized by the OCR

Both the OCR & NER Models are run directly within the app to maximize speed & avoid the need for internet connectivity. Updates to the models are bootstrapped in the background when users are connected to WIFI

<br>

### BlockUSign

#### Document Signing via Ethereum Blockchain
----

![dash]({{site.baseurl}}/images/blockchain.png)

**Years:** 2018-2019

**Description**

Proof of concept of storing anonymous credentials on public blockchains

Blockusign takes a SHA256 hash of an uploaded document & Ethereum account public keys & stores it on the Ethereum blockchain. Any other user can validate that document later using the document and original Ethereum keys. If a user is signed in with their Ethereum account, the associated documents with their account will appear. Future plans were to enable document verification by correlating encrypted data from official records with documents

**Links to Work**

* [Blockusign](https://iamalwaysuncomfortable.github.io/dapp_testing_range/) (requires metamask)

<br>

### AI Support Assistant

#### Support Request Classification + Useful Language Integrations
----

![loggly]({{site.baseurl}}/images/loggly.png)

**Client:** Loggly

**Years:** 2014-2015

**Description**

1. Developed an ensemble classifier within salesforce that analyzed email & chatbot message content, company info & other related variables to classify the potential value of prospective clients & route them to support reps with specific recommendations

2. Developed plugins to enable log collection/shipping to Loggly for popular languages & software. The inbound classifier would automatically recommend specific integration code based on the text in client requests

**Links to Work** 

* [Logging in the Corona Game Engine](https://www.loggly.com/blog/logging-from-game-engines-part-two-logging-in-the-corona-sdk/)

* [Logging for Unity3d](https://www.loggly.com/blog/logging-in-unity3d/)

* [Customer Vertical Targeting](http://www.gamesauce.biz/2014/09/10/a-comprehensive-analysis-of-the-tools-that-support-mobile-game-development-part-1/)

<br>

### PlaySignals

#### Analytics Dashboard for Social Network Games
----

![dash]({{site.baseurl}}/images/research.gif)

**Client:** Game Titles Developed by Bitfold

**Years:** 2011-2013

**Description**

Analytics service for Bitfold's social network games which measured interactions of players with the game's interface. Measurements were warehoused into an isolated Postgres analytics database using stored procedures. An EC2 based web-service was run regularly to calculate metrics & statiscal analyses on collected data

Several game publishers chose to integrate the dashboard into their games

**Links to Work**

The service isn't operational anymore, but the following articles explain the thinking behind the product

* [Overview of the Social Game Industry](https://www.slideshare.net/Bitfold/social-facebook-game-space-at-a-glance)

* [Breaking into Social Game Development](https://www.adweek.com/digital/breaking-into-social-gaming-a-must-read-guide-to-entering-the-facebook-game-space/)

<br>
