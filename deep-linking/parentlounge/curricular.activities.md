**curricular.activities**
----
  Redirects to the target program Student Details > Curricular Activities after a successful user login.

* **Version:**

  	`1`

* **Permission Required:**

  	`Curricular Activities`

* **Method:**

  	`GET | POST`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

	   `studcode [string]` - The Student Code.

	   `activity_assign_id [string]` - The UUID for this student and activity.

* **Success Response:**

    ```HTML
    http://domain.com/parentlounge/login.cfm?sso_token=1EB9E96FECDDFB632EBBBADC8CC4B33D
    ```
    
* **Error Response:**

    ```javascript
    "response_code":"4"
    ```
    
* **Sample Parameters:**

	```HTML
	"target":"curricular.activity"
	"studcode":"0009130"
	"activity_assign_id":"4522"
	```

* **Deep Link without SSO**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"curricular.activity","studcode":"0009130","activity_assign_id":"4522","prod_menu":"Y"}
	```
  
* **Deep Link with SSO**

	```HTML
	<cfhttp url="domain.com/tassweb/external/sso_gateway.cfm?returnType=json" method="post" result="SSOResult" resolveurl="true">
		<cfhttpparam type="formfield" name="method" value="createSSOToken" />
		<cfhttpparam type="formfield" name="cmpy_code" value="10" />
		<cfhttpparam type="formfield" name="prod_code" value="PL" />
		<cfhttpparam type="formfield" name="app_code" value="PR" />
		<cfhttpparam type="formfield" name="sso_code" value="aclarke" />
		<cfhttpparam type="formfield" name="sso_token" value="" />
		<cfhttpparam type="formfield" name="token_key" value="12345" />
		<cfhttpparam type="formfield" name="prod_menu" value="Y" />
		<cfhttpparam type="formfield" name="deep_link" value='{"target":"curricular.activity","studcode":"0009130","activity_assign_id":"4522"}' />
	</cfhttp>
	```