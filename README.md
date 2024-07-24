# Upgrade Java from 11 to 17 manually
In this demonstration I will upgrade Java (which was installed on Rocky Linux) from Java-11 to Java-17 manually.

In below screenshot a Linux machine with Rocky Linux with Java-11 installed is shown below.
![image](https://github.com/user-attachments/assets/c836ff36-2236-4bec-9ad5-74ce73d40685)
![image](https://github.com/user-attachments/assets/d91a5c3d-0836-4297-97ad-09beae1faa04)
![image](https://github.com/user-attachments/assets/8bf3a11b-e5d6-485e-b3d4-2f9ea7248aaf)

Download tar file for java-17 and unarchive it.
![image](https://github.com/user-attachments/assets/5d272812-006b-4de3-bf7a-4ed48f8a30ac)
![image](https://github.com/user-attachments/assets/432ec0d5-7d75-45ae-9fec-e4041d1b91ce)

Change JAVA_HOME and PATH in /etc/profile file as shown in screenshot below.
![image](https://github.com/user-attachments/assets/e3078081-b712-4918-b56d-0c6e9b6ac758)
![image](https://github.com/user-attachments/assets/5f713508-cb49-41bd-a92c-7126b7c93f55)

Now check PATH, JAVA_HOME and java -version as shown in the screenshot below.
![image](https://github.com/user-attachments/assets/d6d4e038-aca5-420d-b909-b4389bc6a7f1)

You can see the java version is not changed and remain java-11. To select the java version as java-17 follow the below steps.
![image](https://github.com/user-attachments/assets/0dc21731-e15d-46f6-b01d-6e81b214fddb)

You can cross verify this, the select java version is java-17 using the command shown below.
![image](https://github.com/user-attachments/assets/ccfcbf5f-5396-47ad-acbc-0ffed8317c30)
