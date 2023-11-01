## Variables:
- It is used to store data.  
Ex: var = "Aadarsh"
- There are two types of variables.
1. User defined variables
2. Jenkins environment variables

**1. User defined variables:**

- These variables are static.  
*A. Local variables:* Variables which defined inside the job is called local variables.  
*B. Global Variables:* Variables which defined outside the job is called global variables.

**2. Jenkins environment variables:** 
 
- Variables which change from build to build is called Jenkins environment variables

## Variables:
**1.User defined variables:**   
**a) Local vars:**  
**Process:**

1. Create Jenkins job
2. Under Build Steps option select “Execute shell”
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/0bf95bf9-53ba-4bd5-9426-69e28c674fa0)
3. Write script, add variable in script like below and save 
![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/835d8e3d-e497-467c-9be5-617a38c0981c)
4. Build your job and check output.

**b) Global Variables:**  
**Process:** 

1. Go to Dashboard
2. Select Manage Jenkins option
3. Go to system option
4. Under global properties option, Select Environment variables and add variable
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/2cb1aa43-c758-45ba-aaf4-7ead37e98711)
5. Add global variable in your script like below.
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/27aae238-b650-487b-8c25-8b1b964c6be3)
6. Build your job and check output

**2. Jenkins Environment Variables:**  
**Process:**

1. Create Job
2. Under Build Steps option select Execute shell and write below script
 ![image](https://github.com/aadarshkumar03/DevOps/assets/96613300/3ca9bc38-42fa-42cd-a1b9-9a370e4344e9)
(Note: Click on “the list of available environment variables” to know the available environment variables)
3. Save, build your job and check output.
