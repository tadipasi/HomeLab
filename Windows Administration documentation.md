**Windows Server 2022 Active Directory Deployment.**

Summary <br/>
Demonstrating the deployment of an Active Directory domain using Windows Server 2022 within a Virtualizated environment. Implementing redundancy through replication

Objectives 
1. Deploy a Windows Server 2022 VM in Hyper-V
2. Assign static IP address to the server
3. Promote the **WinSrv22Proj-DC1** as the Domain controler
4. Configure Organizational Units and user accounts
5. Configure Group Policy Objects for user management
6. Implement folder redirection for user profiles
7. Set up drive mapping to centralized shared folers
8. Deploy the backup Windows Server 2022 VM in Hyper-V
9. Assign the static address to the secondary machine
10. Join the **WinSrv22Proj-D22** to the domain and promote it as a backup Domain controller
11. Test failover and AD replication

<br/>
<br/>
<br/>
<br/>


**1. Deploy Windows server 2022 VM in Hyper-V**<br/>
Deploy the Virtual machine in Microsoft Hyper-V and install the Windows Server 2022. The server WinSrv22Proj-DC1 will server as the primary domain controller 

<img width="527" alt="Virtual machine creation" src="https://github.com/user-attachments/assets/816a2eac-8d5b-4a27-85ee-1ad55165ad54" />

<img width="771" alt="install windows server 2022" src="https://github.com/user-attachments/assets/ef296d1c-5eb2-4ce1-a82b-727bb91fa1f3" />

<img width="960" alt="Confirmation of creation" src="https://github.com/user-attachments/assets/ba0e3ee7-22d7-430b-ae81-e653ec55daeb" /> 

<br/>
<br/>
<br/>
<br/>

**2. Assign static IP to the server**<br/>
Assigned static IP address to the server 

<img width="1025" alt="statically assign IP address" src="https://github.com/user-attachments/assets/645b9ab4-156c-4e8d-98c7-7b5982d806f4" />

<br/>
<br/>
<br/>
<br/>

**3 Add the Active Directory Domain Services role to the server and promote the server to primary domain controller**

<img width="1027" alt="installing active directory services" src="https://github.com/user-attachments/assets/7c9d7555-321b-4b25-81e4-76962a2e790b" />

<img width="1027" alt="promote to DC and create new domain" src="https://github.com/user-attachments/assets/a6a9ae46-bca3-49b5-a200-cc02feb17157" />

<img width="584" alt="confirmation of the domain" src="https://github.com/user-attachments/assets/340d9145-4246-4550-b53f-04c2592cf804" />


<br/>
<br/>
<br/>
<br/>

**4. Configure Organizational Units and user accounts**

<img width="635" alt="create organizational unit " src="https://github.com/user-attachments/assets/96aff358-8bbb-426a-9bf6-d63634ccdf3e" />

<img width="577" alt="create a domain user" src="https://github.com/user-attachments/assets/a99e5ca1-21c8-4cf3-929a-e8127a3200db" />

<br/>
<br/>
<br/>
<br/>

**5.**


<br/>
<br/>
<br/>
<br/>

**6.**

<br/>
<br/>
<br/>
<br/>

**7.**

<br/>
<br/>
<br/>
<br/>


**8.**

<br/>
<br/>
<br/>
<br/>


**9.**
<br/>
<br/>
<br/>
<br/>

**10.**
<br/>
<br/>
<br/>
<br/>

**11.**
<br/>
<br/>
<br/>
<br/>

**12.**
<br/>
<br/>
<br/>
<br/>







