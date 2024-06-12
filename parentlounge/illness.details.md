**illness.details**
----
  Redirects to the Parent Lounge - Illness Details page after a successful user login.

* **Version History:**

    TASS v59.07 - Method Added

* **Version:**

  	`1`

* **Permission Required:**

  	`Parent Lounge -> Student Details -> Illness Details`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

*  **Optional Params:***

    `prod_menu [char]` - Y/N falg to show/hide the menu.
    
* **Sample Parameters:**

	```HTML
	"target":"illness.details"
	"prod_menu":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"illness.details","prod_menu":"Y"}
	```
