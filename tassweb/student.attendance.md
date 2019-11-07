**student.attendance**
----
  Redirects to the program Attendance > Student Information > Student Attendance after a successful user login.

  * **Version History:**

     TASS v51 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Attendance > Student Attendance`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `studcode [string]` - The Student Code.

	   `keynum [string]` - The Key Num.
    
* **Sample Parameters:**

	```HTML
	"target":"student.attendance"
	"studcode":"100"
	"keynum":"00001"
	```

* **Deep Link**

	```HTML
	http://domain.com/tassweb/login.cfm?go={"target":"student.attendance","studcode":"00001","keynum":"100"}
	```
