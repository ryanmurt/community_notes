## **Abstract:**

Misinformation plays a powerful role in shaping events, decisions, and perceptions around the world. Common misinformation topics include: medical misinformation, political misinformation, and natural disaster misinformation. Despite these problems, Twitter (now X) laid off portions of its fact checking teams in late 2022, and decided to rely instead on its crowdsourced system Community Notes. With other platforms such as Youtube, Facebook, and TikTok considering similar moves, it’s critical to assess the ability of Community Notes to effectively add warnings to misleading content before crowdsourced fact checking becomes the norm in the fight against misinformation. Community Notes enables X users to sign up as contributors, submit explanatory notes on potentially misleading tweets, and rate notes submitted by others. Notes rated as "Helpful" by users from “different perspectives” are publicly displayed beneath the original post. Prior research indicates that Community Notes is effective at slowing the spread of misleading tweets once they are flagged with a warning. However, what about tweets that don’t get a warning? Research suggests that only a fraction of all submitted notes actually become warnings. Given the high stakes, we decided to dig further and investigate how well Community Notes adds warnings to misleading tweets. We manually labeled hundreds of tweets, in 7 topic areas, as “misleading” or “accurate/opinion,” and found that about 72% of misleading tweets, submitted to the Community Notes system, don’t get warnings. Furthermore, many misleading tweets without warnings have hundreds of thousands of views (median ~209K), meaning their spread and potential impact is significant. At least 2 factors contribute to this poor performance: low contributor-engagement, and lack of consensus across “different perspectives.” 


## **Repo Organization:**

Community Notes source data is available here: https://x.com/i/communitynotes/download-data

00_preprocessed_data.ipynb contains all code needed to install necessary libraries, load and merge source data, identify English language community notes, and saves file 'df.csv' to current directory. See CONFIGURATION in 3rd cell to read in data files.

01_data_analysis.ipynb reads in file 'df.csv', and contains code to run all exploratory data analysis.


