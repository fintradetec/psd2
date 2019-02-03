# Financial-grade API (FAPI)

The aim of FAPI Standard, developed by the FPAI working group (headed by Nat Sakamura, CEO, OpenID Foundation) is to provide JSON data schemas, security, and privacy recommendations and protocols to:

### Enable applications
*  to utilize the data stored in the financial account,
*  to interact with the financial accounts

### Enable Users
* to control the security and 
* to manage privacy settings.

Both commercial and investment banking account as well as insurance, and credit card accounts are included. 

The comprehensive list of documents and specification is [here](https://openid.net/wg/fapi/)

### Differences in Customer Journey Approach

It is essential to understand that this aspect, not handled by pure (minimal) PSD2 standards is the place of overlap between activities of 
the two global financial API standards, with their distinct and individual views on the Customer Journey:

* Open Bank Project is "Bank Product Customer Journey" and  
* OpenID FAPI, is "Bank User-Security Customer Journey oriented.

## Steps taken in the implementation

The steps taken in the development of the service context can read in CRUD (Create, Read, Update, and Delete) order, and make it easier to understand the individual meaning:

* Financial-grade API — Part 1: Read Only API Security Profile (Implementer’s Draft).
* Financial-grade API — Part 2: Read & Write API Security Profile (Implementer’s Draft).
* Financial-grade API — JWT Secured Authorization Response Mode for OAuth 2.0 (JARM) (Working Draft).
* Financial-grade API — CIBA Profile (Working Draft).

It also should be pointed out, that FAPI context API's include specific elements related to 
* insurance activities, and 
* account creation services. 

### Read only APIs for

The group proposes the following "read-only" Specification deliverables:

* Commercial Bank Accounts,
* Investment Bank (brokerage) Accounts,
* Life Insurance Accounts,
* Casualty Insurance Accounts,
* Credit Card Accounts.

### Write Access API including account creation but excluding web payment for

The group proposes the following "write & update" Specification deliverables:

* Commercial Bank Accounts,
* Investment Bank (brokerage) Accounts,
* Life Insurance Accounts,
* Casualty Insurance Accounts,
* Credit Card Accounts.

References/Sources: https://openid.net/wg/fapi/
