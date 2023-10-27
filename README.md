IMPORTANT!!!!
File is too big for github (3GB) so I store it on Drive.

Here are the steps:
1. Download the file from this link, unzip it:
   https://drive.google.com/file/d/1DUVf5pNbBx_V3lPgjgza763_49VB24pC/view?usp=share_link

2. Go to .env file; create DB and then check and update information to connect DB in .env. 

3. Import kidszone.sql 
   
4. Create generate key:
   php artisan key:generate
   
5. Clear cache server:
   php artisan config:cache

6. Run project:
   php artisan serve

7. Go Link: http://localhost:8000/

PAYMENT GUIDE (I use MOMO payment method):

When you are in the checkout page, open this link in a new tab: https://developers.momo.vn/v3/vi/docs/payment/onboarding/test-instructions/

Scroll down to the "THÔNG TIN TEST THẺ ATM" section 

Copy infomation from row 1 (no need to enter phone number)

Once done, it will take you to a Confirmation Page. Enter OTP then proceed.

It will take you back to the main website.
Cheers!
