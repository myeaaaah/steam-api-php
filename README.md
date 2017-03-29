# README 
- Project Name: steam-api-php
- Description: PHP Class that connects to Steam API via web with PHP. 
- Requirements: 
    PHP VERSION: >5.0
    Libraries  : Openid (included in project)

# USAGE EXAMPLE

```php
<?php
require('steam.php');

$steam = new Steam("http://localhost", API_KEY);

$steam->login( function($loggedUserData){
    // handle the logged user data information as you wish. 
});

$playerSummaries = $steam->get("playerSummaries", STEAMID);
?>
```

# SUPPORT
I believe this project is stable and due to my lack of time I will give no support. 

# ERRORS
Please get in contact if you find any error's.

Email: myeaaaah@gmail.com

# CONCLUSION
Hope it comes to good use.

myeaaaah.
