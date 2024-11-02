#####

A few Notes before we get into the project:
1. I don't have expertise in working with pandas library, So I have used PySpark to do this assignment.
2. Also, I don't have experience with Docker since my company/project is using AWS cloud. We just have to write the PySpark code and push it to Bitbucket, so I haven't created a Docker file.
3. Having said the above 2 points, I am flexible about learning. I thought of learning it within the given timeframe, but since it was the festive weekend, I couldn't. 
4. Below tools I have used for this assignment:
   a. Jupyter notebook
   b. Open source Postgre server whose server details are below:
       Service URI: postgres://avnadmin:AVNS_yGpIBK9-f-QpZ5bA7ri@pg-nikhiltest-nnn-nikhiltest.h.aivencloud.com:17081/defaultdb?sslmode=require
       Database Name: defaultdb
       HostName: pg-nikhiltest-nnn-nikhiltest.h.aivencloud.com
       Port: 17081
       User: avnadmin
       Pass: AVNS_yGpIBK9-f-QpZ5bA7ri
       SSL Mode: require
   c. PySpark framework with version 3.5.3
   d. psycopg2 library to work with Postgre
   e. urllib.parse to parse the URI
5. To execute the code follow the below steps:
   a. Open Jupytar notebook.
   b. Make sure Pyspark is available in your system.
   c. You can check this by executing the below code in your notebook:
       import pyspark
       print(pyspark.__version__)
   d. upload the entire folder to your Jupiter notebook.
   e. Now execute the KinaraAssignment/PySpark.ipynb
   f. At the end I have given execution code, execute that as well.
   g. load_data(transformed_df, "employees") -> Here "employees" is the table name.

6. I have also attached the TDD in doc file with execution images.

########