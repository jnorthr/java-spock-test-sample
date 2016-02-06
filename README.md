Java meet Spock
===============
Sample Gradle Project with Java and Spock tests
---------------------------------------

Sample project configuration with Maven for Java project with readable tests written in [Groovy 2](http://groovy.codehaus.org/)
with [Spock Specification Framework](https://code.google.com/p/spock/)


Simple project configuration
----------------------------

### Project structure

    src/
       main/
           java/
               *.java       (java source code)
       test/
           groovy/
               *Test.groovy (spock code)

        <dependencies>
            <dependency>
                <groupId>org.spockframework</groupId>
                <artifactId>spock-core</artifactId>
                <version>1.0-groovy-2.4</version>
                <scope>test</scope>
            </dependency>
        </dependencies>

     </project>


