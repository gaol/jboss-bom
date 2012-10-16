JBoss Java EE 6 with Hibernate
==============================

This BOM builds on the Java EE full profile BOM, adding Hibernate Community projects including Hibernate ORM, Hibernate Search and Hibernate Validator.

It also provides tool projects such as Hibernate JPA Model Gen and Hibernate Validator Annotation Processor.

Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
	    <dependency>
	       <groupId>com.redhat.jboss.wfk.boms</groupId>
               <artifactId>jboss-javaee-6.0-with-hibernate</artifactId>
               <version>1.0.1.Final-redhat-1</version>
               <type>pom</type>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement> 

