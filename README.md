# Deep Linking

```
	NB: Deep Linking API does not form part of the general TASS API framework.
	As such, it does not require the Encrypted Tokenisation outlined in the API Introduction
```

**Examples**

  Kiosk 
  * Student Profile
  * Teacher Rollcall
  * Teacher Substitution
  
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

If the user has a valid active session, they will be redirected to the target page without requiring re-authentication.


**Notes for Generating Deep Links**

It must be a valid JSON packet.

Both the name and value in the JSON parameter pair should be encapsulated in double quotes.


**Disabling the Product Menu**

To assist in embedding the target program of a Deep Link inside another product, you have the option of disabling that products menu by supplying the below parameter

	"prod_menu":"N"


**Logging Out**

When generating a Deep Link without the TASS or Portal menu structure (`"prod_menu":"N"`), you will be responsible for providing a logout mechanism for your users.

A logout can be initiated by redirecting a user to the logout URL. E.g.: 

 * Parent Lounge: https://domain.com/parentlounge/index.cfm?do=parentportal.user.logout
 * Student Cafe: https://domain.com/studentcafe/index.cfm?do=studentportal.user.logout
 * TASS.web: https://domain.com/tassweb/logout.cfm
 * Kiosk: https://domain.com/kiosk/index.cfm?do=kiosk.user.logout

**Errors**

Any error encountered during the Deep Link redirect attempt will send the user to the Product Home screen. A corresponding entry with error details will be found in the TASS.web exception log.

