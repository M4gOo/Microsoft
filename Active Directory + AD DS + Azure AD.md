


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
