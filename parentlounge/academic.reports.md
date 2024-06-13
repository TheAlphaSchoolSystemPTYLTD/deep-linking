**academic.reports**
----
  Redirects to the Parent Lounge - Academic Reports page after a successful user login.

* **Version History:**

    TASS v59.07 - Method Added

* **Version:**

  	`1`

* **Permission Required:**

  	`Parent Lounge -> Student Details -> Academic Reports`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

*  **Optional Params:***

    `prod_menu [char]` - Y/N falg to show/hide the menu.
    
* **Sample Parameters:**

	```HTML
	"target":"academic.reports"
	"prod_menu":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"academic.reports","prod_menu":"Y"}
	```
