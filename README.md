# customers-api
Slim 4 Framework: RESTful API example

https://www.twilio.com/blog/create-restful-api-slim4-php-mysql

Note:
The article has a typo.
Including the DB class in the index.php file is incorrect.

Instead of 
```php
use App\Model\DB;
```
need
```php
use App\Models\DB;
```
