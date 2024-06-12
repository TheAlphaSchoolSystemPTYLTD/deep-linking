**parent.pti**
----
  Redirects to the Parent Lounge Parent Teacher Interview page that matches the pti_num after a successful user login.

* **Version History:**

    	`TASS v59.07 - Method Added`

* **Version:**

  	`1`

* **Permission Required:**

  	`Parent Lounge`

* **Method:**

  	`GET`
  
*  **Params Required:**

	  `target [string]` - The target program to be redirected to.
	  `pti_num [integer]` - The pti code of the interview being requested.

*  **Optional Params:***

    `prod_menu [char]` - Y/N flag to show/hide the menu.
    
* **Sample Parameters:**

	```HTML
	"target":"parent.pti"
	"pti_num": 51
	"prod_menu":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"parent.pti","pti_num":51,"prod_menu":"N"}
	```
