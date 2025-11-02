# 🏠 New York Airbnb Open Data Analysis

This project performs **extensive Exploratory Data Analysis (EDA)** and
**Sentiment Analysis** on the [New York Airbnb Open
Data](https://www.kaggle.com/datasets/rhonarosecortez/new-york-airbnb-open-data)
dataset from Kaggle.

------------------------------------------------------------------------

## 📊 Project Overview

The objective of this analysis was to uncover insights about Airbnb
listings in New York --- focusing on how **property features**,
**location**, and **review sentiments** influence pricing. The study
integrates visual analytics, statistical summaries, and sentiment
interpretation to draw meaningful conclusions for hosts and guests
alike.

All analyses were conducted using **Python** and standard data science
libraries, including:

`pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `nltk`,
`wordcloud`, and `scikit-learn`.

------------------------------------------------------------------------

## 🔍 Sub-Problem 1: What are the features/facilities/amenities of a property that affect its price?

### Key Insights

-   **Room Type:** Entire homes/apartments dominate listings and command
    the **highest prices**.
-   **Property Type:** Guesthouses, homes, and cottages are among the
    **most expensive**, while shared or private rooms are more
    affordable.
-   **Bedrooms:** A clear **positive correlation** exists between the
    number of bedrooms and the average price.
-   **Amenities:** High-priced listings frequently include **hot water,
    smoke alarms, coffee makers, fire extinguishers, and self check-in**
    --- comfort and safety drive higher valuation.

------------------------------------------------------------------------

## 📍 Sub-Problem 2: Are there particular locations in New York where Airbnb listings fetch higher prices?

### Summary --- Location-Based Price Analysis

-   Prices vary significantly by **neighborhood**.
-   **Fifteenth, Eighth, and Tenth Wards** record the **highest median
    prices**, marking them as premium zones.
-   **Sixth Ward** has the **most listings**, showing it's the most
    active Airbnb area.
-   **Second and Third Wards** show high listing volume but **moderate
    prices**.
-   **Boxplots** reveal high price variability and outliers in **Tenth
    and Eighth Wards**, reflecting luxury property presence.
-   Overall, **central and high-demand neighborhoods** fetch higher
    prices, while **peripheral wards** offer budget-friendly stays.

------------------------------------------------------------------------

## 💬 Sub-Problem 3: Does textual data in the summary and sentiments of reviews affect price?

### Key Findings

#### 1. WordCloud Analysis --- Top 100 Listings

-   High-priced listings emphasize words such as **"home," "private,"
    "restaurant," "spacious," and "Albany."**
-   These highlight **comfort, exclusivity, and premium location**,
    correlating with higher prices.

#### 2. WordCloud Analysis --- Bottom 100 Listings

-   Lower-priced listings use terms like **"apartment," "walking
    distance," "hospital," and "downtown."**
-   These focus on **convenience and affordability** rather than luxury
    or amenities.

#### 3. Sentiment Distribution

-   Most reviews show **strongly positive sentiments**, with few
    negative comments.
-   **Neutral reviews** appear mainly in the **0.4--0.7** range,
    reflecting descriptive or factual feedback.

#### 4. Price vs Reviews Correlation

-   A **very weak negative correlation (-0.04)** exists between price
    and number of reviews.
-   **Lower-priced listings** receive more guest engagement, while
    **higher-priced ones** attract fewer but likely **more satisfied
    guests**.

------------------------------------------------------------------------

## 🧠 Key Takeaways

-   Price dynamics are influenced by **room type, location, and
    amenities** rather than textual sentiment alone.
-   **Central areas** command higher prices but attract fewer reviews.
-   Positive sentiment dominates, indicating **overall guest
    satisfaction** in New York Airbnb stays.
-   The combination of **EDA + Sentiment Analysis** provides actionable
    insights for hosts to optimize pricing and for guests to identify
    value-for-money listings.

------------------------------------------------------------------------

## ⚙️ Tech Stack

  Category                    Tools / Libraries
  --------------------------- ------------------------------
  Data Processing             pandas, numpy
  Visualization               matplotlib, seaborn, plotly
  Text & Sentiment Analysis   nltk, wordcloud, TextBlob
  Machine Learning            scikit-learn
  Environment                 Python 3.x, Jupyter Notebook

------------------------------------------------------------------------

## ✨ Author

**Rutika Avinash Kadam**\
Data Science Graduate Student @ Stony Brook University\
📧 <rutika.kadam@stonybrook.edu>\
🔗 [GitHub](https://github.com/RutikaKadam10) \|
[LinkedIn](https://www.linkedin.com/in/rutikakadam10/)

------------------------------------------------------------------------
