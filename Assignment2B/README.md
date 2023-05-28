Create Docker Container Environment

go Docker docs

2. insatll
3. Docker Desktop for window
4. open from desktop
5. in TERMINAL
------------> docker -v
------------> docker images
------------> docker ps (which container is running on docker)
6. go docker hub
multiple image are available

7. Search openjdk ----> in docker hub

8. copy the commant which is use for pulling jdk

------------> docker pull openjdk 
if you want python then go docker and pull it

9. run image by
------------>docker run --name JAVA -it -d openjdk

10. cheak which cantainer is running
------------>docker ps

11. Execute cantainer
------------>docker exec-it JAVA jshell
*JAVA is anyname you can give*
all command run then we can run any program in this container
example :- print any things inside JAVA
system.out.print("Hello Dcker");

12. Then perform addition program

13. stop running container
------------>/exit
------------> docker stop container_id
------------> docker container rm container_id

