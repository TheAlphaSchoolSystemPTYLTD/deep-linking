**payrollhr.mypayrollhr**
----
  Redirects to the program Payroll/HR > My Payroll/HR > Leave Applications Modal after a successful user login. This link is generated and sent in an email to a Leave Applicant.

  * **Version History:**

     TASS v50.4 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Payroll/HR > My Payroll/HR > Leave/Other Applications`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `leaveappnum [integer]` - The Leave Application Number.

	   `mystaffmode [string]` - The access type of application mode of the leave application ("N" for My Payroll/HR mode).

	   `mode [string]` - The mode of which the modal window will load.

	   `draft [string]` - Is the Leave Application loaded as a Draft?
    
* **Sample Parameters:**

	```HTML
	"target":"leave.application"
	"leaveappnum":"46"
	"mystaffmode":"N"
	"mode":"edit"
	"draft":"Y"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"leave.application","leaveappnum":"46","mystaffmode":"N","mode":"edit","draft":"Y"}
	```
