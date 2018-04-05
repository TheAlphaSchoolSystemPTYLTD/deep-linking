# Deep Linking

**Examples**

  Kiosk 
  * Student Profile
  * Teacher Rollcall
  
  Parent Lounge
  * Curricular Activities
  * School Fees
  * Tours Attachment
  * Tours Excursions
  
  TASS.web
  * Purchasing - Purchase Orders
  * Student Profile

**What is a Deep Link?**

A Deep Link is a URL parameter that is provided to the login screen to automatically redirect the user to the target page on a successful login.

If the user has a valid active session, they will be redirected to the target page without requiring re-autnntication.


**Licence Requirements**

Use of Deep Linking requires a valid TASS licence that includes API02 (Deep Link.) 


**Notes for Generating Deep Links**

It must be a valid JSON packet.

Both the name and value in the JSON parameter pair should be encapsulated in double quotes.


**Errors**

Any error encountered during the Deep Link redirect attempt will send the user to the Product Home screen. A corresponding entry with error details will be found the TASS.web exception log.

