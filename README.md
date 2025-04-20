 <p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Active Directory Domain Services
- PowerShell
- Command prompt 

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
  <h2> Group Policy Managment Editor </h2>
- Here we will be setting the term for password attempts
- To do that we need open Group Policy Management Editor
- Once there we can ether create domain policy or edit existing
- Computer Configuration-> policy-> Window setting-> Security setting->Account Policy 
  <h2>Step 1</h2>

  ![AD GP- step 2](https://github.com/user-attachments/assets/c7f12a31-1388-4dd0-913f-906c27f20d26)

  <h2>Step 2</h2>

  ![AD GP- step 3](https://github.com/user-attachments/assets/313338db-92e8-402f-aab9-34122db075ab)

  <h2>Step 3</h2>

  ![AD GP- step 4](https://github.com/user-attachments/assets/aed261c4-04e4-46f8-83ce-db60e3ca6a41)

 <h2>Step 4</h2>

 ![AD GP- step 5](https://github.com/user-attachments/assets/c576084c-5440-43e4-a914-a41ad542aba4)

 <h2>Step 5</h2>

 ![AD GP- step 6](https://github.com/user-attachments/assets/3ea6d983-fdf2-41e8-9618-9231bfb29e51)

 <h2>gpupdate /force </h2>



  ![AD GP- step 7](https://github.com/user-attachments/assets/260e0638-df52-4302-b510-6824a95b2a08)

<h2> WE WILL NOW LOCK AN ACCOUNT OUT BE ATTEMPTING THE WORNG PASSWORD MORE THEN 5 TIMES </h2> 


  ![AD GP- step 8](https://github.com/user-attachments/assets/5aefb1f8-6650-4f9e-ae4e-dbd1be34a3f3)

  - Now open Active Directory Users & Computers
  - Go to employees
  - Find user and unlock account
<h2>Find User</h2>

![AD GP- step 9](https://github.com/user-attachments/assets/9afc4af8-6ec9-443a-9e79-b10fdcd51e5e)

<h2>Right click the user and open Properties </h2>

![AD GP- step 11](https://github.com/user-attachments/assets/925fd3ae-8992-425d-b378-ab56e9c126bc)

<h2>Unlock Account and Apply </h2>

![AD GP- step 10](https://github.com/user-attachments/assets/824c6241-f833-4344-92b6-fde235218223)








