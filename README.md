SendToSauce
===========

Spins up any number of Sauce Labs test VM's automatically, OS and browser specified by user. It (will) send given tests along to Sauce Labs and automatically run them

Dependencies
============
Python version 2.7.3+

Selenium webdriver

How To Use
==========
To specifiy which OS and browsers you would like to test on, edit the BrowserCompatibility.config.

By default, all OS and browsers in this config file are commented out.

Uncommenting whichever OS+browser combinations you want to test on will spin up a new VM with that configuration.

