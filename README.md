# interview-setup
This repository provides bootstrap project.

`backend` folder includes the server bootstrapper that needs implementation as well as backend question

`frontend` folder simply includes a frontend react app that needs implementation

## Interview Questions

### Write a nodejs express endpoint to fetch exchange rates by given base currency.

You should use: https://exchangerate.host/

We want you to implement an endpoint that will take "base" currency as an input and return currency rates by using
https://api.exchangerate.host/latest

In other words, we want you to implement exchange rates API:

https://api.exchangerate.host/latest?base=USD

by using its

https://api.exchangerate.host/latest

It should work on your localhost 4000 port.



### Create a frontend application which has the following:

  - A single dropdown menu which has static base currencies: EUR, USD, GBP
  - When selected fetch information regarding the selected base currency and put them on a currency table as:
  
Currency | Exchange Rate 
--- | --- 
EUR/CAD | ... 
EUR/USD | ... 
EUR/GBP | ... 

### How should the tests would be structured for such an application?
