**purchasing.purchaseorder**
----
  Redirects to the target program Finance > Purchasing > Orders > Purchase Orders > Edit after a successful user login.

* **Version History:**

    TASS v48.0 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Purchasing > Purchase Orders`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `ponum [string]` - The PO Numer.

*  **Params Optional:**

	   `companycode [string]` - The Company Code.
    
* **Sample Parameters:**

	```HTML
	"target":"purchasing.purchaseorder"
	"ponum":"372"
	```

* **Deep Link**

	```HTML
	http://domain.com/tassweb/login.cfm?go={"target":"purchasing.purchaseorder","ponum":"372","prod_menu":"Y"}
	```