## Docker Compose LAMP stack with phpmyadmin and sync for osx

A hopefully simple Docker-LAMP stack for OSx with phpmyadmin. Uses syncing for osx - should be faster. Maybe I will add some more tools later.

To run it you need docker-sync:  
https://github.com/EugenMayer/docker-sync/wiki/1.-Installation


Based on:  
https://github.com/moyed/docker-compose-lamp-stack (fork / modified)  
and:  
http://docker-sync.io 

After cloning run:  
docker-sync-stack start  
into the main directory. THe ./html directory is synced to the containers webserver.
