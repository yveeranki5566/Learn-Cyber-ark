## Learn-Cyber-ark


![image](https://github.com/user-attachments/assets/47f25d54-3ace-4909-baf4-cf5024b5ca09)

**Policies**

![image](https://github.com/user-attachments/assets/8352e331-3041-43b4-8ca3-b9cce9f381ee)

**Policy by platform** 

![image](https://github.com/user-attachments/assets/7a8d1f8e-ce46-410c-897a-b8b13e96325c)

**Access control safe**

![image](https://github.com/user-attachments/assets/c0f6a502-88de-40c4-8d8d-8acf0a2ddc05)


**Create exception**

![image](https://github.com/user-attachments/assets/bf8a6ca8-6b71-45e2-96ad-c40e4ec88521)

**Exception in mqsql platform**

![image](https://github.com/user-attachments/assets/1ca6b01b-068c-486b-b8fd-986a72a4d377)

**After cpm installation on pvwa server**

![image](https://github.com/user-attachments/assets/b847bc60-a6bb-4c0f-a20d-97096ef1eeda)

![image](https://github.com/user-attachments/assets/eea90b21-865f-49ba-914f-9314db30b811)

**LDAP integration**

![image](https://github.com/user-attachments/assets/ebb06ac1-7b88-4f38-ba25-88a48d4070c5)

![image](https://github.com/user-attachments/assets/ef44f489-6297-4e0e-ae1c-cb407f036fd5)

![image](https://github.com/user-attachments/assets/f30b87f1-6ed3-4fa6-844a-749edc005513)

**mapping**

![image](https://github.com/user-attachments/assets/1788bacc-aae5-40de-a98a-367300ae59b3)

**cyber ark administrators**

![image](https://github.com/user-attachments/assets/38491597-ff67-432f-b46c-6545d5059eb0)

**cyber ark auditors**

![image](https://github.com/user-attachments/assets/b880c402-738f-4b7d-a4fa-b811e5b4a50b)

**cyber ark users and final save**

![image](https://github.com/user-attachments/assets/80dfa8ee-08ba-4fd0-8c98-2e84f0924514)

**Active directory users for the domain**

![image](https://github.com/user-attachments/assets/ea560e0e-56ac-4d93-af20-70ea9f95aa54)

**Add users to cyberark user group in AD**

![image](https://github.com/user-attachments/assets/dae3f0af-5d7c-401b-af54-0a5f7856d398)

**Add user to cyber ark admin group in AD**

![image](https://github.com/user-attachments/assets/2dd1f59a-dc24-4109-a719-4bfc7fd19bca)

**Add user to cyber ark auditor group in AD**

![image](https://github.com/user-attachments/assets/b9287d61-8370-4c6d-bfbb-bf75fc2d481a)

**Login to pvwa with user credentials.**

![image](https://github.com/user-attachments/assets/4e80050d-2972-45ed-b063-b99126f59099)

**User dashboard after logging in**

![image](https://github.com/user-attachments/assets/22a5a1c8-ac7b-415e-8bf8-2728b8865997)

**Admin dashboard:**

![image](https://github.com/user-attachments/assets/56b9b8f5-721e-408b-8138-b74821f12e33)

**Use case scenario of cyber ark:**

**Secure two privileged accounts in cyberark rotating their password every 30 days.**

**Lets create two privileged accounts in the active directory and add them to Domain admin group to make them highly privileged accounts.**

![image](https://github.com/user-attachments/assets/32ff1932-7e0d-441b-b426-4cfc3af4ff8e)

![image](https://github.com/user-attachments/assets/b2188b97-32fa-4bdb-a3b5-8fe5828d1809)

![image](https://github.com/user-attachments/assets/639e33c4-6cd5-481a-a1c3-3cf4a9b6d11c)

**Create an exception in the master policy for windows domain account as per the requirement.**

![image](https://github.com/user-attachments/assets/bb1f6133-488d-4822-92f8-0270bb8b100f)

![image](https://github.com/user-attachments/assets/5c7ae0a3-0c30-459b-a3bd-afe5aae632dc)

**Next add a safe to on board the privileged accounts to cyber ark.**

![image](https://github.com/user-attachments/assets/7865bf7d-cbf5-4de7-9d39-8b291763933b)

**Next steps are followed to add an accountin cyberark.**

![image](https://github.com/user-attachments/assets/e1e2068f-6a6f-48f6-8440-73cfc29f9bb6)

**select the safe to store accounts.**

![image](https://github.com/user-attachments/assets/e1eddd0a-7d0d-49a2-a9ad-955e4f5326ea)

**Add the account by filling out IP Address of the domain controller on which the accounts are created in the active directory.**

![image](https://github.com/user-attachments/assets/9445a00e-0072-4a2c-b63c-9a2597c30941)

**Similarly add another privileged account.**

![image](https://github.com/user-attachments/assets/72a0db32-9a33-4783-9934-06f0dbeda01b)

**Use case scenario 2: There are two users and one manager in a team who would like to access the created privileged accounts in cyber ark. **

**In order to access the cyber ark , we will be adding these users to the cyber ark users group in the active directory.**

![image](https://github.com/user-attachments/assets/6f4c2d89-07d7-46f0-8de9-62b418b38c0a)

**Next , the requirement in this case is the manager should be able to see all the accounts in the cyber ark safe, so next step is to allow access for this member at safe level.**

**Give access permissions to manager to all the accounts in the safe as below.**

![image](https://github.com/user-attachments/assets/23bf1164-eae8-41a2-9431-e3e919c3eebb)

**Lets add user1 and user2 to the safe but without safe level permissions.**

![image](https://github.com/user-attachments/assets/9755ccf7-61a6-4d0f-ae09-c78db5a3cd2f)

![image](https://github.com/user-attachments/assets/18c1d5f3-01ab-470e-a1e6-3f630eb913d5)

![image](https://github.com/user-attachments/assets/e668d2d9-bda0-441d-9c59-b4791ea1af80)

**Now we have to give access of PA1 privileged account to user1 but not other accounts, so for that follow the below steps.**

![image](https://github.com/user-attachments/assets/2710ac90-9e85-4688-aa4b-3fcc02395958)

**Set access permissions of PA1 privilege account to user1 as below.**

![image](https://github.com/user-attachments/assets/d90632b6-0249-4aa6-81bf-6ac4ec03b116)

**Similarly allow access to PA2 for user2.**

![image](https://github.com/user-attachments/assets/d051d3ef-9c70-44b8-b3e1-a3833bf542eb)

**Now lets check if these configurations are working by logging in as manager1, user1 and user 2 and observe the cyber ark dashboards respectively.**

**For manager account all the privileged accounts on the safe are visible and can see the passwords as well.**

![image](https://github.com/user-attachments/assets/21b108c4-a4cf-435c-9422-9153293d04df)

![image](https://github.com/user-attachments/assets/0806c89a-84a8-40bb-9519-614d6eb6ec6b)

**Where as user1 and user2 only have access to assigned privileged accounts.**

![image](https://github.com/user-attachments/assets/41f94a7d-5584-4bfc-b90f-855d8cef7fd2)

![image](https://github.com/user-attachments/assets/d6a0937c-6513-4c82-9bd3-68856376080c)

**Next deploy PSM, privilege session manager and test its functionality.**

**Enable monitoring and isolation policy in the master policy section for all the platforms.**

![image](https://github.com/user-attachments/assets/cb4bf462-b13d-423d-9694-3051bc30872c)

![image](https://github.com/user-attachments/assets/c49dedf6-5cb3-4d01-b9b4-d92842d82197)

**Now, we have PSM in place, user1 can connect to PA1 without showing the password , and the user activity will be monitored and recorded.**

**Login with user1 and click on connect and next give the details of the server to connect, click on the downloaded rdp file and connect.**

![image](https://github.com/user-attachments/assets/aabaa6af-0577-4779-9a6d-5a1861fa2b5d)

![image](https://github.com/user-attachments/assets/e416c8be-dbec-49c8-92fb-cabdc36275a2)

![image](https://github.com/user-attachments/assets/4341528b-0269-4c95-bb36-fc9345b5e152)

**Now, an auditor can see the recorded session of all the activities performed on PA1 account by user1 by logging into cyberark and check the logs.**

![image](https://github.com/user-attachments/assets/dffa5e24-553c-47de-8e9e-812169722df8)

**Lets open the log file and check now as an auditor.**

**Both the activity log and recirded session and available for auditing purpose.**

![image](https://github.com/user-attachments/assets/80838819-3218-4a13-8e0d-ce5564a776bc)

**Upload priveleged accounts using Password Upload Utility:**

**Lets upload selected five privileged accounts below into cyberark, by creating a custom password csv file.**

![image](https://github.com/user-attachments/assets/d9b463dc-a7c5-4625-98bd-4757109fb0a0)

<img width="983" alt="image" src="https://github.com/user-attachments/assets/5e0e7a2d-8040-4326-9d50-4071acdb2981">

![image](https://github.com/user-attachments/assets/5bf93d2d-1755-4420-81ce-45ac3b0b1dc7)

**Lets check on the accounts page in cyber ark if the accounts have been uploaded or not.**

![image](https://github.com/user-attachments/assets/38da22b3-9988-4c4f-b98f-c00c3cba85af)

**Reports:**

**Login as auditor and generate reports.**

**1. Privileged accounts Inventory report:**

   <img width="863" alt="image" src="https://github.com/user-attachments/assets/396b54dc-8de6-457e-836a-8477cfd5ef5a">

   <img width="929" alt="image" src="https://github.com/user-attachments/assets/67c54878-b947-4d6a-b4cb-9e781e9efff0">

   <img width="1919" alt="image" src="https://github.com/user-attachments/assets/ae55c2fd-c007-4a13-80cf-869a9666324f">

   <img width="1361" alt="image" src="https://github.com/user-attachments/assets/748bd6a2-d3a0-490d-8ecd-15f791e4a6a3">

**2. Privileged accounts Compliance Status Report:**

   <img width="1061" alt="image" src="https://github.com/user-attachments/assets/b39e3ef9-4fe9-42e6-9267-ff52d5fe598f">

   <img width="1604" alt="image" src="https://github.com/user-attachments/assets/22dfef7c-a8e5-47af-8b5b-2facda8e9a9a">

**3. Entitlement Report:**

   <img width="1246" alt="image" src="https://github.com/user-attachments/assets/a2b20e22-02de-4ad0-b746-44bb57c6308b">

   <img width="1919" alt="image" src="https://github.com/user-attachments/assets/3e140184-1cdf-47a9-b05e-421f098d2ad9">

   <img width="1772" alt="image" src="https://github.com/user-attachments/assets/08cdc311-b3d5-4b94-a459-26ecd7fcd6f9">

**4.   Activity Log Report:**

<img width="580" alt="image" src="https://github.com/user-attachments/assets/0e2d81ce-b3a3-4489-bc82-725645214f45">

<img width="863" alt="image" src="https://github.com/user-attachments/assets/83de6761-277e-4e9d-95fd-f3bcd162b1ca">

<img width="1305" alt="image" src="https://github.com/user-attachments/assets/906fe3cc-b8a3-4740-898c-37ad0a6042d5">

**Lets filter User1 activity:**

<img width="1445" alt="image" src="https://github.com/user-attachments/assets/17ffa5c7-158c-44e5-821c-a3892ae34ff8">

**Next check what kind of activity is done on Privileged account PA1:**

<img width="1387" alt="image" src="https://github.com/user-attachments/assets/42d36463-d64d-4310-8f2c-057028a8f697">

**Password Management issues solution : Reconciliation account.**

1. **Add a reconciliation account and associate it with a privileged account so that when verfification fails, CPM uses reconciliation account to login and reset the password to resolve the issue.**

 <img width="1562" alt="image" src="https://github.com/user-attachments/assets/d39bdace-d415-46fd-8618-6f5e5d195237">

 <img width="1508" alt="image" src="https://github.com/user-attachments/assets/3a9bfca2-36fe-438d-b846-df87119f20c7">

**Connectivity Issues like network path not found:** 
There reasons might be that the target system is under maintenance or shutdown, or Target system is decommissioned or out of service, or there could be firewall restrictions when the target server is not on the same network.

The resolutions for the above problems are re triggering the password management operation when the server is up and running, remove the account from cyber ark when it is no longer in use, Allow firewall ports (exceptions) from CPM to the target system. 

**Unknown issues**:

First the standard approach for unknown issues would be to check the logs at the below location.

C:\Program Files (x86)\CyberArk\Password Manager\Logs.

If the logs dont give us enough details, increase the debug level of logs in the configuration settings in PVWA server.

![image](https://github.com/user-attachments/assets/5d3e3f85-c854-4546-8a96-078b284d9024)

**Disaster Recover ( DR Vault)**:
A fresh replica vault is built, and configure auto replication between the primary vault and the newly created DR Vault. Configure all the components (PVWA, PSM, CPM) to communicate to DR in case the primary vault is impacted.

![image](https://github.com/user-attachments/assets/e576e61d-fb98-4d00-ae07-837661adf515)

Install DR utility which automatically login into primary vault and pull the data.

Primary Vault settings: 

![image](https://github.com/user-attachments/assets/4ba76534-9b28-45e9-bf4b-7ef98c1f4150)

![image](https://github.com/user-attachments/assets/f367575f-e6de-4020-8c69-7e442449ef02)







 


























































