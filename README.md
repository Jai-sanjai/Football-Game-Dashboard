# Football-Game-Attributes-Analysis
Here’s a structured README content for your <b>Football Strategy </b>, which you can use for your GitHub repository. It follows a clear, organized format that will help showcase my project in the data analytics field:
<hr>

# ⚽Football Game Data-Analysis Dashboard 📊
This repository contains my Football Strategy Analysis project, which I completed as part of my personal data analytics portfolio. The project involves analyzing the physical attributes and draft metrics of Football Game Strategy of various attributes by using Power BI, DAX, and Excel. The primary goal is to identify Squad and count of each squad
<hr>

# &#128204; Project Overview 
The Football Strategy Analysis project focuses on analyzing such as <b>Squad and their teams</b> , <b>Players's Goal</b> ,<b>Nation</b>  and <b>positions</b> of Football Strategy to determine how these metrics influence their draft position and potential success in the league.
<ol>
  <li><b>Dataset:</b>Contains 2922 Football player's score attributes from the years 2021-2022.</li>
  <li><b>Goal:</b>To provide dashboard that which squad's player is top and their position.</li>
  <li><b>Dashboard:</b>The interactive dashboard visualizes player data to help scouts and analysts make data-driven decisions.</li>
</ol>
<hr>
  
# 🛠 Data Cleaning & Preparation
<b>Steps Involved:</b>
<ol type="1">
  <li>Missing Values Handling:<br>
    <ul>
      <li>Columns like Bench, Sprint, and Agility had missing values, which were filled using the average values.</li>
      <li>Formula used: =IF(ISBLANK(Q2), ROUND(AVERAGE($Q$2:$Q$518), 0), Q2)</li>
    </ul> </li>
  <li>
    <b>Power Query in Power BI:</b>
    <ul>
      <li>Null values were filtered out during data loading and transformations were applied to ensure clean, usable data.</li>
    </ul>
  </li>
  <li>    <b>Data Transformation:</b>
    <ul>
      <li>Columns like height and weight were categorized into ranges using the SWITCH() function in DAX.</li>
    </ul>
    
  </li>
  </li>
</ol>
<hr>

# 📊 Key Metrics & Visualizations

<h1>Key Performance Indicators (KPIs):</h1>
<ul>
  <li>Total Players Analyzed: 2921 👥</li>
  <li>Avg Age: 26.09 </li>
  <li>Total Squad: 98</li>
</ul> <hr>

# 🧰 Tools & Technologies
<ul>
  <li><b>Power BI:</b> Used for building interactive dashboards and generating insights.</li>
  <li><b>DAX (Data Analysis Expressions:</b>) Used for calculating averages, measures, and creating KPIs.</li>
  <li><b>Excel: </b> Utilized for initial data cleaning and handling missing values.</li>
  <li><b>SQL:</b> (Optional, if you ran any queries to handle data before importing to Power BI)</li>
</ul>
<b></b>
<hr>

# Dashboard


// <a href="https://github.com/Jai-sanjai/Football-Game-Dashboard/blob/main/2021-2022%20Football%20Player%20Stats.csv">Click to view <b>Dataset</b></a>

![Screenshot 2024-09-24 201713](https://github.com/user-attachments/assets/decc7b64-2efc-47b0-90a6-154244a4a90d)


