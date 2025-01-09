Nexus Install process
There are two way we can install nexus
process1:

  wget https://download.sonatype.com/nexus/3/latest-unix.tar.gz
  
  tar -xf latest-unix.tar.gz
  
  ls
  
  cd nexus-3.76.0-03
  
  cd bin/
  
  chmod +x nexus
  
  ./nexus start

process2:
  docker run -d --name nexus -p 8081:8081 sonatype/nexus3
  
