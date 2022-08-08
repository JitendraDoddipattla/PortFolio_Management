By: POD-3

## MFPE: PORTFOLIO MANAGEMENT SYSTEM

### POD Members

|Name|Work|Employee Id
|---|---|---|
|JITHENDRA DODDIPATTLA (**Leader**)|Calculate Networth Microservice|2160228
|ELAKYA|Daily Mutualfund NAV Microservice And Authorization|2159062
|ROHITH |DailySharepriceApi And CustomerPortalApi|2160304




---

## **OBJECTIVE**

### A leading Financial Services Organization wants to strengthen its Middleware by exposing the core logic related to Portfolio Management as Microservices. This middle ware Microservices will be hosted on Cloud so that all the up/downstream applications can get an access to this for performing business transactions.

### There will also be a customer Portal to be developed part of this scope that consumes these Microservices to view their portfolio information and sell their assets.

### User needs to login to the portal and provide their details i.e(login id and password).
### The application will provide the Net Assets and Networth associated to that particular portfolio.
### The user can be able to sell his/her assets.

---

## **MICRO SERVICES FUNCTIONALITY**

DailySharepriceApi Microservice:
- Daily Share Price Module is a Middleware Microservice which gets daily share price of a stock


Daily Mutual Fund NAV Microservice:
- Daily Mutual Fund NAV Module is a Middleware Microservice which gets the Mutual Fund NAV .

Calculate Net worth Microservice:
- Calculate Net worth Module is a Middleware Microservice that performs the following operations:
    · Calculate the current value of share holdings and mutual fund holdings and find out the total current value or net-worth 
    · Sell Assets and determine the final net-worth

Customer Portal Microservice:
-An Web Portal that allows a customer to Login and allows to do following operations: 
   · Login 
   · View the portfolio holdings & networth 
   · Sell assets

Authentication Microservice:
- It generates the JWT TOKEN for user authentication purpose.

---


---

# EndPoints: 

1. Authorization Microservice: 
[Authorization Microservice](http://localhost:44366/swagger/index.html)

2. DailySharepriceApi Microservice: 
[DailySharepriceApi Microservice](http://localhost:58451/swagger/index.html)

3. Daily Mutual Fund NAV Microservice:
[Daily Mutual Fund NAV Microservice](http://localhost:55953/swagger/index.html)

4. Calculate Net worth Microservice:
[Calculate Net worth Microservice](http://localhost:44375/swagger/index.html)

5. Customer Portal Microservice:
[Customer Portal Microservice](http://localhost:44327/swagger/index.html)
---

```

```




