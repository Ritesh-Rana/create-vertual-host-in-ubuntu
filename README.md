# create-vertual-host-in-ubuntu

Step 1: cd /etc/apache2/site-available/

Step 2: sudo cp 000-default.conf YourServerName.conf

Step 3: sudo a2ensite YourServerName.conf

Step 4: cd /etc/

Step 5: sudo nano hosts

Step 6: add 127.0.0.1 and url of yourserver (Example - myserverurl.com)
