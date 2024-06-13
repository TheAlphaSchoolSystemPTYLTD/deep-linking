**student.profile**
----
  Redirects to the target program Student Details > General Details after a successful user login.
  
**Version History:**

	`TASS v59.07 - Made studcode an optional parameter.`
 
* **Version:**

  	`2`

* **Permission Required:**

  	`General Details`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.
   
* **Optional Params:**
  
	   `studcode [string]` - The Student Code.
    
* **Sample Parameters:**

	```HTML
	"target":"student.profile"
	"studcode":"0009130"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"student.profile","studcode":"0009130","prod_menu":"Y"}
	```
