# U.S. Airfare Trends and Regional Competition Analysis
**Capstone Project – Nashville Software School | DA15 | 2025**  
**Author: Maria Camila Neal**

## Project Overview
This project investigates U.S. airfare trends, competition, and regional pricing dynamics between 1996 and 2025 using data from the U.S. Department of Transportation (DOT). The analysis focuses on how airline competition, low-cost carriers, and regional factors influence average airfare and passenger demand over time.

## Objectives
- Examine fare trends across U.S. regions over a 30-year period.
- Compare low-cost versus traditional carriers and their impact on pricing.
- Analyze whether higher competition leads to lower fares.
- Study regional differences in volatility and growth.
- Identify patterns in origin and destination traffic across major U.S. cities.

## Key Insights
- Low-cost carriers significantly reduce fares, especially in the South and West regions.
- Competition does not always lead to lower prices; demand, route type, and distance strongly influence airfare levels.
- The Northeast and South exhibit lower volatility, indicating more stable pricing trends.
- Passenger volumes have steadily increased, reflecting rising travel demand nationwide.

## Tools and Technologies
| Tool | Purpose |
|------|----------|
| Python (Pandas, NumPy, Seaborn, Matplotlib) | Data cleaning, preparation, and analysis |
| Power BI | Data visualization and dashboard design |
| Jupyter Notebook | Exploratory data analysis and documentation |
| U.S. DOT Data Portal | Source for airfare and airline datasets |

## Data Sources
- Consumer Airfare Report Table 1A – All U.S. Airport Pairs  
- Consumer Airfare Report Table 3 – Fare Increases  
- Consumer Airfare Report Table 4 – Fare Decreases  
- Airline Codes Dataset – Bureau of Transportation Statistics

## Process Summary
1. **Data Preparation:**  
   Merged multiple datasets from the DOT, removed missing or duplicate values, standardized column names, and filtered out incomplete years (1993–1995).  

2. **Data Preparation:**  
   Added regional classifications based on the U.S. Census Bureau.  
   Categorized airlines as low-cost or traditional.  
   Created calculated metrics for fare volatility, percent change, and competition levels.

3. **Exploratory Data Analysis:**  
   Conducted initial exploration using Python libraries to identify patterns and relationships between fares, passengers, and carriers.

4. **Visualization:**  
   Designed a Power BI dashboard illustrating fare trends, regional differences, and the effects of competition and low-cost carriers.

## Dashboard Overview
Link: [Airfare Trends Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzkyMWExMTQtYTE1Yi00MmQ1LTliODgtMzUzN2VlMWM2YjIwIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9)


The interactive Power BI dashboard visualizes:  
- Regional fare trends over time  
- Competition effects by number of carriers  
- Low-cost versus traditional carrier comparisons  
- Origin and destination region patterns  
- Passenger growth over time  

## Reflection
This project integrates my passion for travel and data. By analyzing 30 years of airfare data, I explored how competition, distance, and airline strategies shape air travel accessibility across the United States. This process strengthened my analytical skills and deepened my understanding of how data can reveal patterns within large-scale transportation systems.
