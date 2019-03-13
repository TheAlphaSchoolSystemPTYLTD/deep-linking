**teacher.pti**
----
  Redirects to the program Teacher > Parent Teacher Interview (or Teacher > Parent Teacher Interview > Appointment Schedule Screen if PTI Status is not "Review") after a successful user login.

  * **Version History:**

     TASS v50 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Teacher > Parent Teacher Interviews`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `pti_num [string]` - The PTI Number.
    
* **Sample Parameters:**

	```HTML
	"target":"teacher.pti"
	"pti_num":"100"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"teacher.pti","pti_num":"100"}
	```
