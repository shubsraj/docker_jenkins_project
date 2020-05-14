# __Docker Jenkins__

## __intro__
I made this project with respect to complete my training of Docker by __IIEC Community__
Under the Guidance of __Vimal Daga Sir__

this project consists a Docker-compose file by which you can launch jenkins in just a 
blink of an eye. using __docker-compose__ feature.

## __Dependancies__
should have docker and docker-compose installed in your OS.

## __How to use__
create a seprate directory
1. copy and peste code in a .yml file with name docker-compose.yml
2. clone repository 

## __Commands__
inside that directory where this code is
* docker-compose up    (for creating and launching whole setup)
* docker-compose stop  (to stop jenkins)

once the setup is done you dont have to create it again and again(jenkins will start 
itself with your os but if not).
* docker-compose start

Then in web browser, in url tab type
> your os IP:8000

Thats it

## __Note__
* First time jenkins will require admin key that you can get from the path shown in jenkins login page itself.
* If jenkins crashes or won't work, your data is safe in docker volume attached with it.

If any feedback feel free to contact at - [Gmail]__shubshub1995@gmail.com__
