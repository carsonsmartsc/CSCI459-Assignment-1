# ACID and BASE Overview

# Status: accepted

# Context: 

ACID stands for Atomicity, Consistency, Isolation, and Durability. 
BASE stands for Basically Available, Soft State, and Eventual Consistency

According to https://dev.mysql.com/doc/refman/5.6/en/mysql-acid.html MySQL follows the ACID integrity guarantees. I was unable to locate any resources on whether or not MySQL follows BASE and if Wordpress follows either integrity guarantees. 

# Decision:

Wordpress and MySQL are fairly strong in keeping persistent data with the use of backups. The data is manipulated and only stored in one active location and MySQL does a good job at handling requests from multiple users at the same time while keeping the data consistent. 

 
# Consequences: 

ACID and BASE are generally big concerns in production and this site will likely only be used by my professor and myself. If the system begins to scale, more research and work should be done to ensure both ACID and BASE are satisfied. 
