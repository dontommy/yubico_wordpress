yubico_wordpress
================

wordpress/yubico bash install files

Purpose
================

Easy install of wordpress with yubico key plugin already activated

Specially for webmasters opening new blogs on the regulary


Requirements
================

1: A server/pc running linux

2: root access

3: internet access

4: Yubico Key


How To
================

1: Go the the folder where you want the wordpress installation
    
    run the command "cd /var/www/" thats the standard folder

2: Download the setup files
    
    run the command "git clone https://github.com/dontommy/yubico_wordpress.git"

3: Make them executeable
    
    run the command "cd yubico_wordpress"
    
    run the command "chmod +x *"

4: if LAMP is installed jump to step 6

5: Install LAMP
    
    run the command "./server_install" and follow the steps closely
  
6: Go to localhost/phpmyadmin in your browser and create a database

7: Go to https://upgrade.yubico.com/getapikey/ in your browser to get your Yubico Keys

8: Setup of Wordpress
    
    run the command "./wp_installer" and follow the steps
  
9: Now you just go to localhost/yubico_wordpress and finish the last few steps
