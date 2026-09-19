🎬🍿 Movie Streaming Data Analysis

<div align="center">📺 Exploring Users, Movies & Viewing Behavior with Python & SQL

Python • Pandas • SQLite • SQL • Data Analysis

</div>---

🌟 Project Overview

This project analyzes a movie streaming platform dataset using Python, Pandas, SQLite, and SQL.

The project combines two datasets:

* 👤 Users — subscription plans, countries, ages, favorite genres, and watch time.
* 🎬 Movies — titles, release years, runtime, genres, IMDb ratings, votes, and movie types.

The datasets are explored using Python and Pandas, then stored in SQLite for SQL-based analysis.

---

🎯 Project Objectives

The project explores:

* 👥 Subscriber behavior
* 💳 Subscription plans
* ⏱️ Watch time
* 🎭 Favorite genres
* 🎬 Movie characteristics
* ⭐ IMDb ratings and votes
* 📅 Release years
* 📊 Viewing patterns

---

🛠️ Technologies & Tools

* 🐍 Python
* 🐼 Pandas
* 🗄️ SQLite
* 💻 SQL
* 📊 Data Analysis

---

🔄 Project Workflow

📂 Load CSV Files → 🔎 Explore Data → ⚠️ Check Missing Values → 🗄️ Create SQLite Database → 📋 Create SQL Tables → 💻 Write Queries → 📊 Analyze Results → 💡 Extract Insights

---

🗄️ Database Structure

The SQLite database is called "netflix.db".

It contains two main tables:

👤 users

* "User_ID"
* "Name"
* "Subscription_Type"
* "Country"
* "Age"
* "Favorite_Genre"
* "Watch_Time_Hours"

🎬 movies

* "Title"
* "Release_Year"
* "Runtime"
* "Genre"
* "Rating"
* "Votes"
* "Kind"

---

💡 Analytical Questions

The project contains 20 SQL questions covering:

👥 Users & Subscriptions

* Subscribers by subscription type
* Average watch time by plan
* User percentage by plan
* Users by country
* Favorite genres
* Heaviest viewers
* Users with zero watch time
* Users aged 30+

🎬 Movies

* Movies released from 2000 onwards
* Longest and shortest movies
* Movies by release year
* Average duration by year
* Most-voted movies
* Highest-rated movies
* Movies without ratings
* Average rating by movie type
* Classic, Modern, and Recent movies

---

🧠 SQL Concepts

"SELECT" • "WHERE" • "ORDER BY" • "GROUP BY" • "HAVING" • "COUNT()" • "AVG()" • "ROUND()" • "CASE" • "Subqueries" • "CTE" • "ROW_NUMBER()" • "PARTITION BY" • "LIMIT"

---

🚀 Advanced SQL

The project uses:

* 🔹 Subqueries — comparing user watch time with the overall average.
* 🔹 CTEs — organizing complex queries.
* 🔹 Window Functions — using "ROW_NUMBER()" with "PARTITION BY".
* 🔹 CASE — classifying movies into:
  * 🎞️ Classic → Before 2005
  * 🎬 Modern → 2005–2017
  * 🍿 Recent → 2018 onwards

---

🎯 Final Goal

The goal is to demonstrate how raw streaming data can be transformed into meaningful analytical insights using Python and SQL.

---

<div align="center">🎬🍿 From Raw Data → SQL Analysis → Meaningful Insights 📊✨

Team 6

</div>
