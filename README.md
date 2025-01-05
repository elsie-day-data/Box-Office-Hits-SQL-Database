# Box Office Hits SQL Database

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results Or Findings](#results-or-findings)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References or Resources](#references-or-resources)

---
### Project Overview
---

This data analysis project aims to 1) view the data in the movies table, 2) filter out movies that are from the year 2000 or greater, and 3) further sort by year.

<img width="1202" alt="Screenshot 2025-01-05 at 3 53 40 PM" src="https://github.com/user-attachments/assets/ecf22263-a3eb-4274-8f91-4c67df04a2fe" />

---
### Data Sources
---

Movie Data: The primary dataset used for this was Khan Academy data.

---
### Tools
---

- SQL Lite

---
### Data Preparation
---
In the initial data preparation phase, I performed the following tasks:
1. Used the ```SELECT * FROM movies;``` command to pull and review all the data in the "movies" database.

---
### Exploratory Data Analysis
---

EDA involved exploring the movie data to answer key questions such as:
1. Are there any movies that are from the year 2000 or greater?
2. What is the list if we sort them by the year?

---
### Data Analysis
---

Interesting code/features worked with:

```sql
SELECT * FROM movies WHERE release_year > 2000 ORDER BY release_year;
```

---
### Results or Findings
---

The analysis results are summarized as follows:
- The results revealed that there were three movies in the list that were from the year 2000 or greater.
- The results showed that the first movie to be released from 2000 and beyond was Shrek 2 (2004 release). 

---
### Insights
---

It was interesting that building this data set required three phases of
1. I first attempted to just do a "SELECT * movies" query but realized that I needed to first tell the syntax where to select "movies" from.

``` SELECT * movies;``` changed to ``` SELECT * FROM movies;```

---
### Recommendations
---

- Could be worth adding ratings and categories to the dataset and explore if there is any correlation between ratings and movie categories.

---
### Limitations
---

There were no limitations in this database. In the future I will use this section to detail any outliers or adjustments I had to make to the data to protect the accuracy of analysis I'm working to achieve.

---
### References or Resources
---

1. [Khan Academy](https://www.khanacademy.org/computing/computer-programming/sql/sql-basics/pc/challenge-box-office-hits-database)
