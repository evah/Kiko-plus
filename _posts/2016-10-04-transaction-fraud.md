---
layout: post
title: "All About Fraud(1)"
description: ""
date: 2016-10-04
tags: [graph, fraud, transaction]
comments: true
share: true
---

I have been wondering about fraud for a while, especially transacation fraud and especially after my realizing how much loss it costs credit card companies every day. 

## What is it and How it works
[Wiki](https://en.wikipedia.org/wiki/Credit_card_fraud) has explained and illustrated clearly

1. Card fraud begins either with the theft of the physical card or with the compromise of data associated with the account, 
including the card account number or other information that would routinely and 
necessarily be available to a merchant during a legitimate transaction

2. Stolen cards
  - EMV requires passcode
  - ID or zipcode as additional id verification
  - "tap" < $100 is susceptible to fraud

3. Compromised merchants 
  - Name of card holder
  - Card number
  - Expiration date
  - Verification/CVV code

4. Card-not-present-transaction (CNP)
  - riskier than card-present transaction, and issuer changed more transaction rate
  - shipping companies can guarantee delivery to a location, but they are not required to check identification. 
  A common recent preventive measure for merchants is to allow shipment only to an address approved by the cardholder like AMAZON did. 
  - Customers expect to be able to use their credit card without any hassles, 
  and have little incentive to pursue additional security due to laws limiting customer liability in the event of fraud.

5. Identity fraud
  - Application fraud
  - Account take over

6. Skimming
  - Skimming is the crime of getting private information about somebody else's credit card used in an otherwise normal transaction
  - ATM
  - Gas station

7. Checker
  - Checker is a term used for a process to verify the validity of stolen card data.
  - A website known to be susceptible to carding is known as a cardable website.
  - A set of credit card details that has been verified in this way is known in fraud circles as a phish. 
  A carder will typically sell data files of the phish to other individuals who will carry out the actual fraud. 
  Market price for a phish ranges from US$1.00 to US$50.00 depending on the type of card, 
  freshness of the data and credit status of the victim.

8. BIN attack
  - Credit cards are produced in BIN ranges. 

9. Balance transfer checks

10. Unexpected repeat billing

By reading the WIKI, the part I do not understand and would like to explore 
is about "chargeback right" of the issuers to the merchants when the fraud happens, 
and when that right can be overturned by the merchants. 

## Accidentally, I found something interesting on Github.com how some company wants to address this problem
[Credit Card Transaction Monitor](https://github.com/vakshorton/CreditCardTransactionMonitor) 

> Credit Card Transaction Monitor is an example of a Modern Data Application running on the Hortonworks Connected Platform (HDP/HDF).
The application shows how a financial institution can use Hortonworks Data Flow and Hortonworks Data Platform to 
protect credit card customers from credit card fraud. 

[Credit Card Transaction Monitor Mobile App](https://github.com/vakshorton/CreditCardTransactionMonitorMobileApp)

> Mobile application designed to be used with the CreditCardTransactionMonitor demo.
This mobile application demonstrates how the connected platform allows the customer to provide feedback as 
to whether the account was correctly disabled due to suspected fraud. If the suspected transaction is legitimate, 
then the customer is able to unlock the account

To be continued. 
