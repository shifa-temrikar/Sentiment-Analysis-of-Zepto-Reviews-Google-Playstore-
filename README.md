# Sentiment-Analysis-of-Zepto-Reviews-Google-Playstore-
🔍 Project Overview

This project analyzes real-time customer reviews of the Zepto app collected from the Google Playstore.
The goal is to understand customer sentiment, highlight key issues, and derive insights to improve customer experience.

The pipeline includes:

- Data Collection (web scraping)

- Text Preprocessing (cleaning & lemmatization)

- Exploratory Data Analysis (EDA)

- NLP Sentiment Analysis using VADER

- Visualization & Insights

🛠️ Tech Stack

- Python

- Libraries: pandas, numpy, matplotlib, seaborn, nltk, vaderSentiment, wordcloud, google-play-scraper

📂 Dataset

- Scraped 1,000+ reviews directly from the Playstore using google-play-scraper.

- Collected fields:

- reviewId

- content (review text)

- score (rating)

- at (timestamp)


 📈Problem: High number of complaints about order cancellations.

 📊Insight from Analysis: Negative sentiment clusters heavily around the word “cancel” in 1★ and 2★ reviews.

 ⌛Action: Operations team can optimize inventory & delivery logistics → leading to fewer cancellations → improved customer trust.

 💡 Business Impact

This analysis helps Zepto’s business teams in the following ways:

1. Customer Experience Monitoring
   
- Quickly identifies whether customer sentiment is improving or declining over time.
- Allows product managers to track the effect of app updates, new features, or delivery policies.

2. Product & Operations Feedback

- Negative themes such as “late delivery”, “order cancellation”, and “payment failure” highlight operational issues that need immediate attention.
- Positive themes like “fast delivery”, “discounts”, and “user-friendly app” reinforce what customers value most, guiding feature prioritization.

3. Brand Reputation Management
   
- Real-time monitoring of reviews allows Zepto to respond quickly to customer complaints on Playstore, reducing churn risk.

4. Data-Driven Decisions

- Marketing teams can highlight strengths (quick delivery, discounts) in campaigns.

- Operations teams can focus on resolving weak points (cancellations, app crashes).

📊 Results & Insights

- 84.28% reviews were Positive

- 15.72% reviews were Negative

- Positive themes: fast delivery, convenience, discounts

- Negative themes: app crashes, payment failures, cancellations
