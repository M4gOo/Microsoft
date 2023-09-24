

# Office 365

is combined the core productivity apps such as Word, Excel, PowerPoint, OneNote, Outlook, etc., and the collaboration and communication services such as Microsoft Exchange, SharePoint, and Skype for Business. 

Office 365 gives different licenses. When creating a user (using Microsoft 365 admin center) on Product step, In the Apps option you can remove/add access, this user it will be shown in Azure AD admin center, but with more features, technical details to manage
</br>
In the optional settings is possible to give specific admin permissions
</br>
to login use login.microsoft.com
\
At the end of creating a user, it is possible to create a template

### Microsoft 365 admin center dashboard

#### Users tab in Microsoft 365 admin center dashboard
It is possible clicking in the user and straightaway reset password, block sign in and so on
\
in devices you can set up mobile phone to check for example emails
\
can make some changes in email, like out of office, automatic replies



### ONEDRIVE
\
Everything you create on Office 365 it is saved automatically in OneDrive, this is backup
\

### DELETED - ONEDRIVE

Ask user to go to the onedrive and check the recycle bin

![image](https://github.com/M4gOo/Microsoft/assets/57456345/611ed20d-33a1-43e9-86db-2078a5e7228b)

if it is empty the recycle bin, go to Microsoft 365 admin center > active users > select the user > select onedrive > create a link to files > then click on recycle bin. If it is not showing follow steps below (sharepoint)

![image](https://github.com/M4gOo/Microsoft/assets/57456345/6068eabf-9ea6-4b86-a291-3ac35802d576)

Then go to the SharePoint admin center > More Features > under user profiles click on Open > select Manage User Profile > type user name in Find profiles > found the user click on the drop down arrow and select Manage Personal Site > Under Site Colletion Administrator select Recycle bin

![image](https://github.com/M4gOo/Microsoft/assets/57456345/13b5a895-3011-4827-ab66-e08cfa51ad0a)

then select the file and Restore 


Another way to revocer is under user recicle bin at bottom there is a Second-stage recycle bin, then select the file and Restore.

![image](https://github.com/M4gOo/Microsoft/assets/57456345/b789bcf7-3a80-45a4-9bf6-b4033c08da84)


### SHARE POINT

Organizations use Microsoft SharePoint to create websites. You can use it as a secure place to store, organize, share, and access information from any device.

When creating a group in MO365 it will create a group for exchange and sharepoint (this is like facebook, discord page) services

![image](https://github.com/M4gOo/Microsoft/assets/57456345/a25eacb0-9248-45dc-9844-35828b66e67f)



### TEAMS
\
Team is just a group chat, messaging app for your organization
\
if it is not showing in the office 365 try to type in the url teams.microsoft.com, if  showing 'You are missing out' Ask the admin to enable teams.
\
As a Administrator go to MO365, select the user which is having problem, then  Licenses and app look at for Team and enable in Apps drop box arrow


### Exchange
\
A Microsoft Exchange account is a work or school email account
\
ISSUE: not received the email (user complaining)
\
Go to Microsoft 365 admin center dashboard > Exchange admin center > mail flow > message trace > start a trace (button), then fill up the itens, after that will see if it was delivered, time, etc

![image](https://github.com/M4gOo/Microsoft/assets/57456345/205d3e62-c8c7-4627-a2c2-f308194947ca)

#### SHARED MAILBOX - EXCHANGE 
ADD: in users tab in Microsoft 365 admin center dashboard, select a user and add a manager (this is helpful when they work in the same department, helps to get email from the customers - they will have shared email);
\
in exchange admin center > recipients > mailboxes > add shared mailbox > Fill out all informations required > create
\
Give permissions to the users in the shared mailbox: click on the sharedmailbox > under mailbox permissions click manage mailbox delegation > then edit the permissions 

![image](https://github.com/M4gOo/Microsoft/assets/57456345/16e0a6da-7164-4f73-b2c1-3fd5fe204f5e)

In the outlook for every user add shared folder, add the email for the department

![image](https://github.com/M4gOo/Microsoft/assets/57456345/5fa2c775-aaaf-47f8-b4d3-4cad1be5d0f9)



# Microsoft 365 

When you assign M365 to your company it will create a Domain, this is different from the domain  created in server 2012 AD, for example.

is a cloud-based service that includes the same Office apps and services, plus Windows 10, and Enterprise Mobility + Security

isn't exactly an operating system and isn't installed on a PC like Windows. Windows 365 is a cloud-based service that automatically creates a new type of Windows virtual machine

securely streams your Windows desktop, apps, settings, and content from the Microsoft cloud to a Cloud PC so you can access a personalized Windows 10 or Windows 11 experience from any Windows, iOS, or Android device. 

With a Cloud PC, Windows evolves from a device-based operating system (OS) to hybrid personalized computing

To thrive in this new world of hybrid work, people and organizations need solutions that are fluid, dynamic, and cloud-powered and Microsoft 365 has these solutions.


### Stay connected from anywhere in the world and at any time, your workers are able to access:

Cloud-based services and data in your Microsoft 365 subscription.

Organization resources, such as those offered by on-premises application datacenters.


### Your workers can be as productive as on-premises in a highly collaborative way with:

Online meetings, chat sessions, and push-to-talk communication with Microsoft Teams.

Shared workspaces for cloud-based file storage with global accessibility and real-time collaboration with SharePoint and OneDrive.

Shared tasks to divide up the work and automated business processes to increase operational efficiency.


### Microsoft 365 Developer Program - https://learn.microsoft.com/en-us/office/developer-program/build-microsoft-365-solutions

Microsoft 365 E5 developer subscription that you can use to create your own sandbox and develop solutions.

You can build Microsoft Teams apps, Office add-ins for Word, Excel, PowerPoint, or Outlook, or SharePoint add-ins, using Microsoft Graph, the SharePoint Framework, Power Apps, and more.


![image](https://github.com/M4gOo/Microsoft/assets/57456345/2f874750-aad8-4dbf-a196-6e2d624dfcf2)


After setup the dev program acc, access the webpage below to login using your email administrator acc (created previously) and password

https://admin.microsoft.com/   or   login.microsoft.com  (for users)

![image](https://github.com/M4gOo/Microsoft/assets/57456345/1b2349c8-d9c2-4cc6-b41d-c446dbdbb291)

So you can manage users and groups

There you can access different services

![image](https://github.com/M4gOo/Microsoft/assets/57456345/fe08bbf0-efac-43a5-a7f4-968ad57330b3)


# AZURE DIRECTORY

Everything you done in Microsoft Office 365 it is saved in Azure AD
\
In Azure AD you have more features, more technical level, advanced stuffs
\
Can revoke sessions meaning if she is login in many devices. This is good when reset, lockout acc issues



