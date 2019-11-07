**budget.reqauthorise**
----
  Redirects to the target program Kiosk > Requisitions > Awaiting your Approval after a successful user login.

* **Version:**

  	`2`

* **Permission Required:**

  	`Kiosk > Requisitions > Awaiting your Approval`

* **Method:**

  	`GET`
  
*  **Params Required:**

   	`target [string]` - The target program to be redirected to.
	
   	`action [string]` - Action of this request on requisition.
    
* **Sample Parameters:**

	```HTML
	"target":"budget.reqauthorise"
	"action":"action"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"budget.reqauthorise","action":"action","prod_menu":"Y"}
	```
