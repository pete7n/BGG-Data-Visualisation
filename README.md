<h1>CV Static Website</h1>

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
<img src="https://imgur.com/aKFlHUQ.png" height="80%" width="80%" alt="Static Website Project Steps"/>
<br />
<br />
Downloaded csv file of my board game collection data from boardgamegeek.com:  <br/>
<img src="https://imgur.com/QCq3b6I.png" height="80%" width="80%" alt="Static Website Project Steps"/>
<br />
<br />
Prepared the data in excel and uploaded it into the S3 bucket: <br/>
<img src="https://imgur.com/sy34MxD.png" height="80%" width="80%" alt="Static Website Project Steps"/>
<br />
<br />
Edited and uploaded a manifest JSON file to point QuickSight to S3 bucket and the csv data file:  <br/>
<img src="https://imgur.com/YU5fPiI.png" height="80%" width="80%" alt="Static Website Project Steps"/>
<br />
<br />
Created a QuickSight account and linked to S3 bucket containing the data using the URL for the manifest file.:  <br/>
<img src="https://imgur.com/E3Zvzw0.png" height="80%" width="80%" alt="Static Website Project Steps"/>
<br />
<br />
Created a new dataset within Quicksight, using the URL of the manifest file:  <br/>
<img src="https://imgur.com/2VAn8Rx.png" height="80%" width="80%" alt="Static Website Project Steps"/>
<br />
<br />
Created a sheet visualising the data and exported it as a pdf, which is shared in this repository:  <br/>
<img src="https://imgur.com/YavQJhV.png" height="80%" width="80%" alt="Static Website Project Steps"/>  
</p>
