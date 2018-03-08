**school.fees**
----
  Redirects to the target program Make a Payment > School Fees Account after a successful user login.

* **Version:**

  	`1`

* **Permission Required:**

  	`School Fees Account`

* **Method:**

  	`GET | POST`
  
*  **Params Required:**

	   `target [string]` - The target program to be redirected to.

* **Success Response:**

    ```HTML
    http://domain.com/parentlounge/login.cfm?sso_token=1EE8C0F6073C88B52AC9EA08D62937C1
    ```
    
* **Error Response:**

    ```javascript
    "response_code":"4"
    ```
    
* **Sample Parameters:**

	```HTML
	"target":"school.fees"
	```

* **Deep Link without SSO**

	```HTML
	http://domain.com/parentlounge/login.cfm?go={"target":"school.fees","prod_menu":"Y"}
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
		<cfhttpparam type="formfield" name="deep_link" value='{"target":"school.fees"}' />
	</cfhttp>
	```