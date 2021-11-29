# Sharewell tech test task
The idea is to understand the knowledge of the applications architecturing. You can create this service in one `index.php` file, but we would like to see there the custom architecture that covers the API and data storing modules, provides clean Model-Controller (no View, we do not expect UI at all) structure, and wraps repetitive code in a comfortable OOP system.

We need to build a service that stores the information about users and can also provide it by request. 

### The interaction with the service is simple:
* It must accept POST request with JSON body and store the data
* It must accept GET request with `email` parameter and return the data about stored user or 404 error if user not exists
* The user data sent must be validated

### The example of the user data:
* email (string) - email regex rules
* name (string) - min 3 characters
* company name (string) - min 3 characters
You can add additional validation rules if you see it’s necessary.

### The service must include:
* REST API architecture to accept requests mentioned above
* The system to store the data (no need for a real database, data can be stored in just json files, but it is up to you to decide how to store it)
* PSR usage in API
* The service must be easily extendable

### The technical requirements:
* Language: PHP >= 7.*
* No UI needed, all interactions are through API
* Clean MVC architecture
* No Frameworks

Please, fork this repository and create a service. Send a link to the result on info@sharewell.eu
