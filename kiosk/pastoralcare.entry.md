**pastoralcare.entry**
----
  Redirects to the target program Kiosk > PC Entries > Pastoral Care Entry after a successful user login.

* **Version History:**

 	TASS v51 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Kiosk > PC Entries > Pastoral Care Entry`

* **Method:**

  	`GET`
  
*  **Params Required:**

   	`target [string]` - The target program to be redirected to.
	
   	`studcode [string]` - Student code.
	
   	`seq_num [string]` - The sequence of the approval process (Used for Approve mode).
    
* **Sample Parameters:**

	```HTML
	"target":"pastoralcare.entry"
	"studcode":"0009130"
	"seq_num":"122"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"pastoralcare.entry","studcode":"0009130","seq_num":"122"}
	```
