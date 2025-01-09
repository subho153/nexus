Nexus Install process
There are two way we can install nexus

process1:

  1. wget https://download.sonatype.com/nexus/3/latest-unix.tar.gz
  
  2. tar -xf latest-unix.tar.gz
  
  3. ls
  
  4. cd nexus-3.76.0-03
  
  5. cd bin/
  
  6. chmod +x nexus
  
  7. ./nexus start

process2:

  1. docker run -d --name nexus -p 8081:8081 sonatype/nexus3
  
