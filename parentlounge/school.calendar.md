**parent.lounge.home.page**
----
  Redirects to the Parent Lounge - School Calendar page after a successful user login.

* **Version History:**

    TASS v59.07 - Method Added

* **Version:**

  	`1`

* **Permission Required:**

  	`Parent Lounge -> Calendar -> School Calendar`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

*  **Optional Params:***

    `prod_menu [char]` - Y/N flag to show/hide the menu.
    
* **Sample Parameters:**

	```HTML
	"target":"school.calendar"
	"prod_menu":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"school.calendar","prod_menu":"Y"}
	```
