# create-vertual-host-in-ubuntu

Enter following cmd

Step 1: `cd /etc/apache2/site-available/`

Step 2: `sudo cp 000-default.conf YourServerName.conf`

Step 3: `sudo a2ensite YourServerName.conf`

Step 4: `sudo nano YourServerName.conf`
      
      In step 4 add below lines :-
      ServerName myserverurl.com
      ServerAlias www.myserverurl.com

Step 5: `cd /etc/`

Step 6: `sudo nano hosts`

Step 7: add `127.0.0.1    myserverurl.com` in the list.
