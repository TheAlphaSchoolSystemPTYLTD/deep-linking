**payrollhr.mystaffleaveapplications**
----
  Redirects to the program Payroll/HR > My Staff Leave/Other Applications Modal after a successful user login.  This link is generated and sent in an email to a Leave Application Approver.

  * **Version History:**

     TASS v50.4 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Payroll/HR > My Staff Leave / Other Applications`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `leaveappnum [integer]` - The Leave Application Number.

	   `mystaffmode [string]` - The access type of application mode of the leave application ("Y" for My Staff mode).

	   `mode [string]` - The mode of which the modal window will load (generally "approve" for this link).

	   `seqnum [string]` - The sequence of the approval process (Used for Approve mode).
    
* **Sample Parameters:**

	```HTML
	"target":"leave.application"
	"leaveappnum":"44"
	"mystaffmode":"Y"
	"mode":"approve"
	"seqnum":"2"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"leave.application","leaveappnum":"44","mystaffmode":"Y","mode":"approve","seqnum":"2"}
	```
