<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Scenarios In Active Directory</h1>
This tutorial teaches how to reset passwords and unlock accounts using Active Directory.<br />




- <h2>Prerequisites</h2>  
- [On-premises Active Directory Deployed in the Cloud (Azure)](https://github.com/JordanJefferson/configure-ad)

  
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Objectives</h2>  

- Get locked out Of an account
- Unlock Account As Admin
- Password Reset

<h2>Steps</h2>

<h3>(1) Get locked out of an account</h3>  

Purposely fail to login to Client-1 Remote Desktop as "base.wes" 10 times   
![image](https://github.com/user-attachments/assets/b16d61cf-93c8-4515-99a6-5fb4755afd01)   

<br>
<br>

<h3>(2) Unlock Account As Admin</h3>

Login to DC-1 Remote Desktop as admin (mydomain.com\jordan_admin)  

Server manager -> Tools -> Active Directory Users and Computers -> mydomain.com -> _EMPLOYEES -> find "base.wes" and right click -> Properties ->   
![image](https://github.com/user-attachments/assets/929443ac-787b-425d-9876-7fe23dbf98f3)    

Click Unlock account -> OK  
![image](https://github.com/user-attachments/assets/5cf5e5b0-2067-4163-a87b-e3a0045eb702)

<br>
<br>

<h3>(3) Password Reset</h3>  

Server manager -> Tools -> Active Directory Users and Computers -> mydomain.com -> _EMPLOYEES -> find "base.wes" and right click -> Reset password  
![image](https://github.com/user-attachments/assets/aa209b1e-7c4c-491e-8228-2af2f6bb9e51)   

![image](https://github.com/user-attachments/assets/f2e60cad-7fdc-4f66-a2b7-9956230c73af)   

![image](https://github.com/user-attachments/assets/62ddbed4-915e-4e53-84d8-c4bbb95352d4)


