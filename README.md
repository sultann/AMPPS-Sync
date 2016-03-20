# AMPPS-Sync

To Sync your AMPPS project within multiple machine you can follow the steps below:
* Copy www and var directory to your desired location and then remove those from AMPPS
* open your terminal and use below code to make simlink
//for www direcory

ln -s current_www_location location_where_itwas_in_aampps 

again for var directory
