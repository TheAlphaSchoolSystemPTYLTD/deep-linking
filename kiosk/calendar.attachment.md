**calendar.attachment**
----
  Redirects to the target program for downloading the file attachment of the calendar event.

* **Version:**

  	`2`

* **Permission Required:**



* **Method:**

  	`GET`
  
* **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `feedcode [string]` - Same feedcode used in teacher/student calendar UI.

* **Sample Parameters:**

	```HTML
	"target":"calendar.attachment"
	"feedcode":"ttour"
	"tour_num":"125"
	```

* **Deep Link**

	```HTML
	http://domain.com/publiccalendar/index.cfm?go={"target":"calendar.attachment","feedcode":"ttour","tour_num":"125"}
	```
