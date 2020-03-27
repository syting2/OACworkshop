## **Lab 2 - Provisioning Autonomous Data Warehouse**

In this round, you will provision a new ADW instance

# **Login to Oracle Cloud to create ADW Instance**

<table>
<thead>
<tr class="header">
<th><strong>View</strong></th>
<th><strong>Click Stream</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src=".//media/image2.png" style="width:7.03264in;height:2.7625in" /></td>
<td><ol type="1">
<li><p>Switch to your previous Tab</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image3.png" style="width:7.03264in;height:2.75833in" /></td>
<td><ol type="1">
<li><p>Click <img src=".//media/image4.png" style="width:0.35412in;height:0.32193in" /> on top left to expand service menu</p></li>
<li><p>Click “<strong>Autonomous Data Warehouse</strong>”</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image5.png" style="width:7.03264in;height:2.24583in" /></td>
<td><ol type="1">
<li><p>Click “<strong>Create Autonomous Data Warehouse</strong>”</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><img src=".//media/image6.png" style="width:6.5in;height:3.86111in" /> <img src=".//media/image7.png" style="width:6.5in;height:3.84931in" /></p>
<p><img src=".//media/image8.png" style="width:6.5in;height:3.54792in" /></p></td>
<td><ol type="1">
<li><p>Provide the ADW Instance Information</p></li>
</ol>
<ul>
<li><p>Display Name: &lt;&lt;<strong>anyname</strong>&gt;&gt;</p></li>
<li><p>Database name: &lt;&lt;<strong>anyname</strong>&gt;&gt;</p></li>
</ul>
<p>(<strong>use your username as database name</strong> <strong>and display name</strong>)</p>
<ul>
<li><p>Chose Data Warehouse</p></li>
<li><p>CPU Count: 1 (default)</p></li>
<li><p>Storage: 1 (default)</p></li>
<li><p><strong>Disable Auto Scaling</strong></p></li>
<li><p>Administrator Password: &lt;&lt;<strong>Any&gt;&gt;</strong></p></li>
<li><p>Confirm Administrator Password: &lt;&lt;<strong>Any&gt;&gt;</strong></p></li>
<li><p>License Type – License Included (default)</p></li>
</ul>
<p>Leave all other fields to their default value.</p>
<ol start="2" type="1">
<li><p>Click “Create Autonomous Data Warehouse”</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image9.png" style="width:7.03264in;height:2.00694in" /></td>
<td><ol type="1">
<li><p>Note your ADW service is being provisioned and state appears to be “<strong>Provisioning</strong>”–</p></li>
</ol>
<p><strong>Important – Please wait till this completes</strong></p></td>
</tr>
<tr class="even">
<td><img src=".//media/image10.png" style="width:7.03264in;height:2.09722in" /></td>
<td><ol type="1">
<li><p>State should change to “<strong>Available</strong>” in 2~3 minutes. Once state shows “Available”, it means ADW service is ready for use.</p></li>
<li><p>Please click database name</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image11.png" style="width:7.03264in;height:4.26389in" /></td>
<td><ol type="1">
<li><p>You can see details of ADW</p></li>
<li><p>You can test “<strong>Scale up</strong>” with ocpu or storage as we create ADW with the minimum configuration.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image12.png" style="width:7.03264in;height:1.84028in" /></td>
<td><ol type="1">
<li><p>Scaling up ocpu from 1 to 2.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><img src=".//media/image13.png" style="width:7.03264in;height:2.90972in" /></td>
<td><ol type="1">
<li><p>You can see <strong>SCAILING IN PROGRESS</strong> and also see <strong>ADW is available</strong> as <strong>GREEN</strong> colour</p></li>
</ol></td>
</tr>
<tr class="even">
<td><img src=".//media/image14.png" style="width:7.03264in;height:2.75in" /></td>
<td><ol type="1">
<li><p>It appears to be 2 ocpu now.</p></li>
</ol>
<blockquote>
<p>ADW was continuously up and running while scaling up number of ocpu.</p>
</blockquote></td>
</tr>
</tbody>
</table>

### Congratulation !! You have finsihed our workshop !! -<a href="https://github.com/syting2/OACworkshop/blob/TW_Workshop/Menu/Menu.md"> Back to Menu</a>
