**attendance.addnotification**
----
  Redirects to the target program Student Details > Attendance > Add Absence Notification modal after a successful user login.
  "Attendance Settup" > "Allow parental acknowledgement of absences using Parent Lounge" must be enabled to access the Add Absence Notification modal.

* **Version History:**

    TASS v50.4 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Attendance`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `studcode [string]` - The Student Code.
    
* **Sample Parameters:**

	```HTML
	"target":"attendance.addnotification"
	"studcode":"0009080"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"attendance.addnotification","studcode":"0009080","prod_menu":"Y"}
	```