# Steps to prepare First Spring Application[Core Module]:

1. Download spring farmework[Jars] from Internet.  
2. Prepare java project in Eclips IDE.  
3. Prepare spring liabrary with required jar files.  
4. Prepare Bean class.  
5. Prepare Spring configuration with bean class.  
6. Prepare Test Application.  

# 1. Download spring farmework[Jars] from Internet.  

https://repo.spring.io/ui/native/release/org/springframework/spring

1. commons-logging-1.2  
2. spring-beans-4.3.4.RELEASE.jar
3. spring-context-4.3.4.RELEASE.jar  
4. spring-context-support-4.3.4.RELEASE.jar  
5. spring-core-4.3.4.RELEASE.jar  

# 2. Prepare java project in Eclips IDE.  

# 3. Prepare spring liabrary with required jar files.  

# 4. Prepare Bean class.  

a. Bean is a reusable component,it is a normal java class having properties and the respective setXXX() and getXXX() methods.  

b. Spring Framework is using POJO[Plain Old Java Object] classes ,it will not extend or implement any predefine liabrary except java.io.Serializable marker interface.  

    UseBean----> JSP  
    ActionForm/FormBean---> Struts  
    BackingBean---> JSF  
    POJO---> Hibernate  
    POJO---> Spring  
    
c. In Spring Framework, POJO class must be Java bean class,It must be declared as a public ,non abstract and non final.  
    
    i. The main intention of declaring Bean as a public is to make available to spring Framework indore to create objects.  
    ii. In Spring Framework Applications, Spring Framework must create object for the Bean class,it must be non abstract.  
    iii. In Spring Framework Application, if we want to extends one bean class to another class as per the requirements and   as per improviding code reusability we must declared bean class non final.  
    
    

