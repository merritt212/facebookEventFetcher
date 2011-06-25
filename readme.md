Facebook Event Fetcher Wrapper for PHP
======================================
Event Fetching from facebook profile .

The [example][example] is a good place to start.

Usage
-----
The minimal you'll need to have is :
1. Host the code
  i> upload this folder somewhere in the internet .eg: example.com/facebook.
  ii> Will not work with localhost.

2. Create facebook application first
  i> Follow the link http://www.facebook.com/developers/createapp.php
  ii> After registering the application facebook will provide app id, api key and app secret . Save these credentials and replace these in index.php and cron.php
  iii> Edit the application setting .
	In the Facebook integratin tab specify "Canvas Page" for the url of the application.(eg apps.facebook.com/eventfetcher)
	Replace "Canvas URL" with example.com/facebook/ specified in 1>i> above

3. Use the application
  i> Once you go to the application url(eg. apps.facebook.com/eventfetcher) it will prompt you to login .
  ii> Facebook will ask for the permission from user to allow the access to his/her information.

4. save the events
  i> in the index page access token will be available from the session, save it somewhere (database)
  ii> Use cron.php with cron of some other script to fetch the events in the future


The [examples][examples] are a good place to start. The minimal you'll need to
have is:

[example]: https://github.com/prabeshshrestha/facebookEventFetcher/blob/master/index.php

Feedback
--------

You can directly send me a issue to prabesh708@gmail.com or report the issue in github.
Or you Can fork the project / fix the issue / and send me a pull reques

