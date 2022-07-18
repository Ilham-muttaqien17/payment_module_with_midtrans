# payment_module
This is repository for payment gateway LMS using Midtrans

## How to use
Clone this repository
```
git clone https://github.com/Lumintu-Batch-2/payment_module
```
Go to directory
```
cd payment_module
```
Install composer dependencies
```
composer install
```
Copy .env.example to .env
```
MIDTRANS_SERVER_KEY="YOUR MIDTRANS SERVER KEY"
IS_PRODUCTION="true"
MAILTRAP_USERNAME="YOUR_MAILJET_API_KEY"
MAILTRAP_PASSWORD="YOUR_MAILJET_SECRET_KEY"
MAILTRAP_EMAIL="YOUR_MAILJET_EMAIL_SENDER"
```
Import sql database
```
payment_db.sql
```
Start your webserver
```
apache
or
nginx
```

Enjoy:)

