**pastStudent.profile**
----
  Redirects to the target program Past Students > Student Information > Past Students > Student Profile after a successful user login.

* **Version History:**

    TASS v51 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`PastStudent Records Setup`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `studcode [string]` - The Student Code.
    
* **Sample Parameters:**

	```HTML
	"target":"paststudent.profile"
	"studcode":"00016421908"
	```

* **Deep Link**

	```HTML
	http://domain.com/tassweb/login.cfm?go={"target":"paststudent.profile","studcode":"00016421908","prod_menu":"Y"}
	```
