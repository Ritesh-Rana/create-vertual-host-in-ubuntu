# create-vertual-host-in-ubuntu

Enter following cmd

Step 1: `cd /etc/apache2/sites-available/`

Step 2: `sudo cp 000-default.conf demo.conf`

Step 3: `sudo a2ensite demo.conf`

Step 4: `sudo nano demo.conf`
      
      In step 4 add below lines :-
      ServerName demo.com
      ServerAlias www.demo.com

Step 5: `cd /etc/`

Step 6: `sudo nano hosts`

Step 7: add `127.0.0.1    demo.com` in the list.
