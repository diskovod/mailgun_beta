Mailgun DEMO.
Examples for all endpoints you will find under:
mailgun_demo/examples

To run tests and examples please use virtualenv with next template:
````
DOMAIN="DOMAIN_NAME"
APIKEY="API_KEY"
MESSAGES_FROM="Name Surname <mailgun@domain_name>"
MESSAGES_TO="Name Surname <username@gmail.com>"
MESSAGES_CC="Name Surname <username2@gmail.com>"
DOMAINS_DEDICATED_IP="127.0.0.1"
MAILLIST_ADDRESS="everyone@mailgun.domain.com"
VALIDATION_ADDRESS_1="test1@i.ua"
VALIDATION_ADDRESS_2="test2@gmail.com"
````

Test library in Test PyPi
https://test.pypi.org/project/mailgun-demo/1.0.4/

After you will install this you can just import it like:
````
from mailgun_demo.client import client

client = Client(auth=("api", key))
````
Check examples for more details