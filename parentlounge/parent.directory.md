**parent.directory**
----
  Redirects to the Parent Lounge - Parent Directory page after a successful user login.

* **Version History:**

    TASS v59.07 - Method Added

* **Version:**

  	`1`

* **Permission Required:**

  	`Parent Lounge -> Parent Details`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

*  **Optional Params:***

    `prod_menu [char]` - Y/N falg to show/hide the menu.
    
* **Sample Parameters:**

	```HTML
	"target":"parent.directory"
	"prod_menu":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"parent.directory","prod_menu":"Y"}
	```
