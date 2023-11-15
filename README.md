## LARAVEL CUSTOMER INVOICE REST-Api
 - LARAVEL for PHP framework
 - XAMPP for database

A simple customer invoice api database using laravel and mysql database. This app can do basic GET, POST, PUT, PATCH request with basic authentication for the users depending on the token used for the request.
 - user needs to go to '/setup' to generate the tokens
There are 3 tokens generated: admin-token, update-token and basic-token.
 - admin-token: can create, update and delete
 - update-token: can only create and update
 - basic-token: can only view data

For future development:
- implement the delete function for customers data
- update and delete function for invoices
