# Portfolio

---

## [India-Australia Test Series 20/21 Pitch Map Analysis - Project 1](/sample_page)
### Overview
This project is based on the sport of cricket. The aim of this project is to analyse and compare the pitching zones of the top bowlers in the India-Australia test series in 2020/21. This is accomplished by visualising the ball by ball data which can be obtained from ESPNcricinfo's scorecard commentary. 

### Data Collection and Overview:
The source of the data was the scorecard available on ESPNcricinfo. The ball by ball data from every innings of the four matches was web scraped for this project. The raw dataset obtained were stored as structured data in a CSV format and have the following attributes - 
<ol>
  <li> 'ball' - The ball number identifier for a ball bowled in an innings. </li>
  <li> 'bowler_batsman' - Player information on which bowler bowled to which batsman. </li>
  <li> 'result' - The result of a bowled ball. </li>
  <li> 'commentary' - The detailed commentary for a ball bowled. </li>
</ol>
<i>(Tools used: Python - pandas and BeautifulSoup)</i>

### Data Transformation:
<p>The raw data scraped had to be structured and transformed to be made readily available for data analysis. The data in its raw form does not allow for required analysis and therefore different transformation techniques were applied to make the dataset viable. </p>
Firstly, two new attributes were created using the 'commentary' column. Using word filters, the python code searches for keywords in the 'commentary' field and determines the line and length
The different datasets acquired for each innings in the frour matches were merged into one excel file. 


<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Project 2 Title](/pdf/sample_presentation.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
