# GAS Development Environment
This Vagrant box provides an full development environment for GAS. It
includes a webserver setup to serve both the GAS API and the webclient,
along with an LDAP server configured in a similar manner to the GeekSoc
production server and loaded with a sample members database.

##Setup
* Clone this repository
* Clone gas-api into ./www/api.gas.geeksoc.org/public_html/
* Clone gas-client into ./www/gas.geeksoc.org/public_html/
* Use composer to install gas-client dependencies
* Update any configuration paramaters as needed
* Edit you hosts file to point api.gas.geeksoc.org and gas.geeksoc.org
  at 127.0.0.1
* Run vagrant up
* Visit http://gas.geeksoc.org:8080/

