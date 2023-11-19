# Backup and Restore Your Realtek EQ profile - the easiet way!
Realtek has in its driver the ability to configure your own EQ profile for Audio equipment. Unfortunately, there is no official way to save the profile to a file or transfer it to another computer. <br>
<br>
In this guide, I'll show you how to protect and restore your audio settings on any device with a Realtek sound card.
<img src="https://i.imgur.com/Dpvvxiy.png" width="400" />

## Step 1 - Save Your profile
<h3 align="left">To make a copy of your settings, you will need to use the Windows registry</h3> 

  1. WIN + R
  2. Type "regedit" and hit Enter
  3. Confirm that you run the application with administrator privileges
  <img src="https://i.imgur.com/MMLgd8B.png" width="400" />
  4. Navigate to HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\MMDevices\Audio\Render
  5. Right-click on the "Render" folder and select "Export", save the file in a safe place
  <img src="https://i.imgur.com/9hvtvfg.png" width="400" />  
  <img src="https://i.imgur.com/RTWlKjw.png" align="center" width="400" />

<h3 align="left">Done! Your EQ audio settings are now safe :)</h3> 

## Step 2 - Restoring Your profile (any device)
<h4 align="left">Again, as in the case of saving a profile, we will also use Regedit to restore the settings.</h4> 

  1. At the beginning, a good step would be to manually create any EQ profile for the device we are interested in. For example, "example123" <br>
  <img src="https://i.imgur.com/9tZ2Npk.png" width="600" />  <br>
After creating the profile, we need to close ALL audio settings <br>
  <br>
  2. Open your *.reg copy file with notepad and search for the name of the profile you want to restore. In my case, the profile was called "darek10"
  <img src="https://i.imgur.com/tXqDRd9.png" width="400" />
  * confirm that you run the application with administrator privileges <br>
  CTRL + F, type profile name <br>
  <img src="https://i.imgur.com/iBC5rKy.png" width="600" />

