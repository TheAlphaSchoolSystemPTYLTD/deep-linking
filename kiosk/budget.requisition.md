**budget.requisition**
----
  Redirects to the target program Kiosk > Requisitions after a successful user login.

* **Version History:**

 	TASS v51 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Kiosk > Requisitions`

* **Method:**

  	`GET`
  
*  **Params Required:**

   	`target [string]` - The target program to be redirected to.
	
   	`action [string]` - Action of this request on requisition.
	
   	`req_num [string]` - ID number of this requisition.
    
* **Sample Parameters:**

	```HTML
	"target":"budget.requisition"
	"action":"edit"
	"req_num":"123"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"budget.requisition","action":"action","req_num":"123"}
	```
