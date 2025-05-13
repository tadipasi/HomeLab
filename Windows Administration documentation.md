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


**1. Deploy Windows server 2022 VM in Hyper-V**<br/>
Deploy the Virtual machine in Microsoft Hyper-V and install the Windows Server 2022. The server WinSrv22Proj-DC1 will server as the primary domain controller 

<img width="527" alt="Virtual machine creation" src="https://github.com/user-attachments/assets/816a2eac-8d5b-4a27-85ee-1ad55165ad54" />

<img width="771" alt="install windows server 2022" src="https://github.com/user-attachments/assets/ef296d1c-5eb2-4ce1-a82b-727bb91fa1f3" />

<img width="960" alt="Confirmation of creation" src="https://github.com/user-attachments/assets/ba0e3ee7-22d7-430b-ae81-e653ec55daeb" /> 

<br/>

