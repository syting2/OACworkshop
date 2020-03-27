## **Lab 1: Analysing Data Using Oracle Analytic Cloud**

In this round, you will analyze finance data from Oracle Autonomous Data
Warehouse using Oracle Analytics Cloud based on a dashboard created for
a Finance Manager.

You will also see how you can upload a sample Excel file into ADW and
start doing your own analysis.

## Access to Finance Manager Dashboard

<table>
<thead>
<tr class="header">
<th><strong>View</strong></th>
<th><strong>Click Stream</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src=".//media/image2.png" style="width:4.72153in;height:2.38958in" /></td>
<td><ol type="1">
  <li><p>Open your network browser and log in to <a href ="https://www.oracle.com/index.html"target="_blank">oracle.com.</a></p></li>
<li><p>Click on View Accounts and Sign to Cloud</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image3.png" style="width:4.72153in;height:2.23472in" /></td>
<td><ol type="1">
<li><p>Put in your Cloud Account Name</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image4.png" style="width:3.51389in;height:2.74128in" /></td>
<td><ol type="1">
<li><p>Type in the User Name: <strong>&lt;&lt;user_id&gt;&gt;</strong> and password: <strong>&lt;&lt;password&gt;&gt;</strong></p></li>
<li><p>Click Sign In</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image5.png" style="width:4.72153in;height:1.84236in" /></td>
<td><ol type="1">
<li><p>You will be log in to your Oracle cloud account</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image6.png" style="width:4.72153in;height:1.80625in" /></td>
<td><ol type="1">
<li><p>Click <img src=".//media/image7.png" style="width:0.35412in;height:0.32193in" /> on top left to expand service menu and click on Analytics.</p></li>
<li><p>Then Chose Analytic Cloud</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image8.png" style="width:4.72153in;height:1.80208in" /></td>
<td><ol type="1">
<li><p>You will see a page like this</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image9.png" style="width:4.72153in;height:1.80833in" /></td>
<td><ol type="1">
<li><p>Click on the button and click on Open URL.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image10.png" style="width:4.72153in;height:2.13194in" /></td>
<td><ol type="1">
<li><p>Once you clicked it, you will be in OAC Portal.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p><img src=".//media/image11.png" style="width:4.72153in;height:2.11597in" /></p>
<p><img src=".//media/image12.png" style="width:2.89623in;height:1.62851in" /></p></td>
<td><ol type="1">
<li><p>From the Home Page click on the Navigator icon (Top Left)</p></li>
<li><p>Click on Catalog Menu</p></li>
<li><p>Select Shared Projects</p></li>
<li><p>Navigate to the Finance Manager folder</p></li>
<li><p>Click on Revenue and Cost to open the project</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image13.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>This is the sample dashboard that you can play with.</p></li>
</ol></td>
</tr>
</tbody>
</table>

## Upload an Excel file to Oracle Autonomous Data Warehouse

<table>
<thead>
<tr class="header">
<th><strong>View</strong></th>
<th><strong>Click Stream</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src=".//media/image14.png" style="width:4.66468in;height:1.9375in" /></td>
<td><ol type="1">
<li><p>Click on the “Navigator” Menu at the top left and select Home</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image16.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>From the Home Page click on Create / Project</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image17.png" style="width:2.22437in;height:1.84722in" /></td>
<td>1. Click on Create Data Set</td>
</tr>
<tr class="even">
<td><img src=".//media/image18.png" style="width:4.72153in;height:2.5875in" /></td>
<td><ol type="1">
<li><p>Click on Drop Data file here or click to browse</p></li>
<li><p>Select the “Expense Summary - Finance Manager.xlsx” file provided</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image19.png" style="width:4.68577in;height:2.16667in" /></td>
<td><ol type="1">
<li><p>Click on “Add”</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image20.png" style="width:4.8789in;height:2.17361in" /></td>
<td><ol type="1">
<li><p>Click on Visualize to start visualise your data.</p></li>
</ol></td>
</tr>
</tbody>
</table>

## Analyze Expenses data with OAC

<table>
<thead>
<tr class="header">
<th><strong>View</strong></th>
<th><strong>Click Stream</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src=".//media/image21.png" style="width:3.67361in;height:2.06563in" /></td>
<td><ol type="1">
<li><p>Right click on “Out-of-Policy Expenses” and select Explain Out-of-Policy Expenses</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image22.png" style="width:3.39583in;height:1.90944in" /><img src=".//media/image23.png" style="width:3.39583in;height:1.90944in" /></td>
<td><ol type="1">
<li><p>Check the on the 1<sup>st</sup> chart to keep it for further analysis</p></li>
<li><p>Scroll down to see additional charts</p></li>
<li><p>Select the “by Month”, “by “SubCategory” and “by “Cost Center” charts</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image25.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>Click on “Anomalies for Out-of-Policy Expenses</p></li>
<li><p>Select the 1<sup>st</sup> chart showing that for the Marketing Cost Center “Airfares” and “Per Diem” Out-of-Policy Expenses are much higher than expected</p></li>
<li><p>Scroll down to select the chart showing that for “Airfares” Out-of-Policy Expenses are much higher than expected in Q1 and Q2</p></li>
<li><p>Click on Add Selected</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image26.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>Click on the icon to create a new canvas</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image28.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>From the left “Data Elements” pane select Month and Expense Amount (use the “Ctrl” Key to do multi selections)</p></li>
<li><p>Drag and Drop to the canvas</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image29.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>From the left “Data Elements” pane select Previous Year Amount and drop it under Expense Amount in the Values (Y-Axis)</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image30.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>From the left “Data Elements” pane select Out-of-Policy Expense, SubCategory and Quarter</p></li>
<li><p>Drag and Drop to the left of the existing chart</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image31.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>Click on the Chart Drop Box</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image32.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>Select Sunburst</p></li>
<li><p>Click Navigator Menu to go back to the Home Page</p></li>
</ol></td>
</tr>
</tbody>
</table>

### Congratulation\!\! You have finsihed Lab 1. You are now ready to move to the next lab - <a href ="https://github.com/syting2/OACworkshop/blob/TW_Workshop/ADW/02-ADW.md">Lab 2: Provisioning ADW</a>
