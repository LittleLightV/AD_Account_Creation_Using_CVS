<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating New Active Directory Users Using CSV and Power Shell</h1>
This tutorial outlines creating new users and sending them to the correct Organizational Unit by utilizing a CVS file and Power Shell scripting.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell
- Microsoft Spreadsheet

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Spreadsheet Creation
- Power Shell Scripting
- Script Troubleshooting
- Successful Deployment!!!

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://imgur.com/4uGzgTe.png" height="80%" width="80%" />
</p>
<p>
Here we are, starting off so confident. Spreadsheet looks good, organized. All clear. So we move on to saving the file as a CSV.
</p>
<br />

<p>
<img src="https://imgur.com/dcPW3Z5.png" height="80%" width="80%" />
</p>
<p>
Next, I began writing the script. As you can see, it failed initially. So the with help of ChatGPT, I did some troublshooting. Turns out, I needed the full DN (Distinguished Name) path in order for PowerShell to understand the script.
</p>
<br />

<p>
<img src="https://imgur.com/T3V8akR.png" height="80%" width="80%" />
</p>
<p>
This image is my updated spread sheet. You can see where I corrected OU to add my domain and com
</p>
<br />

<p>
<img src="https://imgur.com/yjkSM01.png" height="80%" width="80%" />
</p>
<p>
Now we have our accounts created successfully!!
</p>
<br />

<p>
  <h2> Moment Of Truth...</h2>
  <p>
    <img src="https://imgur.com/d3ymPce.png" height="80%" width="80%" />
    <img src="https://imgur.com/NLJ0J2t.png" height="80%" width="80%" />
  </p>
  <p> Both images show account creating in both organizational units with departments added!!! It only took about 15 mins.</p>
</p>
<b />
