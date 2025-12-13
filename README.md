## Brief Introduction

Detail-oriented I.T. professional with a strong academic background in Computer Science and Information Security. CompTIA A+, Network+,
Security+, CySA+ certified. Experienced in supporting users, resolving technical issues, and maintaining a secure digital environment. Proven ability to manage hardware and software troubleshooting in fast-paced settings. Committed to delivering excellent technical support and user education.

<a href="https://linkedin.com/in/pierretheophan/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>




## Objective

|  Project                                         | Objectives         |
|-----------------------------------------------|----------------------------|
|Active Directory Home Lab| Built a Windows Server domain controller to simulate enterprise identity management. Focused on creating organizational units, managing users, and configuring group security for realistic IT administration.|
|Group Policy Management Home Lab| Designed and tested GPOs to enforce security, access restrictions, and desktop standardization across an Active Directory domain. Validated policy inheritance and minimized configuration conflicts to mirror enterprise environments.|
|Ticketing System Home Lab (SpiceWorks)| Simulated real-world IT support operations by creating, categorizing, and resolving tickets. Practiced escalation, SLA tracking, and email integration to model enterprise help desk workflows.|
|Remote Desktop Support Lab| Configured and tested Remote Desktop Protocol (RDP) to simulate real-world remote IT support. Enabled Remote Desktop on a client machine, added a support account with proper permissions, and established secure connections from a help desk workstation. Validated firewall rules and IP addressing to ensure reliable remote access in a lab environment.|

## Skills

|  Skill                                         | Associated Project         |
|-----------------------------------------------|----------------------------|
| Account Lockout Policy:  Open Group Policy Management Editor and navigate to: Computer Configuration → Policies → Windows Settings → Security Settings → Account Policies → Account Lockout Policy. Then Double-click “Allow Administrator account lockout” → Select Enabled → Click OK. |<a href="https://github.com/user-attachments/files/23831023/Screenshot.2025-08-30.at.9.03.47.PM.7.59.28.PM.tiff">Group Policy Management Lab</a> |
| Drive Mapping Step 1: Open Group Policy Management Editor, then go to: Computer Configuration → Preferences → Windows Settings → Drive Maps. Right-click in the Drive Maps pane → select New → Mapped Drive. In the New Drive Properties window, set: Action: Update, Location: \\servername\folder, Drive Letter: Select Use and choose a letter (e.g., E:) Click Apply → OK.)| <a href="https://github.com/user-attachments/assets/f022f6c9-5e30-4ece-ac1a-34aabf8602f6">Group Policy Management Lab</a>|
| Drive Mapping Step 2: Verify the mapped drives appear under Drive Maps. You should now see the drive letters (e.g., A: and E:) listed with the correct paths and settings.| <a href="https://github.com/user-attachments/assets/e49611d6-6356-4a43-97d3-c481e49a3b72">Group Policy Management Lab</a>|
| Password Policy Step 1: Open Group Policy Mangement. Right click your domain (e.g., NetworkerChuck.local) → Create a GPO in this domain and Link it here. Name it Password Policy Test, then click Ok.| <a href="https://github.com/user-attachments/assets/aea7c6db-d7b1-4e49-99fd-0433c07d3d0e">Group Policy Management Lab</a>|
| Password Policy Step 2: Right-click Password Policy Test → Edit. Navigate to: Computer Configuration → Policies → Windows Settings → Security Settings → Account Policies → Password Policy. Double-click Minimum password length, check Define this policy setting, and set it to 12 characters. Click Apply → OK.| <a href="https://github.com/user-attachments/assets/25d6ca3a-c9cb-45ae-8ab1-11dee942f6c8">Group Policy Management Lab</a>|
| Removable Storage Access Step 1: Open Group Policy Management. Right-click your domain (e.g., NetworkerChuck.local) → Create a GPO in this domain, and Link it here. Name it Disable USB devices, then click OK.| <a href="https://github.com/user-attachments/assets/3cdc8b39-088c-441f-bccd-803c56946541">Group Policy Management Lab</a>|
| Removable Storage Access Step 2: Right-click Disable USB devices → Edit. In the Group Policy Management Editor, go to Computer Configuration → Policies → Administrative Templates → System → Removable Storage Access. Double-click All Removable Storage classes: Deny all access, select Enabled, then click Apply and OK. | <a href="https://github.com/user-attachments/assets/222d5589-935e-444d-afdf-0d3239136e61">Group Policy Management Lab</a>|
| Restrict Access To Control Panel Step 1: Open Group Policy Management. Right-click your domain (e.g., NetworkerChuck.local) → Create a GPO in this domain, and Link it here. Name it Restrict Control Panel, then click OK.  | <a href="https://github.com/user-attachments/assets/713b32b3-33a6-4bd5-b9eb-fc8e8820a1f1">Group Policy Management Lab</a>|
| Restrict Access To Control Panel Step 2: Right-click Restrict Control Panel → click Edit. In the Group Policy Management Editor, navigate to: User Configuration → Policies → Administrative Templates → Control Panel. Double-click Prohibit access to Control Panel and PC settings, select Enabled, then click Apply and OK.| <a href="https://github.com/user-attachments/assets/a9b6bc7b-15b0-4bff-81a3-363062f4a28a">Group Policy Management Lab|
| Created Users: Open Active Directory Users and Computers → Navigate to your OU (e.g., NetworkerChuck.local → USA → Users). Right-click Users → select New → User. Enter the user details shown in the form: First name, Last name, User logon name, and pre-Windows 2000 logon name. Click Next to continue the user creation process. | <a href="https://github.com/user attachments/assets/23831916-a9f7-4e2c-b0e9-aa38a4478063">Active Directory|
| Created Security Groups: In Active Directory Users and Computers, open the New Group window, enter the Group name, add a description if needed, select the Group Scope (Domain Local / Global / Universal) and Group Type (Security / Distribution), then click OK to create the group.| <a href="https://github.com/user-attachments/assets/5c7eb8c2-4018-4d32-b2d2-0610cbd04864">Active Directory|
| Created Organizational Units: In Active Directory Users and Computers, navigate to: NetworkerChuck.local → USA → Right-click → New → Organizational Unit. Enter the OU name, ensure Protect container from accidental deletion is checked, then click OK.| <a href="https://github.com/user-attachments/assets/487686ff-b7bc-458c-805e-20d112879945">Active Directory|
| Creating a Ticket: Open Spiceworks Help Desk → Click New Ticket. Fill in the required fields: Organization → select NetworkerChuck Contact → choose the user submitting the issue Summary → enter the issue title (e.g., “Monitor isn’t working (Computer01)”) Description → provide detailed information about the problem and availability Assignee → select the technician Priority → choose the appropriate level (High / Medium / Low) Category → choose the issue type (e.g., Hardware) (Optional) Attach a file if needed → click Create to finalize the ticket.|<a href="https://github.com/user-attachments/assets/8781a7fc-a36c-4092-a1cc-97017a03700b">Ticketing System</a>|
| Ticket Closure Checklist: Open the resolved ticket in Spiceworks Help Desk, review the conversation history to confirm the issue is fixed, document the resolution in an internal note, verify the correct assignee, priority, and status, and prepare the ticket for closure after user confirmation.| <a href="https://github.com/user-attachments/assets/4c6fd24f-b249-4cb0-bde9-93b5f6ed5b24">Ticketing System</a>|
| Ticket Escalation Process(Step 1): Open the Spiceworks Help Desk dashboard and select the ticket titled “Can’t access Financial Database (FinDB)”. Review the ticket details, including the user request, priority, category, assigned technician, and internal comments indicating the need for escalation and read-only database access. | <a href="https://github.com/user-attachments/assets/e36bb1be-0905-488c-8005-f5bd8e66e889">Ticketing System</a>|
| Ticket Escalation Process(Step 2): Click the Edit (pencil) icon on the selected ticket. Update the ticket summary and description if needed to clarify the issue, confirm escalation details, and then click Save to apply the changes and continue the escalation workflow. | <a href="https://github.com/user-attachments/assets/11835fd4-1492-4aad-999d-c016765743cd">Ticketing System</a>|
|RDP (Step 1): | <a href="https://github.com/user-attachments/assets/7344cd63-5fb8-461e-91c6-302cce547265">Remote Desktop Support</a>|
|RDP (Step 2): | <a href="https://github.com/user-attachments/assets/195dbfe1-f8e4-493c-9e51-2c0dd6f8823c">Remote Desktop Support</a>|
|RDP (Step 3): | <a href="https://github.com/user-attachments/assets/6c6d1b3e-1c30-474d-951b-89a47141b44d">Remote Desktop Support</a>|
|RDP (Step 4): | <a href="https://github.com/user-attachments/assets/ade8cbc6-7491-4ab2-9bda-6bd660b7703b">Remote Desktop Support</a>|
|RDP (Step 5): | <a href="https://github.com/user-attachments/assets/d88a5bbb-4de2-4f7e-a533-79ff31fe939a">Remote Desktop Support</a>|
|RDP (Step 6): | <a href="https://github.com/user-attachments/assets/752eaec8-4ce0-4ffb-ba30-6b400678e442">Remote Desktop Support</a>|
|RDP (Step 7): | <a href="https://github.com/user-attachments/assets/1b7e3d87-971d-457b-a877-fff0ff7b455c">Remote Desktop Support</a>|




## Certifications

<div>
<img src="https://img.shields.io/badge/-CySA%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-Network%2B-007ACC?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-A%2B-4D4D4D?&style=for-the-badge&logo=CompTIA&logoColor=white" />
</div>

## Projects
- Group Policy Management Lab
- Active Directory Lab
- Ticketing System (SpiceWorks) Lab
- Remote Desktop Support Lab

