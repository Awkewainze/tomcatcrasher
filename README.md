# tomcatcrasher
This is a personal hackathon project which is the war file for a simple website. To properly use this  
  
1. Install Docker http://docs.docker.com/linux/started/  
2. Then run the command "docker run -it --rm -p (desired port):8080 dylanw/hackathon"  
    (this installs ubuntu, then java, then tomcat, and finally this war file, it then launches the tomcat server and boom, there is this website.)  
3. Reach this website with http://(localhost|your ip):(set port)/Crasher_war/Crashsite.html  
    
This was to demonstrate the power of Docker containers (and eventually Kubernetes) but was unable to be finished by
hackathon end time.  

The Docker part is complete and this file is just the war component, the "DO NOT PRESS" button will shutdown the web service  
This was to test Kubernetes heartbeat checker and allow it to spin up a new container with this images...  
Was gonna be pretty legit
