# Scraping news media user comments

This repo contains an algorithm to scrape articles and user comments of Austrian newspaper der Standard.
Originally, I developed it for my MSc thesis **Measuring the comment gap: A machine learning and quantitative text analysis approach to studying news media user comments**
for the MSc Applied Social Data Science at London School of Economics. 

Required input:
* Timeframe of desired articles (date of publication)
* Genre of article

Output:
* list of article URLs in given timeframe
* dataframe containing article info (title, subtitle, article text, date, genre, ..)
* dataframe containing comment info (origin article, heading, text, username, upvotes, downvotes, replies, level of replies, ..)

It was built using R 4.3.1 and RStudio 2023.06.0-421.

📰 [Der Standard](https://www.derstandard.at/)

⚠ [derStandard Crawler Rules](https://about.derstandard.at/agb/)
When scraping, it is required to identify oneself by name and contact information.
Furthermore, there is a limit of 1 hit per second. 
