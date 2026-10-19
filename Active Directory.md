WIndows Server Dashboard
- go to Manage and add Roles and Features
- <img width="192" height="177" alt="image" src="https://github.com/user-attachments/assets/9b9c63be-84ae-473d-a55c-7ab8b048dd5c" />
- <img width="394" height="283" alt="image" src="https://github.com/user-attachments/assets/aeda16ac-5a6f-4412-9eec-dd71a076cf9d" />
Next
- <img width="394" height="281" alt="image" src="https://github.com/user-attachments/assets/eacb3fc2-dc9d-4074-9ef4-da108cfdaeeb" />
- Role based or feature based selection
- <img width="391" height="279" alt="image" src="https://github.com/user-attachments/assets/5c9d5d45-bb3b-4d3f-9ff9-b3cca56911e8" />
Next
- <img width="392" height="285" alt="image" src="https://github.com/user-attachments/assets/092e913c-bdee-4f39-8259-24b8ab9dbf22" />
- Select Active Directory and Domain Services
- Add roles and features
- <img width="396" height="280" alt="image" src="https://github.com/user-attachments/assets/d5dd271c-52bf-4a3e-b3c6-f9bfe22264f8" />
- Select Group Policy Management
- <img width="494" height="360" alt="image" src="https://github.com/user-attachments/assets/8ff28bd3-d3c4-452b-a405-9831e5a46707" />
- Install
- <img width="440" height="310" alt="image" src="https://github.com/user-attachments/assets/3f751616-25d1-4482-acad-52212974c861" />
- <img width="239" height="205" alt="image" src="https://github.com/user-attachments/assets/4a5fae83-5e83-4831-811c-37d3d2f97d92" />
- Promote this server to domain controller
- <img width="416" height="314" alt="image" src="https://github.com/user-attachments/assets/3adb3589-c0d0-4e43-9977-99522e80fe26" />
- select "new forest" and create root domain name. I have created "learn_microsoft.local"
- <img width="422" height="308" alt="image" src="https://github.com/user-attachments/assets/20304f88-b336-40bf-bd82-73adcb1c2a0a" />
- Drop down and select window server version.
- Create password
- <img width="419" height="308" alt="image" src="https://github.com/user-attachments/assets/1a6aa6a9-b4cc-4bb0-a314-265055db2a9c" />
- next
- <img width="418" height="305" alt="image" src="https://github.com/user-attachments/assets/511e2671-42f2-40c6-9711-79d23837254e" />
- domain name "Learn_microsoft"
- <img width="416" height="304" alt="image" src="https://github.com/user-attachments/assets/4dbbe1fd-24ad-4210-8755-b2d6ba9b658b" />
- next
- <img width="415" height="305" alt="AD" src="https://github.com/user-attachments/assets/008370f1-e6d5-4b55-ad9f-1e53ae18e6ef" />
- install
- reboot device
- go to local server and check the details (Domain)
- <img width="1052" height="281" alt="image" src="https://github.com/user-attachments/assets/96135c6a-a3ca-447a-821f-9cf89ba3aa6d" />
- <img width="936" height="427" alt="image" src="https://github.com/user-attachments/assets/a1679e1f-d5ef-42e6-80a1-3871a7304a93" />
- AD DS is installed.


- Troubleshoot
- if you unable to view AD DS on Dashboard - Roles and Server Group
- Open Powershell as admin and run below command.
- <img width="300" height="86" alt="image" src="https://github.com/user-attachments/assets/394c5ef8-b34e-46be-be2b-c467e363be27" />
- "Get-WindowsFeature AD-Domain-Services"
- you will see
- <img width="454" height="142" alt="image" src="https://github.com/user-attachments/assets/f9a0d7f5-d205-48f5-bcef-2bd2a2fe530f" />
- AD DS will be visible on dashboard.
  

