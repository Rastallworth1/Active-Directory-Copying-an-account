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
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%202.png"/>
<br />


<br />
Now, lets create a new user. First, take a look at the tasks list on the right. Under the Users section, there's a New menu entry, which opens a submenu to select what's the type of entity that you want to create. In this case, we want to create a new user, so click User. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%203.png"/>
<br />


<br />
This will open a new window that lets you fill in a number of fields related to the new user. There are numerous fields available, but only a few are mandatory, which are marked with a read asterisk. You can leave the rest empty. The user that we are creating is called Reggie, with their username being also Reggie.<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%204.png"/>
<br />
<br />Once you've entered the necessary information, click the OK button to create the user (Reggie). 
<br/>




<br />
Once you click on the newly created account, you will see that where it displays the name of the user, the system says Reggie (Disabled). This is a problem, but it can be easily fixed by enabling it. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%205.png"/>
<br />

  <br />
Lets try to enable Reggie's account. What happens if you right click on the entry and try to Enable it? The system will not enable an account unless you have a strong password that meets your organizations guidelines. In this case, the password is weak because we haven't set it. Obviously, an empty password is not a strong password. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%206%20Top.png"/>
<br />
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%206%20bottom.png"/>
<br />


  <br />
You can set a password using the Reset password menu option. This will allow the administator to enable the account. Another good practice is to have the User change the password at next logon. This can be done by selecting the change password at next logon option, this will ensure that the user will change their password when they log in. The goal here is to ensure that only the user knows their password and not the System Administrator. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%207%20top.png"/>
<br />
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%207%20bottom.png"/>
<br />

  
<br />
Once you've set a strong password, you can retry enabling the account. This time it should work. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%209.png"/>
<br />
<br />
As you can see in the above slide, the account (Reggie) has been enabled and you now have the option to disable it. <br/>



  
  
  
  
  


<br />
This was a simple Active Directory Home Lab / Tutorial thats demonstrates the proper steps to create a User Account.<br/>




