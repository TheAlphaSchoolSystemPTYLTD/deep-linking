**calendar.attachment**
----
  Redirects to the target program for downloading the file attachment of the calendar event.

* **Version:**

  	`2`

* **Permission Required:**

  	

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `event_id [string]` - The calendar or daily notices event id.

* **Sample Parameters:**

	```HTML
	"target":"calendar.attachment"
	"event_id":"7444"
	```

* **Deep Link**

	```HTML
	http://domain.com/publiccalendar/index.cfm?go={"target":"calendar.attachment","event_id":"7775","prod_menu":"N"}
	```