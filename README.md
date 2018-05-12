# docker-mysql-demo
Create a MySQL container in Docker and establish connections with other containers . And implement the persistent preservation of data . 

## how to use 

### Start Mysql in docker 

* pull mysql images :

        docker pull mysql:5.5.60

    or you can simply run 
    
        ./build-image.sh
        
* in this project , we use ./mysql/conf and ./mysql/data to save data from docker mysql . 

    so , plz rm the content in data , and do not remove the mysqld.conf file in ./mysql/conf
    
* start mysql :

        docker-compose up -d mysql     

        
                