# Swagger Maven Plugin use.
Swagger Maven Plugin with configurations adopted to create and persist plugin configurations and push definition into Azure DevOps Server (TFS)

```                
                <configuration>
                    <owner>STEAM-223-TEST</owner>
                    <isPrivate>false</isPrivate>
                    <token>2a223ad0-67e1-4225-a93c-5a612dbed93c</token>
                    <version>1.0.0</version>
                    <!--<inputFile>swagger</inputFile>-->
                    <!--<token>y7m2mutqnb72g3b4sdjdzfucgww2r2vqjdvihz3svisjv3ytq64a</token>-->
                    <uploadType>directory</uploadType>
                    <!--<format>json</format>-->
                    <!--<api>swagger</api>-->
                    <definitionDirectory>${project.basedir}/src/main/resources/api-definition</definitionDirectory>
                    <definitionFileNameRegex>^swagger\w*</definitionFileNameRegex>
                    <scmProvider>AZURE_DEVOPS_SERVER</scmProvider>
                    <branch>master</branch>
                    <repository>andrej-test</repository>
                    <scmProject>TestProject</scmProject>
                    <scmPersonalAccessToken>y7m2mutqnb72g3b4sdjdzfucgww2r2vqjdvihz3svisjv3ytq64a</scmPersonalAccessToken>
                    <scmUrl>http://10.100.10.90</scmUrl>
                    <scmProjectCollection>DefaultCollection</scmProjectCollection>
                    <protocol>http</protocol>
                    <host>localhost</host>
                    <port>8088</port>
                    <skipFailures>true</skipFailures>
                </configuration>
```                
PS: scmPersonalToken needs to be renewed as it expired on 1st of May 2019
