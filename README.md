<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Unlocking Accounts on Active Directory (Azure)</h1>
This tutorial outlines the step by step process of unlocking an account on Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Step-by-Step Guide to Unlocking a User Account</h2>

- Step 1- Open Active Directory Users and Computers
- Step 2- Open your employee's file
- Step 3- Find the locked user's account
- Step 4- Click the unlock box to unlock the account


<h2>Guide to Unlocking a User Account</h2>

<p>
<img width="1918" height="1070" alt="Screenshot 2025-07-19 123513" src="https://github.com/user-attachments/assets/2811d147-127a-453f-ad7c-6c0213695eed" />


<p> If an employee is experiencing login issues due to a locked account, follow the steps below to unlock their account in Active Directory and restore access. </p>

<br />

<p>
<img width="1919" height="1079" alt="Screenshot 2025-07-12 120837" src="https://github.com/user-attachments/assets/cfedd030-a1b0-4626-bee9-0f0c98fe1df7" />


<p>On your computer, click the Start menu, navigate to 'Windows Administrative Tools', and then select 'Active Directory Users and Computers'. </p>

<br />

<p>
<img width="1502" height="874" alt="Screenshot 2025-07-19 123708" src="https://github.com/user-attachments/assets/741619bc-9951-4a28-af94-332b3b9ad67f" />

<p> Once Active Directory Users and Computers (ADUC) is open, navigate to the organizational unit (OU) where your employee accounts are stored. To locate a specific user more efficiently, right-click the OU, select 'Find', enter the employee’s name, and then click on their name from the search results. </p>

<br />


<p>
<img width="663" height="785" alt="Screenshot 2025-07-19 123729" src="https://github.com/user-attachments/assets/fffd0b96-436e-4f99-8f7f-29b3254f14e2" />


<p>In the employee's account properties window, navigate to the 'Account' tab. If the account is locked, you will see a message indicating that it is locked out. Check the box labeled 'Unlock account', then click 'Apply' and 'OK' to complete the process. </p>

<br />


<p>
<img width="734" height="730" alt="Screenshot 2025-07-19 123842" src="https://github.com/user-attachments/assets/005d2c77-e168-4c3b-b993-c285e8527717" />


<p>After unlocking the account, be sure to inform the employee that their access has been restored and they can now log in. </p>

<br />
</p>


<br />
# Unlocking-Accounts-on-AD
