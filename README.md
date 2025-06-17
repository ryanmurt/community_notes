## **Abstract:**

We found that about 72% of misleading tweets, submitted to the Community Notes system, don’t get warnings.
Furthermore, many misleading tweets without warnings have hundreds of thousands of views (median ~208K),
meaning their spread and potential impact is significant. At least 2 factors contribute to this poor performance:
​low contributor-engagement, and lack of consensus across “different perspectives.”

## **[Read](https://medium.com/@ryanmurt/xs-fact-check-feature-leaves-too-much-unchecked-eab17e70edc9) Medium Article**

## **[View](https://public.tableau.com/app/profile/ryan.murtfeldt/vizzes) Tableau Dashboards**

## **Repo Organization:**

Community Notes source data is available here: https://x.com/i/communitynotes/download-data

**00_preprocessed_data.ipynb** contains all code needed to install necessary libraries, load and merge source data, identify English language community notes, and saves file 'df.csv' to current directory. See CONFIGURATION in 3rd cell to read in data files.

**01_data_analysis.ipynb** reads in file 'df.csv', and contains code to run all exploratory data analysis.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

