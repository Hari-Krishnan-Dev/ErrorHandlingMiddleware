# Express Registration Validation
###### This Express application provides a registration endpoint with data validation for first name, last name, password, email, and phone number.

# Getting Started

* POST /register: Endpoint for user registration.
  * Request Body :
  ```
  {
  "firstName": "John",
  "lastName": "Doe",
  "password": "StrongPassword123!",
  "email": "john.doe@example.com",
  "phoneNumber": "1234567890"
   }
   ```
   
  *  Response (Success): 
 
   ``` 
   {
  "message": "User registered successfully!"
   }
   ```
   
    * Response (Error):
   
    ```
    {
     "error": "Error message here"
    }
    ```
