🍽️ Zomato Restaurant Market Analysis: Data-Driven Growth Strategies
  
📌 Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on the Zomato restaurant dataset. Unlike standard data analysis that focuses solely on visualization, this project aims to diagnose business problems—specifically identifying the "Service Gap" in online delivery, the geographic concentration risk, and the price-segmentation trap that affects revenue scalability.
Key Objective: To transform raw transactional data into a strategic roadmap for vendor onboarding and revenue optimization.

--------------------------------------------------------------------------------
📂 Dataset & Architecture
The analysis is based on two primary datasets merged to create a global view of the restaurant ecosystem:
1. zomato.csv: Contains 9,551 records with features including Average Cost for two, Has Online delivery, Aggregate rating, and Cuisines.
2. Country-Code.xlsx: A dimension table used to map country codes to actual names, enabling geographic segmentation.
Tech Stack:
• Python: Core programming.
• Pandas & NumPy: Data cleaning, merging, and currency normalization.
• Matplotlib & Seaborn: Static visualizations (Boxplots, Heatmaps, Stacked Bar Charts).

--------------------------------------------------------------------------------
🔍 Key Analysis & Insights
1. The "90/10" Geographic Monopoly
• Observation: The dataset is heavily skewed, with India accounting for 94.4% of all listings. Within India, the New Delhi/NCR region holds over 70% of the inventory.
• Business Implication: Zomato functions as a hyper-local utility in North India but merely as a directory (discovery only) in international markets like the US and UK, where delivery penetration is zero in this dataset.
• Action: Global strategies cannot be generalized; models must be segmented by Country to avoid currency and cultural bias.
2. The "Service Gap" (Revenue Opportunity)
• Online Delivery: Only 25.7% of restaurants offer online delivery.
• Table Booking: Only 12.1% offer table booking.
• Strategic Insight: There are over 6,000 verified restaurants in the Indian market that are listed but not monetized via delivery logistics. This represents the immediate Total Addressable Market (TAM) for the sales team.
3. The "Average" Quality Trap
• Rating Distribution: The data follows a Gaussian distribution centered around 3.1 - 3.2.
    ◦ Average (2.5–3.4): ~40-50% of restaurants.
    ◦ Not Rated (0.0): ~22% of restaurants (2,148 partners).
• Insight: The "0" ratings represent a cold-start problem (onboarding issues), not negative customer sentiment. These partners need a "First 5 Reviews" campaign to build social proof.
4. Cuisine & Pricing Strategy
• North Indian cuisine dominates the Low and Medium price tiers (Volume Drivers).
• Consumer Shift: As price sensitivity decreases (moving to Very High price range), consumer preference shifts significantly toward Italian and Continental cuisines.
• Recommendation: To drive higher Average Order Value (AOV), Zomato Gold/Pro marketing should target Italian/Continental clusters.

--------------------------------------------------------------------------------
📊 Visualizations Included
The notebook includes "Boardroom-Ready" visualizations with data labels and strategic color coding:
1. 100% Stacked Bar Charts: To show the shift in Table Booking penetration across countries.
2. Correlation Heatmaps: Analyzing the relationship between Price range, Votes, and Aggregate rating.
3. Boxplots with Semantic Colors: Validating rating thresholds (Red for Poor, Green for Excellent).
4. Geographic Pie Charts: Visualizing the massive market imbalance favoring New Delhi.

--------------------------------------------------------------------------------
🚀 Strategic Recommendations (The "So What?")
Based on the data, the following actions are recommended for the business stakeholders:
1. Aggressive Internal Conversion: Stop focusing on acquiring new restaurants. Focus on converting the 7,100 existing "Listing-Only" partners into "Delivery Partners."
2. Tier-2 City Expansion: The NCR market is saturated. Growth teams should pivot to under-represented metros like Pune, Bangalore, and Mumbai, which show low density in this dataset relative to their population.
3. Vendor Quality Consulting: Launch B2B training for the ~4,000 "Average" rated restaurants to improve hygiene and service, thereby lifting the platform's NPS.

--------------------------------------------------------------------------------
🧠 Learning Outcome
This project strengthened practical skills in:
Data cleaning and preprocessing
Feature engineering and aggregation
Visualization and storytelling using data
Extracting meaningful business insights from real-world datasets

--------------------------------------------------------------------------------
👤 Author
Data Analyst | Strategic Problem Solver Focusing on translating raw data into revenue-generating business insights.
