# Banking-Application 

# Summary of All Endpoints
**1. Add Account (POST)**

**Method:** POST

**URL:** http://localhost:8080/api/accounts

**Headers:** Content-Type: application/json

**Body:** json

**Code**

{

  "first_name": "Deepti",
  
  "last_name": "Wani",
  
  "dob": "2003-09-15",
  
  "accno": "123456789",
  
  "branch": "Main Branch",
  
  "address_line1": "123 Main St",
  
  "city": "abc",
  
  "state": "xyz",
  
  "pincode": 90001
  
}

**2. Get Account by Customer ID (GET)**

**Method:** GET

**URL:** http://localhost:8080/api/accounts/{cust_id}

**3. Get Account by Account Number (GET)**

**Method:** GET

**URL:** http://localhost:8080/api/accounts/account/{accno}

**4. Get All Accounts (GET)**

**Method:** GET

**URL:** http://localhost:8080/api/accounts

**5. Update Account (PUT)**

**Method:** PUT

**URL:** http://localhost:8080/api/accounts/{cust_id}

**Headers:** Content-Type: application/json

**Body:** Full account details JSON.

**6. Partially Update Account (PATCH)**

**Method:** PATCH

**URL:** http://localhost:8080/api/accounts/{cust_id}

**Headers:** Content-Type: application/json

**Body:** JSON with fields to update.

**7. Delete Account (DELETE)**

**Method:** DELETE

**URL:** http://localhost:8080/api/accounts/{cust_id}
