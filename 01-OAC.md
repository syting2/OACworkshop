**Analyst Data Using Oracle Analytic Cloud**

In this round, you will analyze finance data from Oracle Autonomous Data
Warehouse using Oracle Analytics Cloud based on a dashboard created for
a Finance Manager.

You will also see how you can upload a sample Excel file into ADW and
start doing your own analysis.

## Access to OAC Dashboard

<table>
<thead>
<tr class="header">
<th><strong>View</strong></th>
<th><strong>Click Stream</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src=".//media/image1.png" style="width:3.43605in;height:2.68056in" /></td>
<td><ol type="1">
<li><p>Paste the OAC link in your webpage.</p></li>
<li><p>Provide the information</p></li>
</ol>
<blockquote>
<p>User Name : <strong>userXX</strong></p>
<p>Password: <strong>Paste the Password in the email</strong></p>
</blockquote>
<ol start="3" type="1">
<li><p>Click “Sign In“ button</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><img src=".//media/image2.png" style="width:4.72153in;height:1.72222in" /></p>
<p><img src=".//media/image3.png" style="width:4.72153in;height:3.07431in" /></p></td>
<td><ol type="1">
<li><p>From the Home Page click on the Navigator icon (Top Left)</p></li>
<li><p>Click on Catalog Menu</p></li>
<li><p>Select Shared Projects</p></li>
<li><p>Navigate to the Finance Manager folder</p></li>
<li><p>Click on Revenue and Cost to open the project</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image4.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>Mouse over the yellow bar in the OPEX YTD vs. Previous Year</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image5.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="2" type="1">
<li><p>Click on “Revenue” tab at the bottom</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image6.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>Click on ‘OPEX’ tab at the bottom</p></li>
<li><p>Click on the REGION filter at the top left</p></li>
</ol>
<p>Select UK</p></td>
</tr>
<tr class="even">
<td><img src=".//media/image7.png" style="width:4.72153in;height:2.65486in" /></td>
<td>Click on ‘Cost’ tab at the bottom</td>
</tr>
<tr class="odd">
<td><img src=".//media/image8.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol type="1">
<li><p>Click on ‘Headcount’ tab at the bottom</p></li>
</ol>
<ol start="3" type="1">
<li><p>Click on the “Call Center Services” blue line in the tope chart</p></li>
</ol></td>
</tr>
</tbody>
</table>

## Upload an Excel file to Oracle Analytic Cloud

<table>
<thead>
<tr class="header">
<th><strong>View</strong></th>
<th><strong>Click Stream</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src=".//media/image1.png" style="width:3.51389in;height:2.74128in" /></td>
<td><ol type="1">
<li><p>Open your web browser</p></li>
<li><p>Connect to OAC via the provided URL: &lt;&lt;OAC URL&gt;&gt;</p></li>
<li><p>Type in the User ID: <strong>&lt;&lt;user_id&gt;&gt;</strong> and password: <strong>&lt;&lt;password&gt;&gt;</strong></p></li>
<li><p>Click Sign In</p></li>
</ol>
<p><strong>Note:</strong> if you are still connected to OAC after previous exercise, click on the “Navigator” Menu at the top left and select Home</p></td>
</tr>
<tr class="even">
<td><img src=".//media/image10.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="6" type="1">
<li><p>From the Home Page click on Create / Project</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image11.png" style="width:2.22437in;height:1.84722in" /></td>
<td><ol start="7" type="1">
<li><p>Click on Create Data Set</p></li>
<li><p>Click on Drop Data file here or click to browse</p></li>
<li><p>Select the “Expense Summary - Finance Manager.xlsx” file provided</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image13.png" style="width:4.68577in;height:2.16667in" /></td>
<td><ol start="10" type="1">
<li><p>From the Name : Type in your Name</p></li>
<li><p>Click on “Add”</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image14.png" style="width:4.72153in;height:2.35972in" /></td>
<td><ol start="12" type="1">
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
<td><img src=".//media/image15.png" style="width:3.67361in;height:2.06563in" /></td>
<td><ol type="1">
<li><p>Right click on “Out-of-Policy Expenses” and select Explain Out-of-Policy Expenses</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image16.png" style="width:3.39583in;height:1.90944in" /><img src=".//media/image17.png" style="width:3.39583in;height:1.90944in" /></td>
<td><ol start="2" type="1">
<li><p>Check the on the 1<sup>st</sup> chart to keep it for further analysis</p></li>
<li><p>Scroll down to see additional charts</p></li>
<li><p>Select the “by Month”, “by “SubCategory” and “by “Cost Center” charts</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image19.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="5" type="1">
<li><p>Click on “Anomalies for Out-of-Policy Expenses</p></li>
<li><p>Select the 1<sup>st</sup> chart showing that for the Marketing Cost Center “Airfares” and “Per Diem” Out-of-Policy Expenses are much higher than expected</p></li>
<li><p>Scroll down to select the chart showing that for “Airfares” Out-of-Policy Expenses are much higher than expected in Q1 and Q2</p></li>
<li><p>Click on Add Selected</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image20.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="10" type="1">
<li><p>Click on Save to save your project</p></li>
</ol>
<ol start="9" type="1">
<li><p>Click on the icon to create a new canvas</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image22.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="11" type="1">
<li><p>From the left “Data Elements” pane select Month and Expense Amount (use the “Ctrl” Key to do multi selections)</p></li>
<li><p>Drag and Drop to the canvas</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image23.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="13" type="1">
<li><p>From the left “Data Elements” pane select Previous Year Amount and drop it under Expense Amount in the Values (Y-Axis)</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image24.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="14" type="1">
<li><p>From the left “Data Elements” pane select Out-of-Policy Expense, SubCategory and Quarter</p></li>
<li><p>Drag and Drop to the left of the existing chart</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image25.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="16" type="1">
<li><p>Click on the Chart Drop Box</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image26.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="17" type="1">
<li><p>Select Sunburst</p></li>
<li><p>Click Navigator Menu to go back to the Home Page</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image27.png" style="width:4.72153in;height:2.65486in" /></td>
<td><ol start="19" type="1">
<li><p>Click on Watch Overview for a video demonstration</p></li>
<li><p>You can click on “?” for more help</p></li>
</ol></td>
</tr>
</tbody>
</table>
