# British-Airways-Review-Dashboard
British Airways Review – Tableau Dashboard: An interactive Tableau dashboard analyzing British Airways customer reviews across overall rating, cabin staff, entertainment, food & beverages, ground service, seat comfort, and value for money, with trends, country insights, and aircraft-wise performance.

## Overview  
This project is an interactive **Tableau dashboard** built to analyze customer reviews of **British Airways**.  
It provides insights into passenger experiences by visualizing ratings across several service categories, aircraft types, countries, and travel classes.

The dashboard helps identify:
- How customer ratings have changed over time  
- Which countries rate the airline highest and lowest  
- Ratings across different aircraft models  
- Traveller type and seat class–based variations  
- Key performance metrics such as cabin crew, seat comfort, entertainment, food & beverages, ground service, and value for money

---

## Features  
### Interactive Filters
- Pick a Metric (Overall Rating, Cabin Staff Service, Entertainment, etc.)
- Seat Type (Economy, Business, First Class)
- Travel Type (Solo, Business, Family, Couple Leisure)
- Aircraft Type (A320, A321, Boeing 777, 787, 747, A380, etc.)
- Continent  
- Date Range

### Visualizations Included
- **KPI Cards:** Avg. Rating across 7 major service categories  
- **Line Chart:** Average Overall Rating by Month (2016–2024)  
- **Map:** Country-wise Average Rating  
- **Bar Charts:** Ratings by Aircraft & Total Number of Reviews  
- **Dynamic Filters** for slicing insights quickly  

## KPIs

The dashboard highlights the following KPIs derived from customer review data:

- **Average Overall Rating** – Measures the general satisfaction level of passengers.
- **Average Cabin Staff Service Rating** – Evaluates courtesy, responsiveness, and professionalism of crew members.
- **Average Entertainment Rating** – Assesses in-flight entertainment quality, content variety, and availability.
- **Average Food & Beverages Rating** – Captures passenger satisfaction with meals, snacks, and drinks offered onboard.
- **Average Ground Service Rating** – Reflects airport service quality including check-in, boarding, and baggage handling.
- **Average Seat Comfort Rating** – Measures comfort factors such as legroom, seat design, and overall seating experience.
- **Average Value for Money Rating** – Indicates whether passengers feel the service quality justifies the ticket price.
- **Number of Reviews** – Total volume of customer responses used to support the analysis.

These KPIs provide a high-level overview of British Airways' performance across essential service dimensions, enabling quick assessment and comparison across aircraft models, countries, seat types, and travel categories.

## Dataset & Technology Used
### Dataset
1. <a href = "https://github.com/Likith-Business-Analytics/British-Airways-Review-Dashboard/blob/main/ba_reviews.csv"> British_Airways <a/> – Contains British Airways customer reviews with fields such as:
- Review Date
- Country
- Traveller Type & Seat Type
- Aircraft Type
- Ratings: Overall, Cabin Staff Service, Entertainment, Food & Beverages, Ground Service, Seat Comfort, Value for Money

2. <a href = "https://github.com/Likith-Business-Analytics/British-Airways-Review-Dashboard/blob/main/Countries.csv"> Countries <a/> – Used for mapping country names to geographical coordinates for visualization.

### Technology Used
- **Tableau Desktop** – Dashboard creation and visual analytics
- **Excel** – Data storage and preprocessing

## Dashboard
<img width="1882" height="881" alt="image" src="https://github.com/user-attachments/assets/648987df-9925-4de2-b0bc-c3e4c014113a" />

## Key Insights
- **Overall Rating** remains around **4.0+**, indicating moderate customer satisfaction.
-  **Cabin Staff Service** shows strong performance with an average above **3.0**, while **Entertainment** scores lowest (~1.4), suggesting a key improvement area.
-  **Food & Beverages** and **Ground Service** score moderately (~2.4–3.0).
-  **Seat Comfort** and **Value for Money** show room for improvement (below 3.0).
-  **Ratings by Month** show fluctuations across years, with noticeable dips during global travel disruptions (2020–2021).
-  **Country-wise Ratings** vary significantly; regions like the UK, USA, and parts of Europe show higher satisfaction compared to others.
-  **Aircraft-specific analysis** shows:
    * Boeing 747-400 and 787 receive the highest ratings.
    * A319, A321, and older aircraft models get relatively lower scores.
    * Aircraft with the most reviews include **Boeing 777** and **A320 series**.
- **Traveller Type Comparison** reveals differing perceptions:
  * Business travellers generally rate higher,
  * Economy and family travellers show more mixed feedback.



## Conclusion

This Tableau dashboard provides a comprehensive view of British Airways’ customer satisfaction trends. By analyzing ratings across time, geography, aircraft type, and traveller categories, the dashboard highlights strong areas—such as cabin staff service—and identifies improvement opportunities in entertainment, seat comfort, and value for money. The insights enable airlines, analysts, and stakeholders to understand customer expectations and prioritize service enhancements.



