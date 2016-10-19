# play-framework
sample play application

Deploying sample app on container with play framework

Docker pull dordoka/play-framework (Container with play framework and activator)
         
         (https://hub.docker.com/r/dordoka/play-framework/)

Download sample app for playwork s0 simply get it from git 
         
         git clone https://github.com/nikitsenka/play-jpa-java-example.git

Run command:

         docker run -d -it -v "/home/abhi/play-jpa-java-example/app:/home/play/Code" -p 9000:9000 -p 9999:9999 -p 8888:8888 dordoka/play-framework

         docker attach container_id

Change the directory to /play-java/bin/ of project and run activator 

Code/play-java/bin/activator

Code/play-java/bin/activator new

then enter play-java as name and then again enter play-java or simply hit enter for play-java

then /home/play/Code/play-java/bin/play-java/activator run

then simply run the localhost:9000 in browser


