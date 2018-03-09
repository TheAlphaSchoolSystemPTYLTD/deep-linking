**student.profile**
----
  Redirects to the target program Student Records > Student Information > Students > Student Profile after a successful user login.

* **Version:**

  	`2`

* **Permission Required:**

  	`Student Records Setup`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `studcode [string]` - The Student Code.
    
* **Sample Parameters:**

	```HTML
	"target":"student.profile"
	"studcode":"0009130"
	```

* **Deep Link**

	```HTML
	http://domain.com/tassweb/login.cfm?go={"target":"student.profile","studcode":"0009130","prod_menu":"Y"}
	```