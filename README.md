# prjmvc01

# Java Profiling:

## JProfiler
  Tutorial:
  * https://www.youtube.com/watch?v=DsJgiRp-yLw
  * https://www.youtube.com/watch?v=032aTGa-1XM
  * https://www.youtube.com/watch?v=ZwBiVYOWrSc&list=PLCyYT3oyW-T3Y3BYC3H_NLzCXQE6o_Fmx&index=7
    * pour surveillance JPA/Hibernate
    * toto

## Surveillance de fond
  A inclure dans la JVM: Java Melody
  
## Tutorial sur le fonctionnement de la JVM
  https://fr.slideshare.net/muhammedshakirmisarwala/java-performance-monitoring-tuning
  
# Logging

## activation log hibernate

cf. https://stackoverflow.com/questions/30118683/how-to-log-sql-statements-in-spring-boot

cf. https://www.mkyong.com/spring-boot/spring-boot-show-hibernate-sql-query/

Dans application.properties
#spring.jpa.properties.hibernate.show_sql=true
#spring.jpa.properties.hibernate.use_sql_comments=true
#spring.jpa.properties.hibernate.format_sql=true
#
#spring.jpa.properties.hibernate.type=trace 

logging.level.org.hibernate.SQL=DEBUG
logging.level.org.hibernate.type=TRACE
spring.jpa.show-sql=true 
