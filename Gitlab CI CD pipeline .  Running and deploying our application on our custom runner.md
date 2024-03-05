Gitlab CI CD pipeline .  Running and deploying our application on our custom runner

**1.Creating a python app file and comminting in a repo in gitlab**


![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/94cdc16d-e347-4397-9b75-f5a2395e98a3)


**2.Creating a dockerfile in the same repo for the python app and writing all the dependencies and the script.**


![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/5ecdb148-7876-4047-8bac-900c90a20bc3)


**3. Now we can go for creating our own CICD pipeline for the custom gitlab runner. YAML File**


![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/d1087cb3-b8d7-487f-ae39-fe8adace902f)


**4. Install the docker on the aws instance and also install gitlab runner in the docker group**


![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/a4aed9e8-0167-46bb-95f1-e83ccee6b67f)



**5. After job succeded, we can access the app using the public IP of the AWS Instance.**


![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/d4098640-e193-4cc6-896f-07db2a6a2bad)



