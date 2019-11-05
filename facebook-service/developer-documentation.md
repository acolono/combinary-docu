---
description: Additional information for developers
---

# Developer Documentation

#### Explanation of site code

A **.docksal/etc/php/php.ini** file should exist if you want to be able to add sttings such as `xdebug.remote_host`_._

_**Database**_ folder contains the setup for the database and creates the required tables for the Facebook Graph API calls to be able to save the information to them.

_**docker**_ folder contains important environment variables for the site. Important to change is the `LIVE_URL` and `DEV_URL` depending on where you are running the application. Also setting the `Development` variable to `true` or `false`so the redirects are to the correct address.

_**docroot**_ contains the css and images requires as well as the application code. The main files are index.php, monitor.php and manage.php. The rest contain helper functions to save data to the database, get information from the Facebook Graph API and parse data. webhooks.php and webhook\_helper.php help to save webhook results by first confirming the webhook is actually from Facebook by checking the sha signature. wenhook\_helper.php helps to save data coming in from webhooks.



