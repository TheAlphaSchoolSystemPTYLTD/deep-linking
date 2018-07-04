**teachers.view.substitution.detail**
----
  Redirects to the target program Teacher > Teacher Substitution after a successful user login.

* **Version:**

  	`1`

* **Permission Required:**

  	`Teacher > Teacher Substitutions`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `previousCriteria [string]` - The parameters in the format "#substitution-detail/<Leave Number>/<Period Code>/<Subject Code>/<Year Group>/<Class>".
    
* **Sample Parameters:**

	```HTML
	"target":"teachers.substitutions"
	"previousCriteria":"#substitution-detail/254/4/0076/10/A"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"teachers.substitutions","previousCriteria":"#URLEncodedFormat("##substitution-detail/#data.leave_num#/#data.prd_code#/#data.sub_code#/#data.year_grp#/#data.class#")#"}
	```