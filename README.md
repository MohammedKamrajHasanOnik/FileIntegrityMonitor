<h1>FileIntegrityMonitor </h1>

<h2>Description</h2>
This project is a guide of how I create hashing algorithims and code up a custom file integrity monitor, integrity means maintaining consistency and trustworthy of data, this could indicate making sure data doesnt get changed when its not meant to be, 
if it does get changed perhaps get an alert or notification to that change, so an analyst/monitor can investigate and fix this issue.
<br />

<h3>Languages and Utilities Used</h3>

- <b>Powershell</b> 
- <b>Hashing Algorithims (SHA-512, etc.)</b>
- <b>Automation</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Windows Powershell ISE (x86)</b>



<h4 align="center">Program guide</h4>

<p align="center">
<b>The network diagram as shown I will be utilizing for the project</b> <br/>
<img src="https://imgur.com/a/CDfGo6t"/>


<p align="center">
<b> What would you like to do? A) collect new baseline or B begin monitoring files with saved Baseline? write host with read host prompt commands Please enter A or B with user responses</b> <br/>
<img src="https://imgur.com/W8t1Jrl"/>
<br />
<br />
<br/>

<p align="center">
<b> What would you like to do? with if else if statement works ran and tested both A and B with run script, added foreground colours</b> <br/>
<img src="https://imgur.com/MbV9k4K"/>
<br />
<br />
<br/>


<p align="center">
<b> Created function to calculate file hash to file path using algorithim SHA512 which shows the algorithim hash and path of the file a.txt and prints to the screen</b> <br/>
<img src="https://imgur.com/DSxhOeO"/>
<br />
<br />
<br/>

<p align="center">
<b> Instead printing calculate file hash on screen stored in variable object $hash as shown in run test</b> <br/>
<img src="https://imgur.com/sw25Bud"/>
<br />
<br />
<br/>
<b> Setting up 


<br />
<br />
<br/>

<p align="center">
<b> Collect all files in the target folder by using Get-childItem to the path .\files then printing files on the screen mode, last write time, length and name </b> <br/>
<img src="https://imgur.com/TKHGLfR"/>
<br />
<br />
<br/>


<p align="center">
<b> Utilized an array with dictonary assigining certain methods, checking baselines as well as checking for values etc. </b> <br/>
<img src="https://imgur.com/rBuVH35"/>
<br />
<br />
<br/>


<p align="center">
<b> Created if else if while for each statements with different options to check e.txt file if it has been changed or created etc </b> <br/>
<img src="https://imgur.com/undefined"/>
<br />
<br />
<br/>


