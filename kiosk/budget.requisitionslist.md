**budget.requisitionslist**
----
  Redirects to the target program Kiosk > Teachers Substitutions after a successful user login.

* **Version History:**

 	TASS v51 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Kiosk > Teachers Substitutions`

* **Method:**

  	`GET`
  
*  **Params Required:**

   	`target [string]` - The target program to be redirected to.
	
   	`status_flg [string]` - Status flag of requisition. ("C":"Approved", "O":"Unapproved", "R":"Rejected", "X":"Cancelled")
    
* **Sample Parameters:**

	```HTML
	"target":"budget.requisitionslist"
	"status_flg":"C"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"budget.requisitionslist","status_flg":"C"}
	```
