**academic.results.and.comments**
----
  Redirects to the Parent Lounge - Academic Results and Comments page after a successful user login.

* **Version History:**

    TASS v59.07 - Method Added

* **Version:**

  	`1`

* **Permission Required:**

  	`Parent Lounge -> Student Details -> Academic Results and Comments`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

*  **Optional Params:***

    `prod_menu [char]` - Y/N flag to show/hide the menu.
    
* **Sample Parameters:**

	```HTML
	"target":"academic.results.and.comments"
	"prod_menu":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"academic.results.and.comments","prod_menu":"Y"}
	```
