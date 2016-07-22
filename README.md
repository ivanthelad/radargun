# radargun
Image to execute performance test on the official JDG image from Redhat

##To build the zip or distributiob 
- Clone https://github.com/radargun/radargun.git
- cd to folder
execute the following maven 
 - mvn clean install -Dno-coherence -Dno-ehcache -Dno-chm -Dno-hazelcast -Dno-jgroups -Dno-jbosscache -Pjdg -DskipTests -U
 
 
 
 ## more info
  - example scenarios https://github.com/radargun/radargun/tree/branch_2.x/core/src/main/resources
  
