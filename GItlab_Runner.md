# Gitlab-Runner-Documentation
We can learn how to ceate a custom runner and delploy it on the AWS EC2 instance doing ssh configuration

**1. Open Gitlab and choose cicd**

![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/22f47d61-a646-4e12-a881-ed6d1aaf0944)

**2.**



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/b71815cf-57e1-4afe-9340-6b16afb554bf)



**3.**



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/df30a659-112f-4739-8ff5-48eef44d59bd)



**4. Copy all these commands and put it in a script file in the AWS terminal**



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/81aabd43-6ba4-4db7-b03f-4c7dfcad6df2)


![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/d0da3662-273e-43d3-bdd2-6bc3fc6a04cd)



**5. Paste all the commands**



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/aa3ad4dc-3bf9-435d-ab22-aa0819201a84)



**7. Giving it the execution/read,write permissions**



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/d30bb2bc-a7a9-4f64-aa32-a975827f12db)



**8. command to register the runner**



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/d6cca3a7-ad0d-465f-ae0c-3611dfa7c7f5**)



**9. Registering the rinner on the ec2 by pasting the command**



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/3c294c5a-f76b-4599-a07f-1f9224ceaba4)



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/27a3d85b-80f3-46e4-8ab8-b0e14856c0ef)



**10. Press Enter-Enter by looking at the token and matching it with the runner token on the gitlab site**


**11.It Asks for different types of executers like docker, docker-ssh, docker-windows, sh, bash,etc.**

![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/2b2c6aa5-7f84-4e9a-be8f-61a55e77539d)



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/a5f6bf99-0edd-4ff4-a1c6-db4ebfb11345)


**12. After that when we go in our git lab account and expand runners section, we can see our runner in the list.**



![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/8ac5cbe9-ad4d-4860-8918-37e2f06dfd4c)


**Adding Gitlab Runner to the AWS instance**


![image](https://github.com/kushalShuklaaa/Gitlab-Runner-Documentation/assets/96085546/4c70c35e-252c-4574-aa40-7c32765edaef)




