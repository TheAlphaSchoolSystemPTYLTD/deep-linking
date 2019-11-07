**budget.committeddetail**
----
  Redirects to the target program Kiosk > Budget Information after a successful user login.

* **Version History:**

 	TASS v51 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Kiosk > Budget Information`

* **Method:**

  	`GET`
  
*  **Params Required:**

   	`target [string]` - The target program to be redirected to.
	
   	`acct_code [string]` - Account code.
    
* **Sample Parameters:**

	```HTML
	"target":"budget.committeddetail"
	"action":"edit"
	"req_num":"01-1300-00-00"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"budget.committeddetail","acct_code":"01-1300-00-00"}
	```
