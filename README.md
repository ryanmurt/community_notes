## **Abstract:**

Misinformation is a major force in global affairs. In late 2022, Twitter (now X) laid off portions of its fact-checking teams, and went all-in with its “crowd sourced” system Community Notes. With other platforms such as Youtube, Facebook, and TikTok considering similar moves, it’s critical to assess the ability of Community Notes to effectively flag misleading content before it becomes the norm in the fight against misinformation. Community Notes enables X users to sign up as contributors, submit explanatory notes on potentially misleading tweets, and rate notes submitted by others. Notes rated as "helpful" by a diverse group of users are publicly displayed beneath the original post. Prior studies have evaluated the system primarily by examining the proportion of submitted notes that are ultimately displayed. While this metric highlights important limitations, it is insufficient given that 38% of noted-tweets contain either accurate or opinion-based content. To address this, our study shifts the focus to recall, the percentage of misleading tweets that go unflagged. Our findings show that 72% of misleading tweets are not flagged by the Community Notes system. Low engagement is a significant contributor to this failure, and we hypothesize that low consensus among contributors may also play a major role. We propose that future research leverage X’s note-ranking algorithm to measure ideological disagreement and assess its relationship to low consensus and recall rates.


## **Repo Organization:**

Community Notes source data is available here: https://x.com/i/communitynotes/download-data

00_preprocessed_data.ipynb contains all code needed to install necessary libraries, load and merge source data, and identify English language community notes, and saves file 'df.csv' to current directory. See CONFIGURATION in 3rd cell to read in data files.

01_data_analysis.ipynb reads in file 'df.csv', and contains code to run all exploratory data analysis.


