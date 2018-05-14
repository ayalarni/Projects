# Online Real Estate Office
Software Requirements Specification
 
## NIA Realty Group, Inc.

## Prepared by Nia Rosa

##4/23/2018

Table of Contents

1. Introduction
   1.1 Purpose
   1.2 Project Scope
   1.3 References

2. General Description
   
3. System Features
  3.1 New User Registration    
    3.1.1 Description 
    3.1.2 Response Sequences
    3.1.3 Detailed Categorizations
    3.1.4 Provide Search facility
  3.2 User Authentication/Maintain User profile
    3.2.1 Description
    3.2.2 Provide personalized profile
    3.2.3 Response Sequences 
    3.2.4 Provide Customer Support
    3.2.5 E-mail confirmation
    3.2.6 Detailed invoice for Client
    3.2.7 Provide viewing cart facility
  3.3 Category Selection
  3.4 Agreement(s) Selection
  3.5 Agreement(s) Execution
  3.6 Real Estate Agent Assignment
  3.7 Listing Showcase
  3.8 Buyer Home Search
  3.9 Allow multiple payment methods
  3.10 Allow online change or cancellation of selection
  3.11 Allow Online Agent(s) reviews and ratings
  3.12 Provide detailed sitemap
  3.13 Usability
    3.13.1 Graphical User Interface (GUI)
    3.13.2 Accessibility
  3.14 Reliability & Availability
    3.14.1 Back-end Internal Computers
    3.14.2 Internet Service Provider
    3.14.3 Performance
  3.15 Security
    3.15.1 Data Transfer
    3.15.2 Data Storage
  3.16 Supportability
    3.16.1 Configuration Management Tool
  3.17 Design Constraints
    3.17.1 Standard Development Tools
    3.17.2 Web Based Product
  3.18 On-line User Documentation and Help System Requirements
  3.19 Interfaces
    3.19.1 User Interfaces
    3.19.2 Hardware Interfaces
    3.19.3 Software Interfaces
    3.19.4 Communications Interfaces
  3.20 Licensing Requirements
  3.21 Legal, Copyright, and Other Notices
  3.22 Applicable Standards

4. Supporting Information

      
Revision History


1. Introduction

  1.1 Purpose
  
This document aims to gather, analyze, and provide a high-level view of an online Real Estate Office for NIA Realty Group, Inc. software system.  It specifies the detail requirements of the software system, its parameters and goals. This document describes the project's target audience and its user interface, hardware and software requirements. It further defines how our client and the real estate office team see the categories and its functionality. Once completed, the required systems will depict a Search tab to search for Properties and Special Searches.  
  
  1.2 Project Scope

The scope defines required features for the Real Estate Office for NIA Realty Group, Inc. to function properly. It focuses on the necessary applications allowing clients to interact with the system for a real online real estate experience.  This SRS aimed at the design of the software specific requirements.  The "Real Estate Office for NIA Realty Group, Inc." is an internet application designed to help clients find a house to buy or rent, and sellers to list their home for sale in the current market.  

The software needs Internet connection to search and display results.  The application also has the capability of representing both summary and detailed information about the properties.
  
  1.3 References
IEEE Software Engineering Standards Committee, "IEEE Std 830-1998, IEEE Recommended Practice for Software Requirements Specifications", October 20, 1998.	

2. General Description

What follows provide a general description, including characteristics of the Modules on this project, the product's hardware, and the functional and data requirements of the categories. (Section 3) gives the functional requirements, data requirements, constraints and assumptions made while designing the Online . Section 3 also discusses the external interface requirements and gives detailed description of functional requirements. Section 4 is for supporting information.

3. System Features

The functional requirements of the online Real Estate Office are organized by functional categories.  These categories are: Search for Property Search and Special Searches.  Under Property Search: Single Family Detached, Single Family Attached, Acreage & Farms, Commercial, Land Lot, Multi-Family, Rental - Residential, Rental - Commercial, and All Property TYpes.  Under the Special searches: Status Change, Hotsheet, Just Sold, Just Listed, Just Expired, Foreclosures, and Open Houses. 

  3.1 New User Registration
    
    3.1.1 Description     
This feature shall allow a new User to register on the online Real Estate Office website.  There is no cost for User to register on the website.
    
    3.1.2 Response Sequences    
The User shall choose his/her unique Username and Password.  The User shall select up to 3 unique Security Questions/Answers to further authenticate its registration. There is no risk unless the User chooses a common password lacking proper security protocols.

    3.1.3 Detailed Categorizations
The system shall display detailed categorization to the User.
The system shall display detailed information of the selected categories.
The system shall provide browsing/search options to see category details.

    3.1.4 Provide Search facility
The system shall enable User to enter the search text on the screen.
The system shall enable user to select multiple options on the screen to search.
The system shall display all the matching categories based on the search.
The system shall display up to 30 matching results on the current screen.
The system shall enable User to navigate between the search results.
The system shall notify the User when no matching category is found on a specific search.
  
  3.2 User Authentication/Maintain User profile
  
    3.2.1 Description
    
Once the User has registered, users will select their  specific roles, i.e. renter, buyer, seller, property management, or all.  
The system shall allow User to create profile and set his credential.
The system shall authenticate user credentials to view the profile.
The system shall allow User to update the profile information.   
The system shall allow User to add, upload, field in registration form so that Users can upload documents, images and more.

    3.2.2 Provide personalized profile
The system shall display both the active and completed order history in the customer profile.
The system shall allow User to select preferences from the search history.
The system shall display the detailed information about the selected search.
The system shall display the most frequently searched items by the User in the profile.
The system shall allow user to register for newsletters and surveys in the profile.
    
    3.2.3 Response Sequences    
Content Restriction – allows website manager to restrict full or partial content from page, post to only logged in Users or logged in Users with specific roles.

    3.2.4 Provide Customer Support
The system shall provide online Help, FAQs customer support, and sitemap options for customer support.
The system shall allow User to select their preferred support type.
The system shall allow User to enter category information for the support.
The system shall display the customer support contact numbers on the screen.
The system shall allow User to enter the contact number for support personnel to call.
The system shall display the online Help upon request.
The system shall display the FAQs upon request.

    3.2.5 E-mail confirmation
The system shall maintain customer/User e-mail information as a required part of customer profile.
The system shall display cart/basket confirmation to the User through e-mail.

    3.2.6 Detailed invoice for Client
The system shall display detailed invoice for fees once confirmed.
The system shall optionally allow User to print the invoice.

    3.2.7 Provide viewing cart facility
The system shall provide viewing cart during online viewing.
The system shall allow User to add/remove categories in the viewing cart.
  
  3.3 Category Selection
User select Search, Search for Property Search and Special Searches.  Under Property Search: Single Family Detached, Single Family Attached, Acreage & Farms, Commercial, Land Lot, Multi-Family, Rental - Residential, Rental - Commercial, and All Property TYpes.  Under the Special searches: Status Change, Hotsheet, Just Sold, Just Listed, Just Expired, Foreclosures, and Open Houses. User select category, i.e. Listing, Selling, Renting (Renter or Landlord), and/or Property Management.
  
  3.4 Agreement(s) Selections
User shall select agreement, provide data and Agent fills out Exclusive Selling Brokerage Agreement.
User shall select agreement, provide data and Agent fills out Exclusive Listing Brokerage Agreement.
User shall select agreement, provide data and Agent fills out Exclusive Leasing Brokerage Agreement. 
  
  3.5 Agreement(s) Execution
The assigned Agent shall review, accept, bind selected agreement(s) and return it to client via e-mail.
  
  3.6 Real Estate Agent Assignment
The Real Estate Office Broker shall assign real estate agent(s) to client(s)/registered users.
  
  3.7 Listing Showcase
Real estate agent shall showcase listing(s) on the online Real Estate Office website.
  
  3.8 Buyer Home Search
Buyer shall search website to select potential houses to view with Agent.

  3.9 Allow multiple payment methods
The system shall display available payment methods for payment of fees i.e. Retainer, Withdrawal fee, etc.
The system shall allow User to select the payment method for any fees.

  3.10 Allow online change or cancellation of selection
The system shall display the Categories that are eligible to change.
The system shall allow User to select the Category to be changed.
The system shall allow User to cancel the Category.
The system shall allow User to change payment method.
The system shall notify the User about any changes made to the selection.

  3.11 Allow Online Agent(s) reviews and ratings
The system shall display the reviews and ratings of each agent, when selected.
The system shall enable the User to enter their reviews and ratings.

  3.12 Provide detailed sitemap
The system shall allow User to view detailed sitemap.
The system shall display schools rating for comparison among other school districts.

  3.13 Usability
    3.13.1 Graphical User Interface (GUI)
The system shall provide a uniform look and feel between all the web pages.
The system shall provide a digital image for each category in the Search catalog.
The system shall provide use of icons and toolbars.
   3.13.2 Accessibility
The system shall provide handicap access.
The system shall provide multi language support.

  3.14 Reliability & Availability
    3.14.1 Back-end Internal Computers
The system shall provide storage of all databases on redundant computers with automatic switchover.
The system shall provide for replication of databases to off-site storage locations.
The system shall provide RAID V Disk Stripping on all database storage disks.
    3.14.2 Internet Service Provider
The system shall provide a contractual agreement with an internet service provider for T3 access with 99.9999% availability.
The system shall provide a contractual agreement with an internet service provider who can provide 99.999% availability through their network facilities onto the internet.
    3.14.3 Performance
The Categories shall be based on web and has to be run from a web server.
The Search shall take initial load time depending on internet connection strength which also depends on the media from which the Search is run.
The performance shall depend upon hardware components of the client/customer.

  3.15 Security
    3.15.1 Data Transfer
The system shall use secure sockets in all transactions that include any confidential customer information.
The system shall automatically log out all customers after a period of inactivity.
The system shall confirm all transactions with the customer’s web browser.
The system shall not leave any cookies on the customer’s computer containing the user’s password.
The system shall not leave any cookies on the customer’s computer containing any of the user’s confidential information.
    3.15.2 Data Storage
The customer’s web browser shall never display a customer’s password. It shall always be echoed with special characters representing typed characters.
The customer’s web browser shall never display a customer’s credit card number after retrieving from the database. It shall always be shown with just the last 4 digits of the credit card number.
The system’s back-end servers shall never display a customer’s password. The customer’s password may be reset but never shown.
The system’s back-end servers shall only be accessible to authenticated administrators.
The system’s back-end databases shall be encrypted.

  3.16 Supportability
    3.16.1 Configuration Management Tool
The source code developed for this system shall be maintained in configuration management tool.

  3.17 Design Constraints
    3.17.1 Standard Development Tools
The system shall be built using a standard web page development tool that conforms to Microsoft’s GUI standards.
    3.17.2 Web Based Product
There are no memory requirements.
The computers must be equipped with web browsers such as Internet explorer, Moxilla, FireFox.
The Category must be stored in such a way that allows the client easy access to it.
Response time for loading the Category should take no longer than five minutes.
A general knowledge of basic computer skills is required to use the system.

  3.18 On-line User Documentation and Help System Requirements
As the product is E-Office, On-line help system becomes a critical component of the system which shall provide specific guidelines to a User for using the Real Estate Office for NIA Realty Group, Inc. system and within the system.
To implement online User help, link and search fields shall be provided.

  3.19 Interfaces
There are many types of interfaces as such supported by the Real Estate Office for NIA Realty Group, Inc. software system namely; User Interface, Software Interface and Hardware Interface.
The protocol used shall be HTTP.
The Port number used will be 80.
    3.19.1 User Interfaces
The user interface for the software shall be compatible to any browser such as Internet Explorer, Mozilla or Netscape Navigator by which User can access the system.
The User interface shall be implemented using any tool or software package like Java Applet, MS Front Page, EJB etc.
    3.19.2 Hardware Interfaces
Since the application must run over the internet, all the hardware shall require to connect internet will be hardware interface for the system. As for e.g. Modem, WAN – LAN, Ethernet Cross-Cable.
    3.19.3 Software Interfaces
1. The Real Estate Office for NIA Realty Group, Inc. system shall communicate with the Configurator to identify all the available components to configure the product.
2. The Real Estate Office for NIA Realty Group, Inc. shall communicate with the content manager to get the product specifications, offerings and promotions.
3. The Real Estate Office for NIA Realty Group, Inc. system shall communicate with billPay system to identify available payment methods , validate the payments and process payment.
4. The Real Estate Office for NIA Realty Group, Inc. system shall communicate with CRM system to provide support.
5. The Real Estate Office for NIA Realty Group, Inc. system shall communicate with Sales system for order management.
6. The Real Estate Office for NIA Realty Group, Inc. system shall communicate with external Tax system to calculate tax.
7. The Real Estate Office for NIA Realty Group, Inc. system shall communicate with export regulation system to validate export regulations.
8. The system shall be verisign like software which shall allow the users to complete a secured transaction. This usually shall be the third party software system which is widely used for internet transactions.
    3.19.4 Communications Interfaces
The system shall use the HTTP protocol for communication over the internet and for the intranet communication will be through TCP/IP protocol suite.

  3.20 Licensing Requirements
Georgia Real Estate Commission (GREC)

  3.21 Legal, Copyright, and Other Notices
Real Estate Office should display the disclaimers, copyright, word mark, trademark and product warranties of the NIA Realty Group, Inc.

  3.22 Applicable Standards
It shall be in compliance with the Real Estate industry standard.

4. Supporting Information
Please refer the following documents:
1. Vision document for Real Estate Office for NIA Realty Group, Inc.
2. Use case analysis.
3. Structural models.
4. Behavioral models.
5. Non-functional requirements model.
6. Traceability Matrix.
7. Project Plan


