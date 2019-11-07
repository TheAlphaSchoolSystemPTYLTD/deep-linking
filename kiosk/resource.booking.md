**resource.booking**
----
  Redirects to the target program Kiosk > Resource Booking System after a successful user login.

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
	"booking_id":"123"
	```

* **Deep Link**

	```HTML
	http://domain.com/kiosk/login.cfm?go={"target":"resource.booking","booking_id":"123","prod_menu":"Y"}
	```
