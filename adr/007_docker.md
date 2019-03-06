# Docker Capabilities and Overview

# Status: accepted

# Context: 

Docker is a computer program that performs containerization. These containers are isolated from one another and bundle together to create powerful systems. 

# Decision:

I have decided to use Docker containers for this system because they are very lightweight and scale easily. Docker containers are currently one of the most common platforms used in industry. Docker-compose's volumes feature will be used to have persistent data. In this example, the wp_data folder will be mapped to the /var/www/html directory of the Wordpress site and the db_folder will be mapped to the /var/lib/mysql directory. 

 
# Consequences: 

Containers do not run at bare-metal speeds but the speed currently provided is more than sufficient for this project. 
