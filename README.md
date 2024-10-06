<h1>Azure Active Directory</h1>

- <b>This tutorial outlines the configuration and observation of Microsoft Azure's Active Directory hierarchy groups</b>

<h2>Environments and Technologies Used</h2>

- <b>Microsoft Azure</b> 
- <b>Azure Active Directory</b>

<h2>Operating Systems</h2>

- <b>Windows 10</b>


<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/ce1f1471-35ca-455a-8cb6-e315d20125c8)
- <b>Navigate to Microsoft Entra ID and create a new user</b>

![image](https://github.com/user-attachments/assets/9cf6d06b-fda4-4005-be21-44aa2bffc441)
- <b>Display name: globalreaderjohn</b>

![image](https://github.com/user-attachments/assets/383d78d4-5b5d-4c04-86f5-ec082247dc54)
- <b>Click globalreaderjohn then assigned roles</b>
- <b>Search for global reader then add</b>

![image](https://github.com/user-attachments/assets/fc334a17-4056-4f13-9e1f-a27ba37154f8)
- <b>Login to globalreaderjohn in Azure</b>

![image](https://github.com/user-attachments/assets/de9c9860-60f2-4c47-981f-6c66c98a2d66)
- <b>Create another user named "subreaderjane"</b>

![image](https://github.com/user-attachments/assets/3bdc915c-1df9-44ed-998c-7cd1e357a9c7)
- <b>Navigate to subscriptions then access control (IAM)</b>
- <b>Click add role assignment then choose reader</b>

![image](https://github.com/user-attachments/assets/55fcc089-c40f-4ae6-95db-358ca0aa69e1)
- <b>Select members then select subreaderjane</b>

![image](https://github.com/user-attachments/assets/5e4f86b5-ae71-4ccf-8704-144e7f153162)
- <b>Login to subreaderjane in Azure</b>

![image](https://github.com/user-attachments/assets/bd9a2e9e-d917-4838-9eec-7d5eb4237618)
- <b>Create another user within Azure Active Directory named "rgcontributordave"</b>

![image](https://github.com/user-attachments/assets/e94149fd-128e-4814-a496-d2a96e00937c)
- <b>Navigate to resource groups and create a new resource group called "Permissions-Tester"</b>
- <b>Region: US EAST 2</b>

![image](https://github.com/user-attachments/assets/38739648-7659-49b6-ab58-59732d572db8)
- <b>Click access control (IAM) then add role assignment</b>
- <b>Select contributor then click privileged administrator roles</b>
- <b>Select rgcontributordave then login to rgcontributordave in Azure</b>
