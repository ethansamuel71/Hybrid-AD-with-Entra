# Hybrid-AD-with-Entra
Making a home lab that syncs an on-prem users in an Active Directory environment with Entra ID using Microsoft Entra Connect.

## How it will work:

- DC01 (Windows Server 2022) running AD DS and DNS for the on-prem domain
- 
- SYNC01 will run Entra Connect
- 
- Entra Connect reads users and groups from on-prem AD and syncs them to a Microsoft Entra ID tenant on a recurring sync cycle
- 
- **Password Hash Sync** lets synced users sign in to cloud services with their on-prem credentials
- 
- Changes made on-prem like disabled accounts and new users go to the cloud automatically


