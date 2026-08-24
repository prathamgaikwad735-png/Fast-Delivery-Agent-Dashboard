# Fast Delivery Agent Performance Dashboard
An Excel dashboard analyzing delivery agent performance (Blinkit, JioMart, Swiggy Instamart, Zepto) across 10 Indian cities using a Location slicer to break down delivery time, product availability, agent ratings, and customer feedback city-wise.

## Objective
To analyze how fast-delivery agents (Blinkit, JioMart, Swiggy Instamart, Zepto) perform across cities, and identify:
- Which agent has the best delivery time, rating, and customer feedback in each city
- Which product categories dominate in each city
- Which agent performs most consistently across all metrics, city-wise

## Quick Nevigation
- <a href="https://github.com/prathamgaikwad735-png/Fast-Delivery-Agent-Dashboard/blob/main/Fast%20Delivery%20Agent%20Reviews.xlsx">Dataset</a>
- <a href="Key-Questions-/KPIs">Key Questions / KPIs</a>


<h2><a class="anchor" id="key-Questions / KPIs"></a>Key Questions / KPIs</h2>
- Price Range's Avg Delivery Time — Which price range (High/Low/Medium) takes the longest to deliver?
- Order Types – Products Availability — Which product category is most available in each city?
- Agent's Customer Service Rating — Which agent has the best customer service rating in each city?
- Agent's Avg Rating — Which agent has the highest overall average rating?
- Customer Feedback Type by Agent — Which agent receives the most positive/negative feedback?
Overall (unfiltered) numbers: Avg Rating 3.0 | Avg Delivery Time 35 minutes

# Process & Methodology
1.	Data Source: Delivery agent order-level data (city, price range, delivery time, product category, ratings, feedback) collected and loaded into Excel.
2.	Slicer Setup: A single Location (City) slicer was used (Excel PivotTable/PivotChart Slicer), allowing the entire dashboard to filter to a specific city with one click.
3.	Charts Built (Excel PivotCharts): Price Range's Average Delivery Time, Order Types – Products Availability, Agent's Customer Service Rating, Agent's Avg Rating, Customer Feedback Type by Agent.
4.	Analysis Approach: Each city was selected on the slicer, and the exact numbers from all 5 charts were recorded from the dashboard screenshots below.
5.	Screenshots: A screenshot was captured for each city view (11 total — 1 overview + 10 cities), included below.

## -	Overview 

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/b255f354-f10a-4159-83fd-f13bcf40044d" />

Analyze : Avg Rating 3.0 | Avg Delivery Time 35 min | Delivery time nearly flat across price ranges (High 35, Medium 36, Low 35)
Insight: At the aggregate level, delivery time stays close to 35 minutes regardless of price range, and no single agent leads decisively — performance only differentiates once the data is broken down city-wise.

## 1. Ahmedabad

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/3c9cd26e-9fba-4afb-a42c-ea6f63ee9b11" />


Analyze : Delivery Time — High 35, Low 35, Medium 37 min | Pharmacy leads availability (121 products) | Customer Service Rating: Swiggy Instamart 3.12 (highest) | Agent Avg Rating: JioMart 3.18 (highest) | Positive Feedback: Zepto 50 (highest)
Insight: Medium-priced orders take the longest to deliver in Ahmedabad. Swiggy Instamart leads on service rating and JioMart on overall rating, but Zepto receives the most positive feedback — three different agents lead three different metrics.

## 2. Chennai

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/1b198db2-0cc3-47e3-850d-e8a31cbebb52" />

 
Analyze : Delivery Time — High 34, Low 35, Medium 33 min | Grocery leads availability (122 products) | Customer Service Rating: JioMart 3.17 (highest) | Agent Avg Rating: Swiggy Instamart 3.15 (highest) | Feedback: Blinkit 44 positive, 51 negative (highest on both)
Insight: Grocery is the top category in Chennai. Blinkit stands out with both the highest positive and highest negative feedback counts — its service quality appears inconsistent across orders.

## 3. Hyderabad


<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/8ee053be-8fef-4263-88b5-564fba1ab8c4" />

 
Analyze : Delivery Time — High 35, Low 37 (slowest), Medium 36 min | Grocery leads availability (108 products) | Customer Service Rating: Swiggy Instamart 2.97 (highest) | Agent Avg Rating: Swiggy Instamart 3.17 (highest) | Positive Feedback: Blinkit 59 (highest)
Insight: Low-price orders are the slowest to deliver in Hyderabad. Swiggy Instamart tops both rating metrics, while Blinkit receives the most positive feedback — rating leadership and feedback leadership belong to different agents.

## 4. Kolkata

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/1abccdc9-6733-44cd-9b61-bca14121462c" />

 
Analyze : Delivery Time — High 34, Low 34, Medium 36 (slowest) min | Essentials lead availability (113 products) | Customer Service Rating: Blinkit & JioMart tied at 3.07 (highest) | Agent Avg Rating: Zepto & Blinkit tied at 3.08 (highest) | Positive Feedback: Swiggy Instamart 45 (highest)
Insight: Essentials dominate product availability in Kolkata. Blinkit is strong on both rating metrics, but Swiggy Instamart receives the most positive feedback among all agents.

## 5. Mumbai

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/ab9e8370-8460-42ff-88f1-b90265d144ee" />

 
Analyze : Delivery Time — High 34, Low 37 (slowest), Medium 35 min | Availability fairly balanced across categories (90–106 range) | Customer Service Rating: JioMart 3.07 (highest) | Agent Avg Rating: Zepto 3.11 (highest) | Feedback: JioMart 50 positive, 48 negative (highest on both)
Insight: Low-price orders take the longest in Mumbai. JioMart has both the highest service rating and the highest feedback volume — positive and negative — indicating it handles the largest share of orders in this city.

## 6. Bangalore

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/4eae1de7-bb56-44ec-801c-e627452f1b05" />

 
Analyze : Delivery Time — High 35, Low 35, Medium 34 min (flat, ~34–35 min) | Availability fairly balanced, highest category ~113 | Customer Service Rating: Swiggy Instamart 2.86 (highest) | Agent Avg Rating: Swiggy Instamart 3.11 (highest) | Positive Feedback: Blinkit 47 (highest)
Insight: Delivery time in Bangalore stays consistently in the 34–35 minute range across price levels. Swiggy Instamart leads both rating metrics, while Blinkit receives the most positive feedback.

## 7. Delhi

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/5085c42f-74c3-4f8f-ae6d-4862bd88d9c7" />


 
Analyze : Delivery Time — High 34, Low 37 (slowest), Medium 32 min | Food leads availability (120 products) | Customer Service Rating: Blinkit 3.21 (highest) | Agent Avg Rating: Blinkit 3.04 (highest, narrowly over Swiggy Instamart 3.03) | Positive Feedback: Swiggy Instamart & Zepto tied at 43 (highest)
Insight: Food is the leading category in Delhi. Blinkit leads on both rating metrics, while Swiggy Instamart and Zepto are tied for the most positive feedback.

## 8. Jaipur

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/145b4139-430d-4a2a-abda-24d409861228" />



 
Analyze : Delivery Time — High 36, Low 36, Medium 35 min | Essentials lead availability (109 products) | Customer Service Rating: Zepto 3.19 (highest) | Agent Avg Rating: JioMart 3.06 (highest) | Positive Feedback: Blinkit 65 (highest)
Insight: Essentials dominate availability in Jaipur. Zepto leads on service rating and JioMart on overall rating, but Blinkit's 65 positive responses is the highest single feedback count across all 10 cities.

## 9. Lucknow

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/748dfd64-9326-4704-800f-ddd7bb6a3efd" />



 
Analyze : Delivery Time — flat across all price ranges (~35 min) | Electronics leads availability (110 products) | Customer Service Rating: JioMart 3.16 (highest, narrowly over Blinkit 3.15) | Agent Avg Rating: Zepto 3.07 (highest) | Positive Feedback: fairly close across agents (33–36 range)
Insight: Lucknow is the only city where Electronics is the top category. Ratings are closely contested between JioMart and Blinkit, with Zepto leading on overall rating, and positive feedback is spread evenly across all four agents.

## 10. Pune

<img width="938" height="531" alt="image" src="https://github.com/user-attachments/assets/1bca3f10-b5ce-488c-a6f9-436225517686" />


 
Analyze : Delivery Time — High 35, Low 35, Medium 33 min | Food leads availability (110 products) | Customer Service Rating: Swiggy Instamart 3.14 (highest) | Agent Avg Rating: JioMart 3.08 (highest, narrowly over Zepto 3.07) | Positive Feedback: Zepto 51 (highest)
Insight: Food is the top category in Pune. Swiggy Instamart leads on service rating, JioMart narrowly leads on overall rating, and Zepto receives the most positive feedback.

# Conclusion
-	Delivery Time: Bangalore and Lucknow are the most consistently fast (~34–35 min flat); Hyderabad, Mumbai, and Delhi each have a slowest segment reaching 37 minutes.
-	Category Trend: Grocery and Essentials dominate most cities; Electronics is the top category only in Lucknow, Food leads in Delhi and Pune, and Pharmacy leads in Ahmedabad.
-	Highest Customer Service Rating by City: Swiggy Instamart (Ahmedabad, Hyderabad, Bangalore, Pune), JioMart (Chennai, Mumbai, Lucknow), Zepto (Jaipur), Blinkit (Delhi), Blinkit/JioMart tied (Kolkata)
-	Highest Positive Feedback by City: Zepto (Ahmedabad, Pune), Blinkit (Chennai, Hyderabad, Bangalore, Jaipur), Swiggy Instamart (Kolkata), JioMart (Mumbai), Swiggy Instamart/Zepto tied (Delhi)
	
## Key Observation: In 8 out of 10 cities, the agent with the highest customer service rating is not the same agent with the highest positive feedback. This shows rating and feedback measure different things — ratings reflect the immediate service score, while feedback reflects overall customer sentiment. Blinkit appears most frequently as the top positive-feedback agent across cities (4 out of 10), making it the most consistently well-received agent on customer sentiment nationally.

## Tools Used
- Microsoft Excel (Dashboard, PivotTables, PivotCharts, Slicers)







