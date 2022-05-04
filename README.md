### M-PESA Laravel Turials Source code
Hello Guys,

#### Installing this code
- Clone this repo
- Run ```composer install``` while in the root directory of the project
- Run project either via xampp/mampp/apache/nginx etc 


#### Modifying
In this project, we have uploaded the ```.env``` file, and you will get the M-PESA configuration files that are required. To change to your details, please edit the following as per the tutorial

```env
MPESA_CONSUMER_KEY=
MPESA_CONSUMER_SECRET=
MPESA_SHORTCODE=
MPESA_STK_SHORTCODE=
MPESA_ENV=
MPESA_TEST_MSISDN=
MPESA_TEST_URL=
MPESA_PASSKEY=
MPESA_B2C_PASSWORD=
```

#### Modifying Controllers
To edit controllers specific for this project, open ```App\Http\Controllers\Payments\mpesa\``` and you will find our controllers.




