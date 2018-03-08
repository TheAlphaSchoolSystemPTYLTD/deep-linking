**school.fees**
----
  Redirects to the target program Make a Payment > School Fees Account after a successful user login.

* **Version:**

  	`2`

* **Permission Required:**

  	`School Fees Account`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.
    
* **Sample Parameters:**

	```HTML
	"target":"school.fees"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"school.fees","prod_menu":"Y"}
	```