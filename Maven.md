##  Maven:

- It is an automation project management tool developed by ASF (Apache Software Foundation) released on 12 July 2004.
- It is a build tool and it is used to add/manage dependencies for the code.
- It converts the source code into artifact for deployment.
(Artifact is nothing but the final product(JAR, WAR, EAR))
- It is based on POM.XML
(Project Object Model) (Extensible Markup Language)
- POM.XML contains information and dependency for code.
- POM.XML file consists metadata, dependencies, kind of output/project, description.  
(Note: One project contain only one workspace and each workspace consists of one POM.XML file)

- Maven Home Path: ".m2" folder
- Dependency: java-1.8.0-openjdk 

**Architecture/Process:**  
Code --> Compile --> Test --> WAR  
Code(GitHub) --> artifact(Maven) --> tomcat(WAR)

1. Get code from GitHub and convert into artifact
2. To convert into artifact we are going to execute the GOAL  
(GOAL is nothing but the command used to execute maven task)
3. GOAL is referring to POM.XML  
Note: If we have fresh server then we don't have plugins on local repo, it will download from remote repo only. Once we download plugins from remote repo to local repo then we have compiler plugin.

**Installing process:**

*#yum install git java-1.8.0-openjdk maven tree -y*  
*#git clone https://repo_link*  
*#cd repo_name*

**Maven Commands:**

1. To compile the source code (GOAL)  
*#mvn compile*

2. To test the source code  
*#mvn test*

3. To generate artifact from source code  
*#mvn package*

4. To copy artifact into local folder (.m2 folder)  
*#mvn install*

5. To delete the target folder  
*#mvn clean*

6. To perform complete life cycle  
*#mvn clean package*

**Commands history of my EC2-Instance**
 ![image](https://github.com/aadarshkumar03/Hackerrank-Python-Solutions/assets/96613300/6935d72d-885e-47c2-9fa0-861129508a3b)
