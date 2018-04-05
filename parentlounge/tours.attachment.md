**tours.attachment**
----
  Redirects to the target program for downloading the file attachment of the tour after a successful user login.

* **Version:**

  	`2`

* **Permission Required:**

  	`Tours and Excursions`

* **Method:**

  	`GET`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `studcode [string]` - The Student Code.

	   `tour_num [string]` - The Tour Number.

* **Sample Parameters:**

	```HTML
	"target":"tours.attachment"
	"studcode":"0009130"
	"tour_num":"320"
	```

* **Deep Link**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"tours.attachment","studcode":"0009130","tour_num":"320","prod_menu":"N"}
	```