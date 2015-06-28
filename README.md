Digital Ocean DynDNS
====================

Updates the A record of a domain using the API v1 provided by Digital Ocean.

Usage
-----

To update the IP of myrecord.yourdomain.com:

    digitalocean-dyndns --domain yourdomain.com --record myrecord

Options
-------

* `--allownew`: With this flag, the record will be created if it does not exist
* `-v`, `-vv`: To increase the verbosity

Requirements
------------

* Python >= 2.7
* Python package `requests`

Installation
------------

Install the dependency.

    pip install requests

Clone the repository, or download it.

Edit the file to fill in your client ID and API key.

That's it.

(To install `pip` use `brew`, `apt-get` or see: http://www.pip-installer.org/en/latest/installing.html)

License
-------

Licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php)
