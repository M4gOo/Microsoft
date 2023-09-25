

# Enterprise Deployment 


The enterprise deployment lifecycle is a framework for identifying the processes and tasks required to deploy and manage an organization’s desktops.
<br/>
The lifecycle also includes how you'll support the deployment process, including upgrades, and how it will eventually be retired.

--------

Windows Autopilot, deeply integrated with Azure Active Directory (Azure AD) and Intune, simplifies and personalizes the out-of-the-box (OOBE) user experience. Windows Autopilot joins the device to Azure AD and enrolls it in Intune. Intune automatically applies users’ email, apps, files, preferences, and organization’s security settings without creating custom OS images.

-----------

#### Data Migration

->   Migrate essential data to a cloud or non-local solution before deployment: It's generally easier and safer than continuing the risk and solving the problem after migration. Tools like Known Folder Move (KFM) can help seamlessly migrate local data to the cloud. When cloud solutions aren’t feasible, consider migrating data to network file shares or work folders. You can use features like Enterprise State Roaming to migrate common settings.
<br/>
->   Use in-place upgrades when possible. This process is the recommended practice for deploying upgrades. While re-imaging devices were historically recommended in the past, this is only the case today if there’s a scenario where in-place upgrades aren’t supported.
<br/>
->   Use the User State Migration tool The User State Migration Tool is used when local data or application settings migration is necessary. You can use User State Migration Tool (USMT) 10.0 to streamline and simplify user state migration during large deployments of Windows operating systems. USMT captures user accounts, user files, operating system settings, and application settings and migrates them to a new Windows installation. You can use USMT for both PC replacement and PC refresh migrations.

-----------------

### Plan an application deployment

-> Updates to Windows rarely affect application compatibility; however, they can happen. Most applications will function as expected when upgrading from a previous OS, such as Windows 10, to Windows 11. However, there are typically always some applications (such as Anti-virus) that will require attention.


-------------------

### When employees leave the company, IT will disconnect the device from the network and wipe selective information related to company access. What Mobile Device Manager (MDM) enables IT to selectively remove applications and application data without affecting personal data? 

-> Microsoft Intune is a cloud-based device management technology to secure data users can access on company owned or personal devices. 
\
With Intune, you can manage devices on the network, and selectively remove applications from the device. 
\
In a BYOD scenario, employees may not want to risk their personal data to be on a company network. 
\
Employees should be aware of policies and security requirements before enrolling personal devices.


-----------------
-----------------

#  Windows Editions  

### Examine Windows client editions and capabilities

It's essential that you select the most suitable edition for your organization before you install Windows. The different editions of Windows address the needs of consumers, from individuals to large enterprises. 
\
Windows 11 and previous editions run on several devices or form factors. However, not all editions of Windows can run on all device types.
\
Hardware requirements:
- Win 10  20 GB for 64-bit and 2 GB RAM
- Win 11  64 GB for 64-bit and 4 GB RAM, Trusted Platform Module (TPM) version 2.0.
- Windows will detect most hardware and install the driver to support the device. Many companies producing hardware have their drivers certified at the Windows Hardware Quality Labs and delivered through Windows updates. Otherwise look at manufacturer’s website

-> IT department wants to choose the pace at which it adopts new technology for user devices. It also requires a broad range of options for operating system deployment and device and app management. Which of the following Windows 10/11 editions allows Fabrikam to meet these IT requirements? ENTERPRISE
\
-> Your organization is in the process of migrating users to Microsoft 365 E3. You have a mix of Windows 10 editions deployed. You're required to provide conditional access and SSO from anywhere for the Microsoft 365 E3 users using Domain Join with Azure Active Directory. Which of the following Windows versions will support this requirement?  PRO and ENTERPRISE
\
-> You're the IT Support professional for Contoso, a large enterprise organization that's a Microsoft Volume License customer. Contoso needs to deploy a set of Windows 11 computers for an isolated office that won't be managed for at least six months. Given Contoso's requirements, which of the following Windows 11 editions would be the most suitable for deployment? ENTERPRISE






# ACTIVE DIRECTORY

### Install windows administrative tools

on PC user search on google  Install windows administrative tools, installed we can access the server remotely


### AD Users and Computers

under Domain there folder (organizational unit)
\
once add a computer in computers folder you can manage like permissions, restrictions, security, tells where the computer is in the network

-> Join a computer to the domain 
\
On SERVER

![image](https://github.com/M4gOo/Microsoft/assets/57456345/4a747bd6-2419-4ef9-9ec0-0d2bac60ea8a)

On Computer User -> Type About or system properties or system properties -> Advanced System settings (from -> About or system properties) -> Computer Name TAB -> Change... -> Type computer name as is wrote on domain server AD and select  Member of DOMAIN (domain name is the same as is wrote on AD users and computers

!!! You need administrator credentials 

![image](https://github.com/M4gOo/Microsoft/assets/57456345/aec732fe-93c4-47a1-89e3-89113c66d17a)






