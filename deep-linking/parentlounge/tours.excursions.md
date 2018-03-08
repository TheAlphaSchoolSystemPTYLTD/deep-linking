**tours.excursions**
----
  Redirects to the target program Make a Payment > Tours and Excursions after a successful user login.

* **Version:**

  	`2`

* **Permission Required:**

  	`Tours and Excursions`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `studcode [string]` - The Student Code.

	   `tournum [string]` - The Tour Number.

* **Sample Parameters:**

	```HTML
	"target":"tours.tour"
	"studcode":"0009130"
	"tour_num":"320"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"tours.tour","studcode":"0009130","tour_num":"320","prod_menu":"Y"}
	```