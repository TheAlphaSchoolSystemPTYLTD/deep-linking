**calendar.attachment**
----
  Redirects to the target program for downloading the file attachment of the calendar event.

* **Version History:**

    TASS v51.X - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Parent Portal > Calendar Events`

* **Method:**

  	`GET`
  
* **Params Required:**

   	`target [string]` - The target program to be redirected to.
	
   	`event_id [string]` - The id of an event.

* **Sample Parameters:**

	```HTML
	"target":"calendar.attachment"
	"feedcode":"per"
	"event_id":"7444"
	```

* **Deep Link**

	```HTML
	http://domain.com/studentportal/index.cfm?go={"target":"calendar.attachment","event_id":"7444"}
	```
