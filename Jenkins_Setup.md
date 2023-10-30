## Jenkins:
- It's a CI/CD tool.

**CI: Continues Integration**

- It is combination of Continues build and Continues test
- Build, Test and Deploy all these activities are performed on single CI Server.

**CD: Continues Delivery + Continues Deployment**

***Continues Delivery:***  
Anytime a new build artifact is available. The artifact is automatically placed in the desired environment and deployed.

***Continues Deployment:***  
When we commit our code then it gets automatically tested, build and deploy on the production server.

`Deployment: The process of Installing application on app server.`

**Jenkins:**

- It's a CI/CD tool.
- It is used to automate entire SDLC (Software Development Life Cycle)
- It is free and open-source tool.
- It was invented by sun-microsystem as Hudson which is paid tool.
- Later oracle brought Hudson and renamed it as Jenkins.

**About Jenkins:**  
Platform: Independent  
Dependency: Java-11  
Who: Koushuke Kawaguchi  
Year: 2004  
PORT: 8080  

**Advantages:**

- Jenkins follows master-slave architecture.
- Jenkins master is going to assign a job to the slaves.
- If slaves are not available then Jenkins itself does the job.
- By using labels we can specify the jobs to the nodes.


**Steps to setup Jenkins**

1.	Create Script  
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/89240838-9c6b-4d8c-956e-94abc2b71c7f)

	Script Content:  
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/ce5a378c-7723-4fb6-ab36-6fd449f1791b)

2.	Run Script  
![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/26c3075c-d398-42ec-8c53-7d1625785f79)
 
3.	Public_ip:8080 (18.133.233.100:8080)  
![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/8b11b220-3876-41ec-9f3c-8741112311f9)
 
4.	Copy password from server/instance using below command, paste it in Administrator Password and click on continue  
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/745c7c75-6822-425b-b048-bb0eb24308e5)

5.	Click on Install Plugins  
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/3b52dfdd-b3e8-4d5c-bbd0-4db911008539)

6.	After plugins installed successfully, give user details  
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/84a4ccac-eb07-4cb2-890d-c50e5742b6ec)

7.	After this step, click on save and finish and then click “Start Using Jenkins” and enjoy.

**Process to Create Job**

After Jenkins setup you redirect to Jenkins dashboard and to create job/project follow below steps.

1.	Click on new item, enter name, select Freestyle and click on “OK”
2.	Then you will redirect to configuration page  
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/60158127-f604-4306-aacd-18829ececc30)
3.	On this configuration page under Source Code Management option, select “GIT” and enter repository URL and repository details.
4.	On same page Build Steps option, select execute shell and enter “mvn clean package”
5.	Save and build your code. 
