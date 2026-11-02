\# Global Olympic Sports Performance Analysis



\## 📌 Project Overview



Global Olympic Sports Performance Analysis is a data visualization and analytics project that analyzes Olympic sports performance using historical athlete and medal data.



The project uses Tableau to identify patterns in medal performance, countries, sports, seasons, gender participation, and Olympic cities.



A Flask-based website is also developed to provide a professional web interface for presenting the Tableau dashboard and story.



\---



\## 🎯 Project Objectives



\- Analyze Olympic medal performance across countries.

\- Identify sports producing the highest number of medals.

\- Analyze gold medal performance.

\- Study Olympic medal trends over the years.

\- Compare Summer and Winter Olympic Games.

\- Analyze medal participation by gender.

\- Identify top-performing Olympic cities.

\- Create interactive Tableau dashboards and stories.

\- Integrate Tableau visualizations into a Flask website.



\---



\## 📊 Dataset



The project uses the \*\*120 Years of Olympic History: Athletes and Results\*\* dataset.



\### Dataset Files



\- `athlete\_events.csv`

\- `noc\_regions.csv`



The athlete dataset contains approximately \*\*271,000 athlete-event records\*\* with information such as:



\- Athlete ID

\- Athlete Name

\- Gender

\- Age

\- Height

\- Weight

\- Team

\- NOC

\- Games

\- Year

\- Season

\- City

\- Sport

\- Event

\- Medal



The `noc\_regions.csv` file is used to map Olympic NOC codes to country/region names.



\---



\## 🛠️ Technologies Used



\- Python

\- Flask

\- Tableau Public

\- HTML

\- CSS

\- JavaScript

\- Data Visualization

\- Data Analysis



\---



\## 📈 Tableau Visualizations



The project contains 10 major visualizations:



1\. Top 10 Countries by Medal Count

2\. Medals by Sport

3\. Medal Type Distribution

4\. Medals Over the Years

5\. Top 10 Countries by Gold Medals

6\. Medals by Season

7\. Medals by Gender

8\. Top 10 Sports by Gold Medals

9\. Top 10 Olympic Cities by Medal Count

10\. Top 10 Countries by Season



\---



\## 📊 Dashboard



The Tableau dashboard combines the major visualizations into one interactive dashboard.



\### Dashboard Filters



\- Year

\- Season

\- Sport

\- Country



These filters allow users to explore Olympic performance according to different conditions.



\---



\## 📖 Tableau Story



The project contains an 8-scene Tableau story:



1\. The Olympic Performance at a Glance

2\. Olympic Medal Trends: A Historical Overview

3\. Nations Leading the Olympic Medal Race

4\. Sports Driving Olympic Medal Success

5\. The Gold Medal Leaders

6\. Summer vs Winter: Olympic Medal Landscape

7\. The Changing Landscape of Olympic Participation

8\. Sports Producing the Most Gold Medals



\---



\## 🧮 Tableau Calculated Fields



The project uses calculated fields including:



\- Medal Count

\- Gold Medal Count

\- Silver Medal Count

\- Bronze Medal Count

\- Country

\- Athlete Count

\- Medal Winner



These calculations help create meaningful measures and categories for analysis.



\---



\## 🌐 Flask Website



A Flask web application was developed to present the project in a professional web interface.



The website includes:



\- Project introduction

\- Project objectives

\- Project statistics

\- Tableau Dashboard

\- Tableau Story

\- Technology section

\- Responsive design

\- Interactive Dashboard/Story switching



\### Flask Structure



```text

Global\_Olympic\_Sports\_Analysis/

│

├── app.py

├── requirements.txt

├── README.md

│

├── templates/

│   └── index.html

│

└── static/

