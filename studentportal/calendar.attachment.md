**calendar.attachment**
----
  Redirects to the target program for downloading the file attachment of the calendar event. Deeplink is returned from the various calendar APIs.

* **Version History:**

    TASS v51.2 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	Student Calendar Events

* **Method:**

  	`GET`
  
* **Params Required:**

   	`target [string]` - The target program to be redirected to.
	
   	`feedcode [string]` - The type of attachment (including `per`, `ssch`, `stour`, `spti`, `sport`, `pcare`).

* **Params Conditional:**
	
   	`event_id [string]` - The id of an event (Required for `per`, `ssch`, `stour`, `spti`, `sport`, `pcare`).

   	`event_type [string]` - School or Dynamic (Required for `ssch`).

   	`tour_num [string]` - Tour number (Required for `stour`).

   	`pti_num [string]` - PTI number (Required for `spti`).

   	`session_num [string]` - Session number (Required for `spti`).

   	`entity_code [string]` - Entity code (Student code) (Required for `spti`).

   	`appoint_time [string]` - Appointment time (Required for `spti`).

   	`act_code [string]` - Activity code (Required for `sport`).

   	`entity_code [string]` - Entity code (Student code, required for `sport`).

   	`season [string]` - Season (Required for `sport`).

   	`rnd_code [string]` - Round code (Required for `sport`).

   	`opp_code [string]` - Opposition code (Required for `sport`).

   	`lev_code [string]` - Level code (Required for `sport`).

   	`fix_date [string]` - Fixture date (Required for `sport`).

* **Sample Parameters:**

	```HTML
	"target":"calendar.attachment"
	"feedcode":"per"
	"event_id":"7444"
	```

* **Deep Link**

	```HTML
	http://domain.com/studentportal/index.cfm?go={"target":"calendar.attachment","feedcode":"per","event_id":"7775"}
	```
