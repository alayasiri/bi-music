<h1>Data Analysis on Track Features</h1>

<h2>Description:</h2>

Running analysis on track features of popular songs on a music streaming platform. This project consists of cleaning, normalizing, and ETL (extracting-transforming-loading) data to create a Tableau storyboard that offers actionable insights to promote data-driven decision-making. Looking to see if there is a relationship between popularity and track features.

<br /><a>
[Link to Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)</a>


<h2>Languages and Utilities Used:</h2>

- <b>MySQL</b> 
- <b>Python</b>
- <b>SQL</b> 
- <b>Excel</b> 
- <b>Tableau and Tableau Prep</b>


<h2>Cleaning and Normalizing:</h2>

<a> First, I had to clean and normalize the data by removing reduant data, building reference tables, and fixing encoded data. I used MySQL and Python to normalize the data; I used Python, Tableau Prep, and Excel to clean the data. I had to normalize the artist, track, and genre data by building reference tables. When I load the CSV files into MySQL, this will improve execution and simplify the querying process. Then, I changed the tracks' duration from being recorded in milliseconds to minutes. This will make any analysis done on track duration to be more meaningful and easier to understand. 

I then loaded the CSV files into MySQL and was able access the database through Tableau to conduct all the analysis. I used Tableau to create visuals that offer insights into the data. Tableau was used to offer insights into relationships between track features, understanding the track features of popular tracks, and analyzing patterns found in the track features of popular music. All of these visualizations were used in creating the story board.</a>

<h2>Tableau Storyboard:</h2>

<a> You can [downlad the Tableau storyboard here](https://github.com/alayasiri/bi-music/blob/main/spotify%20tableau.twbx). </a>

<!--

<p align="center">
Conceptual Diagram: <br/>
<img src="https://i.imgur.com/y6PFfWt.jpeg" height="80%" width="80%" alt="Clinic DB"/>
<br />
<br />
Schema:  <br/>
<img src="https://i.imgur.com/8p3eMOu.png" height="80%" width="80%" alt="Clinic DB"/>
<br />
<br />

<h2>Create and Insert:</h2>

<b>Building a Database for a Clinic</b>
- [Create Tables](https://github.com/alayasiri/ClinicDatabase/blob/c352ca6e6d38b99bc8dd34ec7708f6dd89f94e9d/Create%20Table)
- [Insert Statements](https://github.com/alayasiri/ClinicDatabase/blob/main/Inserts)

<p align="center">
Example using Patient's Table: <br/>
<img src="https://i.imgur.com/cJ5SKKs.png" height="80%" width="80%" alt="Clinic DB"/>
<br />
<br />
  
<h2>Writing Queries and Views:</h2>

<b>Code to All Queries and Views</b>
- [Queries](https://github.com/alayasiri/ClinicDatabase/blob/main/Create%20Table)
- [Views](https://github.com/alayasiri/ClinicDatabase/blob/main/Views)
  
<p align="center">
Example Query:  <br/>
<img src="https://i.imgur.com/6FKnmUf.png" height="80%" width="80%" alt="Clinic DB"/>
<br />
<br />
Example View:  <br/>
<img src="https://i.imgur.com/RqlX2TO.png" height="80%" width="80%" alt="Clinic DB"/>
<br />
<br /> 

<br/>
<img src="https://i.imgur.com/nSyMgA3.png" height="80%" width="80%" alt="Clinic DB"/>
<br />
<br /> 
  
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
