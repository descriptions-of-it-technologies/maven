# Maven Commands.





| Key/Command                                        | Description                                           |
| -------------------------------------------------- | ----------------------------------------------------- |
| mvn versions:display-dependency-updates            |                                                       | 
| mvn archetype:generate                             |                                                       |
| mvn spring-boot:run                                |                                                       |
| mvn clean                                          |                                                       |
| mvn clean deploy                                   |                                                       |
| mvn clean eclipse:clean eclipse:eclipse            |                                                       |
| mvn clean install                                  |                                                       |
| mvn clean install eclipse:eclipse                  |                                                       |
| mvn clean initialize                               |                                                       |
| mvn clean install -DskipTests                      |                                                       |
| mvn clean install -DskipTests --offline            |                                                       |
| mvn compile                                        |                                                       |
| mvn clean package                                  |                                                       |
| mvn clean test                                     |                                                       |
| mvn clean verify                                   |                                                       |
| mvn clean verify -DskipTests                       |                                                       |
| mvn deploy                                         |                                                       |
| mvn dependency:resolve -Dclassifier=javadoc        |                                                       |
| mvn dependency:tree                                |                                                       |
| mvn eclipse:eclipse                                |                                                       |
| mvn jetty:run                                      |                                                       |
| mvn package                                        |                                                       |
| mvn site                                           |                                                       |
| mvn dependency:sources                             |                                                       |
| mvn test                                           |                                                       |
| mvn tomcat:run                                     |                                                       |
| mvn tomcat7:run                                    |                                                       |

`mvn -f $(git rev-parse --show-toplevel 2>/dev/null || echo ".")/pom.xml`
