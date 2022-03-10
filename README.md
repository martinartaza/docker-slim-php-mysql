# Docker php composer slim mysql phpmyadmin

#### Requeriments
Have install docker  

#### Steps

In this folder execute the following command
    ``docker-compose -up``

To connect mysql from container execute
``mysql -u project -h mysql project -p``
the pass is ``project`` 

#### Setting Hosts
add in your /etc/hosts the following line
``127.0.0.1 ::1 jobsity.local``

#### PhpMyadmin

In your browser you can see jobsity.local:8080 the phpmyadmin

#### Where install slim framework

in the folder ``src/public/jobsity`` here need all files slim project