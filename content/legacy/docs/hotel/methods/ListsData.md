---
title: Lists of Data
keywords: hotel, data structure, list data
search: Hotel - Data Structure - Lists of Data
sidebar: mydoc_sidebar
permalink: /docs/hotel/DSF/ListData
---



### Method Goals


This paragraph aims to return all of the data lists used in our system: language codes, error codes,currency list, credit cards, nationality and market.

<div class="anchor-offset" id="languages-codes"></div>

### Language Codes


| **Language**	| **Code**	|
| ------------- | ------------- |
|  English      | en		|
|  Spanish      | es		|
|  Portuguese   | pt		|
|  Italian      | it		|
|  French       | fr		|
|  German       | de		|
|  Brazilian    | br		|


<div class="anchor-offset" id="error-codes"></div>

### Error codes



| **Code**	| **Description**												|
| ------------- | ------------------------------------------------------------------------------------------------------------- |
|  101         	| System Exception (Exception not controlled or not classified as general exception).			|
|  102         	| Supplier Error.					|
|  104         	| Timeout (Timeout during the execution of an operation (look in the common attribute timeout )).		|
|  105         	| Communication Error. 		|
|  204         	| Supplier returns 0 results in availability.									|
|  205         	| The Supplier doesn't accept the distribution RQ.								|
|  206         	| The Supplier doesn't accept the dates RQ.									|
|  207         	| The Supplier doesn't accept the request RQ.									|
|  301         	| Option not found in policies.											|
|  302         	| Hotel Not Found in DescriptiveInfo.											|
  

<div class="anchor-offset" id="currency-codes"></div>

### Currency codes


Our system uses a standard ISO - 3 for all suppliers.

<div class="anchor-offset" id="credit-cards"></div>

### Credit Cards



| **Codes**	| **Names**			|
| ------------- | ----------------------------- |
|  VI      	| Visa				|
|  AX      	| American Express		|
|  BC      	| BC Card			|
|  CA      	| MasterCard			|
|  CB      	| Carte Blanche			|
|  CU      	| China Union Pay		|
|  DS      	| Discover			|
|  DC      	| Diners Club			|
|  T       	| Carta Si			|
|  R       	| Carte Bleue			|
|  N       	| Dankort			|
|  L       	| Delta				|
|  E       	| Electron			|
|  JC      	| Japan Credit Bureau		|
|  TO      	| Maestro			|
|  S       	| Switch			|
|  EC      	| Electronic Cash		|
|  EU      	| EuroCard			|
|  TP      	| universal air travel card	|
|  OP      	| optima			|
|  ER      	| Air Canada/RnRoute		|
|  XS      	| access			|
|  O       	| others			|


<div class="anchor-offset" id="currency-codes"></div>

### Currency codes


Our system uses a standard ISO - 3 for all suppliers.

<div class="anchor-offset" id="markets"></div>


### Markets


Most suppliers use a standard ISO - 3166_1_alfa_2, but it depends on each individual supplier.


<div class="anchor-offset" id="nationality"></div>

### Nationality


We use a standard ISO - 3166_1_alfa_2.


<div class="anchor-offset" id="payment-types"></div>

### Payment Types


| **Codes**	| **Description**			|
| ------------- | ----------------------------- |
|  MerchantPay      	| The payment is managed by the supplier.				|
|  LaterPay      	| The payment is managed by the hotel. The customer will use a credit-card as a guarantee for the hotel and the payment will be completed at check in.		|
|  CardBookingPay      	| The payment is managed by the supplier. The payment is effectuated at the time of booking.			|
|  CardChekInPay      	| The payment is managed by the supplier. The payment is effectuated at check in in the hotel.			|
|  PayX      	| The payment is managed by TravelgateX's payment system.			|