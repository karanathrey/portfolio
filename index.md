# Portfolio

---

## [India-Australia Test Series 20/21 Pitch Map Analysis - Project 1](/sample_page)
### Overview
This project is based on the sport of cricket. The aim of this project is to analyse and compare the pitching zones of the top bowlers in the India-Australia test series in 2020/21. This is accomplished by visualising the ball by ball data which can be obtained from ESPNcricinfo's scorecard commentary. 

### Data Collection and Overview
The source of the data was the scorecard available on ESPNcricinfo. The ball by ball data from every innings of the four matches was web scraped for this project. The raw dataset obtained were stored as structured data in a CSV format and have the following attributes - 
<ol>
  <li> 'ball' - The ball number identifier for a ball bowled in an innings. </li>
  <li> 'bowler_batsman' - Player information on which bowler bowled to which batsman. </li>
  <li> 'result' - The result of a bowled ball. </li>
  <li> 'commentary' - The detailed commentary for a ball bowled. </li>
</ol>
<i>(Tools used: Python - pandas and BeautifulSoup)</i>

### Data Cleaning and Transformation:
<p>The raw data scraped had to be structured and transformed to be made readily available for data analysis. The data in its raw form does not allow for required analysis and therefore different transformation techniques were applied to make the dataset viable. </p>
<p>Firstly, two new attributes were created using the 'commentary' column. Using word filters, the python code searches for keywords in the 'commentary' field and determines the line and length for a bowled ball. The line and length are key attributes for a pitch map analysis as they define the position of ball landing on the pitch. </p>
<p>The different datasets acquired for each innings in the four matches were merged into one excel file so that the entire series can be analysed under a single dataset. This excel dataset can be viewed on my <a href="https://www.kaggle.com/karanathrey/india-vs-australia-2021-ball-by-ball-data">Kaggle Profile</a>. The dataset was further cleaned for consistency. The 'bowler_batsman' was split into two columns of 'bowler' and 'batsman' and the data tpyes of each column were corrected.</p> 
<i>(Tools used: Python - pandas, Power BI - Power Query Editor)</i>

### Analysis and Findings
<p>A pitch map was achieved by the use of a scatter plot. The line and length represent the x and the axis of the scatterplot respectively. This creates a simplified pitch map to represent the point at where the ball pitched. </p>
<img src="images/Starc.png?raw=true"/>
<ul>
  <li>The Australian bowler Mitchell Starc bowled 47.62% of 'Good' Length deliveries with 26.7% of those balls being 'Outside Off'.</li>
  <li>Starc also favoured the 'outside off' a lot in terms of line with approximately 50% of deliveries in that line. </li>
</ul>
<img src="images/Siraj.png?raw=true"/>
<ul>
  <li>The Indian bowler Mohammad Siraj was more condensed in his bowling with 57.61% of 'Good' length balls and 46.72% of balls bowled on the 'Off Stump' and 'Outside Off' combined. </li>
  <li>Siraj also bowled significantly more on the 'Good' length and on 'Off Stump' compared to Starc with 20.60% of balls pitching in that region.</li>
</ul> 
<img src="images/Cummins.png?raw=true"/>
<ul>
  <li>Australian bowler Pat Cummins was similar to Siraj where 19.14% of his balls were pitched on 'Off Stump'on 'Good' length and 56.30% ball pitched on the 'Good' length.</li>
  <li>Cummins also pitched the most balls on the 'Good' length and 'Outside Off' line with 30.37% of balls pitched in that region. </li> 
</ul> 
<i>(Tools used: Power BI - Visualisations)</i>

### Conclusion 
The most vital conclusion is how the worst pace bowler in the series, Starc with 11 wkts @40.72 average didn't bowl enough good length aiming at the off stump area. Compare that to Cummins or Siraj who were much more disciplined in that aspect. Both Siraj's and Cummins' success can be related to their higher pitches in that area. 
