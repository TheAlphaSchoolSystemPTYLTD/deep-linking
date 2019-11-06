**Donor.Profile**
----
  Redirects to the target program Fundraising > Donor Information > Donors > Donor Profile after a successful user login.

* **Version History:**

    TASS v51 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Donor Records Setup`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `donornum [string]` - The Donor Code.
    
* **Sample Parameters:**

	```HTML
	"target":"student.profile"
	"donornum":"1133"
	```

* **Deep Link**

	```HTML
	http://domain.com/tassweb/login.cfm?go={"target":"donor.profile","donornum":"1133","prod_menu":"Y"}
	```
