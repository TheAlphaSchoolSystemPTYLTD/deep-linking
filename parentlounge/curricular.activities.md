**curricular.activities**
----
  Redirects to the target program Student Details > Curricular Activities after a successful user login.

* **Version History:**

	`TASS v59.07 - Made studcode and activity_assign_id optional parameters.`

* **Version:**

  	`2`

* **Permission Required:**

  	`Curricular Activities`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.
   
*  **Optional Paramaters:**
  
	   `studcode [string]` - The Student Code.

	   `activity_assign_id [string]` - The UUID for this student and activity.
    
* **Sample Parameters:**

	```HTML
	"target":"curricular.activity"
	"studcode":"0009130"
	"activity_assign_id":"4522"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"curricular.activity","studcode":"0009130","activity_assign_id":"4522","prod_menu":"Y"}
	```
