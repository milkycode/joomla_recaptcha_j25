# Google ReCaptcha v2 fix for Joomla 2.5 ReCaptcha plugin

Google support for ReCaptcha v1 ended on 31st March 2018. 
Then the Joomla 2.5 default ReCaptcha plugin stopped working.

* https://www.milkycode.com
* Like us on Facebook: https://www.facebook.com/milkycode

To keep it working and upgrade it to Captcha v2, here is a fix for the Recaptcha plugin shipped with Joomla 2.5:

* On your site, backup the file ./plugin/captcha/recaptcha/recaptcha.php
* Replace it with the recaptcha.php from this repository
* You need to create a new ReCaptcha v2 API Key and Secret from https://www.google.com/recaptcha/
* Everything else, including admin UI, remains unchanged.
* Enter the new credentials and save the plugin config.

Thats's it, just reload the page. Clear the cache if necessary.