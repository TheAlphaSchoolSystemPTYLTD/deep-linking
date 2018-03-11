**teacher.rollcall**
----
  Redirects to the target program Teacher > Teacher Details > Timetable > Rollcall after a successful user login.

* **Version:**

  	`2`

* **Permission Required:**

  	`Teacher > Teacher Details > Rollcall`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `ttid [string]` - The Timetable ID.

	   `yeargroups [string]` - The Year Groups this rollcall class contains.

	   `classes [string]` - The Classes this rollcall class contains.

	   `tchcode [string]` - The Teacher Code for this rollcall class.

	   `subjectcode [string]` - The Subject Code for this rollcall class.

	   `date [string]` - The Date of the rollcall period (dd/mm/yyyy).

	   `periodcode [string]` - The Period Code for the rollcall period.

	   `daycode [string]` - The Day Code for the rollcall period.

* **Sample Parameters:**

	```HTML
	"target":"teacher.rollcall"
	"ttid":"82"
	"yeargroups":"11"
	"classes":"A"
	"tchcode":"AJ"
	"subjectcode":"0001"
	"date":"28/02/2018"
	"periodcode":"4"
	"daycode":"3"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"teacher.rollcall","ttid":"82","yeargroups":"11","classes":"A","tchcode":"AJ","subjectcode":"0001","date":"28/02/2018","periodcode":"4","daycode":"3","prod_menu":"Y"}
	```