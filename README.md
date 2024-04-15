<h1>Data Visualisation</h1>

<h2>Description</h2>
Used Amazon QuickSight and S3 to visualise data of my board game collection.
<br />

<h2>AWS Products Used</h2>

- <b>Simple Storage Service (S3)</b>
- <b>QuickSight</b>

<h2>Other Products Used</h2>

- <b>Microsoft Excel</b>
- <b>Windows Notepad</b>

<h2>Project Stages:</h2>

<p align="center">
Created S3 bucket to store data.: <br/>
<img src="https://imgur.com/LI617s3.png" height="80%" width="80%" alt="BGG QuickSight"/>
<br />
<br />
Downloaded csv file of my board game collection data from boardgamegeek.com:  <br/>
<img src="https://imgur.com/drhBLWH.png" height="80%" width="80%" alt="BGG QuickSight"/>
<br />
<br />
Prepared the data in excel and uploaded it into the S3 bucket: <br/>
<img src="https://imgur.com/0Vo9jxc.png" height="80%" width="80%" alt="BGG QuickSight"/>
<br />
<br />
Edited and uploaded a manifest JSON file to point QuickSight to S3 bucket and the csv data file:  <br/>
<img src="https://imgur.com/CejWAlo.png" height="80%" width="80%" alt="BGG QuickSight"/>
<br />
<br />
Created a QuickSight account and linked to S3 bucket containing the data using the URL for the manifest file, then created a new dataset within Quicksight, using the URL of the manifest file:  <br/>
<img src="https://imgur.com/M7WWuOV.png" height="80%" width="80%" alt="BGG QuickSight"/>
<br />
<br />
Created a sheet visualising the data and exported it as a pdf, which is shared in this repository:  <br/>
<img src="https://imgur.com/noTxaZ3.png" height="80%" width="80%" alt="BGG QuickSight"/>  
</p>
