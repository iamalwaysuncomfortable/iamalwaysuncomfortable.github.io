---
layout: page
title: "Projects"
permalink: /projects/
---

A mix of open and closed source software I've worked on throughout the years. Most projects have links you can follow in order to interact with the software directly

### Private Cryptocurrency Gifting

#### Implementing New Transaction Types
----

![mobilecoin]({{site.baseurl}}/images/rustcode.png)

**Client:** Mobilecoin Inc.

**Years:** 2021-2022

**Description**

Expanding the number of useful transaction types within the Mobilecoin blockchain

It was desired to create the ability to send Mobilecoin to mobile phone users who did not yet have Mobilecoin accounts. A solution was created allowing Mobilecoin account holders to send a transaction to a reserved subaddress and then send the data needed to create an account and redeem that transaction over gRPC to a counterparty without a mobilecoin account

**Links To Work**

* [API Endpoints](https://mobilecoin.gitbook.io/full-service-api/api-endpoints/gift-code/claim_gift_code)

* [TxOut Gift Code MCIP](https://github.com/mobilecoinfoundation/mcips/blob/main/text/0032-fog-compatible-gift-codes.md)

* [Block Metadata MCIP](https://github.com/mobilecoinfoundation/mcips/blob/main/text/0043-block-metadata.md)

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

2. [Forest](https://github.com/mobilecoinofficial/forest) - An async Python based application framework that allows people to build automated chat applications with AI driven dialog flow and fiat + cryptocurrency payments

Mobilecoin, a cryptocurrency integrated into Signal Messenger acquired the Forest Framework 2021 in order to provide developers with a platform to build Signal apps that supported Mobilecoin transactions

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

#### Automated Prescription Reminders Using NLP and Computer Vision
----

![medical_app]({{site.baseurl}}/images/medical_compressed.png)

**Client:** Scripd Inc.

**Years:** 2020-2021

**Description**

Scripd is a Flutter based app which allows users to scan their prescriptions and automatically populate prescription reminders. Text is recognized using CNN based Optical Character Recognition (OCR) and prescription data is populated using transformer based Named Entity Recognition (NER) applied to the text recognized by the OCR

Both the OCR and NER Models are run directly within the app to maximize speed and avoid the need for internet connectivity. Updates to the models are bootstrapped in the background when users are connected to WIFI

<br>

### BlockUSign

#### Document Signing via Ethereum Blockchain
----

![dash]({{site.baseurl}}/images/blockchain.png)

**Years:** 2018-2019

**Description**

Proof of concept for credential verification on Ethereum

BlockUSign takes a hash of an uploaded document, signs it with an Ethereum account's private key and stores it on the Ethereum blockchain. Any other user can validate that document later using the document and public key of an Ethereum account. If a user is signed in with their Ethereum account, the app will scan the Ethereum chain for the associated documents and display them to the user

This served as a proof of concept for a larger product designed to allow people to prove ownership of sensitive official credentials (such as financial statements or medical records) to counterparties in a private way

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

Custom AI layer built into a Salesforce CRM for recommending actions to increase sales conversion and improve responses to support requests. The framework performs the following tasks:

1. Classify the potential value of prospective clients and route them to support reps with specific sales recommendations
2. Add customized responses to automated support email and chatbot replies
3. Classify support requests from existing clients with severity levels and recommendations

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

Analytics service for multiplayer mobile games

Measurements of player in-game actions and game state were collected by the UI and warehoused into a Postgres database. Metrics and simple predictive models were built into Postgres stored procedures and run against the data regularly. An EC2 based web-service was used to generate visualizations of the data onto a browser based dashboard for analysts on demand

Several game publishers chose to integrate the dashboard into their games

**Links to Work**

The service isn't operational anymore, but the following articles explain the thinking behind the product

* [Overview of the Social Game Industry](https://www.slideshare.net/Bitfold/social-facebook-game-space-at-a-glance)

* [Breaking into Social Game Development](https://www.adweek.com/digital/breaking-into-social-gaming-a-must-read-guide-to-entering-the-facebook-game-space/)

<br>
