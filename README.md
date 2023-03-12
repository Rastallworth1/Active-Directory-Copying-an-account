<h1>Active Directory: Copying an account</h1>



<h2>Description</h2>
In some cases you may want to create an account and not go through the process of assigning that account to different group or assigning certain rights or privileges. In that case, you could simply copy another account that already has the desired attributes. For this example, we will copy an administrator account.
<br />




<h2>Environments Used </h2>

- <b>Windows Server 19</b> 

<h2>Copying an Account</h2>

<p align="center">
Start at the Server Manager Dashboard and open Tools, located on the top right corner. From there, select Active Directory Users and Computers.<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Copying-an-account/blob/main/Screenshot%201.png"/>
<br />


<br />
I would recommend pining Active Directory Users and Computers to your taskbar, since this starting point will be used very often.<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Copying-an-account/blob/main/Screenshot%202.png"/>
<br />


<br />
Next, you would double click on Domain (ReggieTech), select users and then right click on Administrator and select Copy.  <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Copying-an-account/blob/main/Screenshot%203.png"/>
<br />


<br />
In this instance the Administrator is a member of 6 groups with specific permissions.<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Copying-an-account/blob/main/Screenshot%204.png"/>
<br /> <br /> Each time you create an administrator, you would have to give him those permissions and assign him to each group. This could be tedious and time consuming. To make this more efficient, we could simply copy the account and just change the user information.<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%204.png"/>
<br />




<br />
Once you select copy, fill out all the account information and assign an account password to create the account.  <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Copying-an-account/blob/main/Screenshot%205%20first.png"/>
<br />
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Copying-an-account/blob/main/Screenshot%205%20Seconf%20half.png"/>
<br />

  <br />
Now the Administrator 2 account has been created. Simple double click the account and select Member Of from the top to verify it belongs to the same groups as the original Administrator account. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%206%20Top.png"/>
<br />

  


<br />
This was a simple Active Directory Home Lab / Tutorial thats demonstrates the proper steps to copy an account.<br/>




