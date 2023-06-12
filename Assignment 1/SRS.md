# Software Requirements Specification

## **1. Introduction**
### 1.1 Purpose
The main purpose of the online shopping system is,
- customers can give an order easily anytime who wants the particular order.
- orders can be delivered in most possible early time.
- The system stores some customer's shopping information because developing marketing advertisements,Improving marketing strategy, Product content management.

### 1.2 Document Conventions
The following documentation conventions are followed in preparing this SRS:

  SRS - Software Requirement Specification
  
  
### 1.3 Intended Audience and Reading Suggestions
This document is created for,
- Store IT Personnel,
- Customer,
- Store Personnel,
- Software Developement Team

### 1.4 Product Scope
- Sellers can increase and widen their reach to way beyond their cities – they can get customers from literally anywhere in the world, provided they are willing to ship.
- Even small businesses can increase their sales and grow by selling online.
- As online stores can be operated with minimal staff, there is huge savings in salaries; sellers can also save on overheads like electricity and other utility bills.
- Online storefronts are open 24/7 to serve customers – no more worrying about missing out because of holidays, strikes, or even lockdowns.
- Sellers can deal in a wide range of products.
- They can analyse customer buying patterns and preferences and offer tailor made offers, discounts, and services.
- Business can be easily scaled.

### 1.5 Overview
This system provides an easy solution for customers to buy the product without going to the shop and also to shop owner to sale the product.
This proposed system can be used by any naive users and it does not require any educational level, experience or technical expertise in computer field but it will be of good use if user has the good knowledge of how to operate a computer.

## 2.Overall Description
### 2.1 Product Perspective
Amazon Online Shopping application  has been serving as Aisa's one of the largest and most extensive e-commerce site since 1994. This software system can be used through mobile application and website. This software system is not a subcomponent of any system.It started in India in june 2013.
### 2.2 Product Functions
This software system is expected to offer the following services:
1. `Store IT Personnel`
    * They analyze the product sales
    * They have to add new products in system through user interface
    * They can see instantly orders and analyze them
    * Follow closely for any possible modifications needed
2.  `Store Personnel`
    * Can see instantly orders
    * Prepare order to supplier
    * Products fall from stocks
3.  `Customers`
    * Can see all products in Online Shopping Platform.
    * Have to register for shopping. 
    * Have to give some personal information (Address, Phone Number, TC Number, Mail Address)  during registration
4.  `Supplier`
    * Send order and prepare order
### 2.3 User Classes and Characteristics
1. `Store IT personnel:`
It adds new products to the database via user interface and makes necessary updates. It keeps track of the product stocks in the store where it is responsibleand the changes which may occur and occur.
2. `Customer:`
Customers can see all products sold at online stores. May be a member to shop. Separate  can buy the products it adds. They share certain personal information.
3. `Store Personnel:`
Can see instantly orders, prepare order to supplier and products fall from stock.

4. `Supplier:`
Brings the product to the application

### 2.4 Operating Environment
This software system is  Works in -Android OS ,Windows and  Linux  version. And uses technologies like "cookies", "pixel tags" and "web beacons" . It is Developed in Microsoft Visual Studio, ASP.NET with C#, JSON, CSS, Java script, jQuery,HTML.
### 2.5 Design and Implementation Constraints
The constraints are as follows-
* This software system will be used by such a mass range of people so the software system must deal with this weight.
* It should store all users' data without any  problem in associating this data.
* Application have to ensure the safety of the data.
* We could not get any definitive information about the database

### 2.6 User Documentation
This software system is delivered with an Instruction manual for the stakeholders to use.Analysis reports, designs, well-maintained software, test cases and test suites were also delivered at the end of the project.
### 2.7 Assumptions and Dependencies
After this software system maintenance is done, the Store IT Personal addition, deletion and update process will be done more quickly and smoothly.Store IT Personal will not encounter a synchronization problem on the tablet screen.They will make requests of other customers faster and more comfortable experience.Achieving these desired assumptions depends on the success of successful engineers,database administrators and front-end developers.

## 3. System Requirements
### Functional Requirements:
This section provides requirements overview of the system. Various functional modules that can be implemented by the system such as, 

### **3.1 Description**

`Registration`
If the customer wants to buy the product the he/she must be registered, unresgistered user cannot go to the shopping cart.

`Login`
Customer logins to the system by entering valid user id and password for the shopping.

`Changes to Cart`
Changes to cart means the customer after login or registration can make order or cancel order of the product from the shopping cart.

`Payment`
In this system we are dealing the various modes of payment that is by Cash, Credit Card, Debit Card etc.

`Logout`
After ordering or surfing for the product, customer has to logout.

`Report Generation`
After ordering for the product,the system will sent one copy of the bill to the customer’s Email-address and another one for the system data base.


## 4.External Interface Requirement:
### 4.1 Hardware Interface:
Hardware requirements for insurance on internet will be	same for both parties which are as follows:
* `Processor:`Dual Core RAM:2 GB
* `Hard Disk:`320 GB NIC:For each party
### 4.2 Software Interface
* `Operating System:`Windows7 Ultimate which supports networking.
* JAVA development toolkit
### 4.3 Communication Interfaces
The two parties should be connected by LAN or WAN for the communication purpose.

## 5.Other Non-Functional Requirements
### 5.1 Performance Requirements
This software should be able to handle the following tasks:We have to develop the performance and fix the bugs because systems performance is not enough.Database could need to be normalization.
In order to maintain an acceptable speed at maximum number of uploads allowed from a particular customer as any number of users can access to the system at any time.
Also, the connections to the servers will be based on the attributes of the user like his location and server will be working 24X7 times.

### 5.2 Safety RequirementsThis
This software will ease the process of customers order. It could try to perfect service. All important details should be maintained in hard copy as well.
Certificate Authorities is significant issue. All Certificates must be current for safety and reliability

### 5.3 Security Requirements
Systems firewalls, IPS's and storages can be controlled and increased. System's logs must be saved 24*7. Confidentiality must be provided from attackers.Customers and Staff private and important informations must be stored encrypted types (hash + salt) in Database.Systems and stakeholders software's must be used current version. Systems should be used multiple factor authentication.This software will-Authenticate each user, who logs in,When the user performs any action, authorize him/her to perform the actions allowed for the user and displays an error message if found to be unauthorized
### 5.4 Software Quality
* AttributesSystem should be user friendly.
* System should be has used easy interfaces.
* System should be understandable.
* System should be agile software.
* System should be increased process capabilities.
* System should be protected stability.

## 6.Other Requirements

`Appendix 1: Username and Password`
* Username must be unique for all users.
* Password must be unique for all users.
* Your password must be at least 6, at most 20 characters, at least 1 letter and at least 1 digit.

`Appendix 2: Information requested while being a member`

* Enter e-mail address and create a new password.(Your password must be at least 6, at most 20 characters, at least 1 letter and at least 1 digit.)
* Name, Surname, Date of birth, Gender, T.C. Identification number, Money Card Type



