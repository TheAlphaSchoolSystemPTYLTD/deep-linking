**resource.booking**
----
  Redirects to the target program Kiosk > Resource Booking System after a successful user login.

* **Version History:**

 	TASS v51 - Method Added

* **Version:**

  	`2`

* **Permission Required:**

  	`Kiosk > Resource Booking System`

* **Method:**

  	`GET`
  
*  **Params Required:**

   	`target [string]` - The target program to be redirected to.
	
   	`booking_id [string]` - The ID of the booking.
    
* **Sample Parameters:**

	```HTML
	"target":"resource.booking"
	"booking_id":"5FC48833-98E2-92D3-2E0D0E4EBF430901"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"resource.booking","booking_id":"5FC48833-98E2-92D3-2E0D0E4EBF430901"}
	```
