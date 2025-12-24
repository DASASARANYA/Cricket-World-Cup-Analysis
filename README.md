Cricket World Cup 2023 Data Analysis
📌 Project Overview

This project performs a beginner to intermediate level data analysis of the ICC Men’s Cricket World Cup 2023 using Python in Google Colab.
The goal is to extract meaningful insights by combining match results, batting performance, bowling performance, and player information.

The project demonstrates core data analytics skills such as:

Data cleaning

Data merging (multiple tables)

Exploratory Data Analysis (EDA)

Data visualization

Insight generation

🎯 Objectives

Analyze batting and bowling performances across matches

Understand role-based player contributions

Study venue-wise match behavior

Compare team-wise overall performance

Combine multiple datasets for deeper insights

📂 Datasets Used
1️⃣ Match Data (match_schedule_results.csv)

Columns:

Match_no

Date

Venue

Team1

Team2

Winner

Scorecard URL

2️⃣ Batting Summary (batting_summary.csv)

Columns:

Match_no

Match_Between

Team_Innings

Batsman_Name

Batting_Position

Dismissal

Runs

Balls

4s

6s

Strike_Rate

3️⃣ Bowling Summary (bowling_summary.csv)

Columns:

Match_no

Match_Between

Bowling_Team

Bowler_Name

Overs

Maidens

Runs

Wickets

Economy

4️⃣ Player Information (world_cup_players_info.csv)

Columns:

player_name

team_name

battingStyle

bowlingStyle

playingRole

description

🛠 Tools & Technologies

Python

Pandas – data manipulation

Matplotlib & Seaborn – data visualization

Google Colab – development environment

🔄 Data Cleaning & Preparation

Verified missing values across datasets

Handled null values where required

Removed duplicate records

Standardized column names for merging

Converted numerical columns to correct data types

Ensured only existing columns were used (no assumptions)

🔗 Data Merging Strategy

Match_no was used to merge match, batting, and bowling data

player_name was used to merge player roles and team information

This created a unified structure enabling cross-dataset analysis

📊 Key Visualizations
📈 1. Total Runs by Player Role

Combined batting data with player roles

Compared contribution of batsmen, bowlers, and all-rounders

Insight:
Batsmen and all-rounders contributed the highest number of runs in the tournament.

📊 2. Venue-wise Runs and Wickets

Combined match, batting, and bowling data

Compared total runs scored and wickets taken at each venue

Insight:
Some venues were batting-friendly, while others favored bowlers, indicating pitch variation.

📊 3. Team-wise Performance (Runs + Wickets)

Combined team-level batting and bowling statistics

Compared overall balance between batting and bowling

Insight:
Top-performing teams showed strong balance between runs scored and wickets taken.

📌 Key Insights

Player roles significantly impacted match outcomes

All-rounders played a crucial role in team success

Venue conditions influenced match performance

Balanced teams consistently performed better
