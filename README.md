# Best-Neighborhood-for-Pokemon

Using various Python libraries to determine the best neighborhood in Pittsburgh to play Pokemon Go

<h2>Description</h2>
For this project, I wanted to find which neighborhood in Pittsburgh would be the best for playing Pokemon Go. In the game, Pokemon tend to spawn in parks, so I knew that one of the metrics would measure the size of the parks in each neighborhood. I also discovered that most Pokemon Go players are adults, so neighborhoods with fewer children could correlate to more Pokemon Go players. Furthermore, when a player is walking around staring at their phone, they don't want to be at risk of danger, so the third metric measures how safe a neighborhood is by looking at recent police reports.

<br />

So, ideally, the best neighborhood will have:
<br />
-the least number of police reports (fewer police reports = less crimes = more safe)
<br />
-the greatest number of park equipment (more park equipment = more parks/larger park)
<br />
-the least children
<br />


<h2>Language Used</h2>
- Python

<h2>Environments Used </h2>

- <b> macOS version 12</b> (21H2)
- Jupyter Notebook

<h2>Program walk-through:</h2>

<p align="center">
Import Data from the Western Pennslyvania Regional Data Center: <br/>
<img src="https://i.imgur.com/CnZaDdZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Metric 1 - Determine the neighborhood with the least number of police reports:  <br/>
<img src="https://i.imgur.com/caitoJ6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/SEhGEln.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Metric 2 - Determine the neighborhood with the fewest children: <br/>
<img src="https://i.imgur.com/qxgFijh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/LqaYvXt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Metric 3 - Determine the neighborhood with the biggest park:  <br/>
<img src="https://i.imgur.com/KjiTFnN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/LqaYvXt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ranking system:  <br/>
After each metric, points were assigned with a running total. This will be used at the end to determine the winner
<br/>
<img src= "https://i.imgur.com/im7usZO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Conclusion:  <br/>
<img src="https://i.imgur.com/qzVEibn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
