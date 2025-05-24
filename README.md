# Target-and-Walmart-Review-Sentiment-Analysis-using-BERT-and-LSTM
## Project Overview
This analysis investigates whether customer review data can help predict if a retail store is at risk of closure. Using Yelp reviews for over 500 Walmart and Target stores across the U.S., we combine Natural Language Processing (NLP), sentiment analysis, and machine learning to identify early warning signs of underperformance.

We aim to proactively flag distressed stores before financial indicators suggest closure, enabling data-driven operational strategies.

Team Members: Edselmo Biondi, Ibtehaj U Deen, Kavya Murugan, Piyush Gautam, Vineeth Kalyanaraman

# Research Question
Can customer sentiment and review content help predict whether a Walmart or Target store is still open or has closed?

# Why it Matters
- Allows retailers to identify struggling stores early, reducing financial loss and brand damage.
- Provides actionable insights from customer complaints on inventory, cleanliness, pricing, and service.
- Shifts decision-making from reactive to proactive, enabling smarter retail strategy.

# Methodology
Data Collection
- Yelp Open Dataset (1.5M reviews from 500+ stores)
- Review metadata: stars, length, sentiment score, unique users
- Business metadata: store location, open/closed status
NLP & ML Techniques
- Sentiment Analysis using VADER
- Topic Modeling with BERT & Zero-Shot Classification
- Binary Classification using:
   - Logistic Regression
   - Naïve Bayes
   - Support Vector Classifier (SVC)
   - Random Forest (Best Model)

# Key Results
## Random Forest achieved the best results:
  - Walmart: 94.08% accuracy
  - Target: 96.7% accuracy
# Key Issues Identified
  - Negative themes: Stockouts, rude staff, dirty stores, checkout delays
  - Positive themes: Price drops, friendly service, clean layout

# Business Impact
- Helps corporate teams prioritize interventions at high-risk stores
- Strengthens customer experience strategies using real-time feedback
- Provides early detection systems that integrate review data with financial performance

# Limitations
- Yelp data is user-generated and may not represent all customers
- External factors (e.g., lease expiration, local economy) not captured
- Sentiment scoring may miss sarcasm or mixed reviews

# Files Included
- Final_Draft_Team005.ipynb – Full model notebook
- Final_Presentation_CIS509.pptx – Project summary deck
- README.md – Project summary

