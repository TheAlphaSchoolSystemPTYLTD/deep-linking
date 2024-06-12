**email.class.teachers**
----
  Redirects to the Parent Lounge > Student Details > Email Class Teachers page after a successful user login.

* **Version History:**

   	 `TASS v59.07 - Method Added`

* **Version:**

  	`1`

* **Permission Required:**

  	`Parent Lounge > Student Details > Email Class Teachers`

* **Method:**

  	`GET`
  
*  **Params Required:**

	  `target [string]` - The target program to be redirected to.

*  **Optional Params:***

    `prod_menu [char]` - Y/N flag to show/hide the menu.
    
* **Sample Parameters:**

	```HTML
	"target":"email.class.teachers"
	"prod_menu":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"email.class.teachers","prod_menu":"N"}
	```
