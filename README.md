fl_simplesamlphp
================

PHP SimpleSaml Implementation already configured to work with Fucina Ludica's Identity Provider. Follow the readme instructions to deploy it.

* Register your SP with FucinaLudica by contacting info@fucinaludica.it
* Create certificates for your SP by giving these commands:
```shell
cd cert
openssl req -newkey rsa:2048 -new -x509 -days 3652 -nodes -out saml.crt -keyout saml.pem
