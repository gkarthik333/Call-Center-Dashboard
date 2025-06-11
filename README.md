# Call-Center-Dashboard 

# 💠 Project Overview
The Call Center Analysis project utilizes Power BI to analyze and evaluate key aspects of call center operations, including total calls, resolution rates, abandoned calls, agent performance, and customer satisfaction.
The analysis highlights patterns in call volume by time and day, identifies top-performing agents, and pinpoints areas needing improvement, such as response times and unresolved issues.
By providing interactive and visually intuitive dashboards, the project equips stakeholders with actionable insights to optimize resource allocation, improve service quality, and enhance customer satisfaction. - This data-driven approach supports better decision-making to address operational challenges effectively.

# 💠 Problem Statement:
* How can we reduce the number of abandoned calls and improve the overall call resolution rates?

* Which agents are performing well, and who requires additional support or training to enhance their efficiency?

* What are the key factors contributing to low customer satisfaction ratings, and how can they be addressed?

* Are there specific days or times when call volumes peak?

* How can we optimize response times and workload distribution among agents to improve service quality?

* What topics or issues generate the highest volume of calls, and how can we proactively address them?

* How can insights from this analysis help in resource planning and enhancing the customer experience?

# 💠 Data Source
This dataset is from PwC Switzerland Virtual Internship Program offered by Forage, which containing call records from a customer service center.
Each row represents a call with various attributes such as Call Id, Agent, Date, Time, Topic, whether it was Answered (Yes/No), Resolved, Speed of answer in seconds, and Average Talk Duration.
<p align="center" style="font-size: 9pt;"><a href="https://github.com/gkarthik333/Call-Center-Dashboard/blob/main/Call-Center-Dataset.csv">📂Download</a></p>

# 💠 Data Preparation
In the initial data preparation phase, we performed the following tasks:

* Data loading and inspection.

* Handling missing values.

* Data cleaning and formatting 

* Normalization, Standardisation and data modelling.

![Modelling](https://github.com/user-attachments/assets/43b6160c-c6be-4aac-aaa8-45cfa3e434f3)


# 💠 Project dashboard includes:-
➵ Page 1: Calls Analysis

➵ Page 2: Agent Analysis

# 💠 Insights & Findings
<br><br>

![Home](https://github.com/user-attachments/assets/7aae481b-41d2-4be1-86b1-16648c2f3076)

This homepage is professionally designed and branded with the PwC logo, is titled "Call Centre Analysis Dashboard," indicating its purpose is to provide insights into call center operations. It highlights three core analytical areas: "Calls Analysis," "Clients Satisfaction," and "Agents Performance." The design suggests a professional and user-friendly interface aimed at managers seeking quick performance overviews.

<br><br>

![Call Analysis](https://github.com/user-attachments/assets/f4145828-0746-458f-9ce0-15a6b5cf4d2b)
<br><br>


# 📞 Call Analysis

## 🎯 KPIs

➼ Total Calls :
5,000 calls were received in total during the selected time frame.

➼ Resolved % :
Out of the 4,054 answered calls, 89.94% (3,646) were resolved successfully.

10.06% (408) of the calls were unresolved, which highlights areas where better resolution processes might be needed.

➼ Abandoned % :
Out of the 5,000 calls, 18.92% (946) were abandoned Calls.
4,054 calls (81.08%) were successfully answered. This indicates a good response rate.


➼ Average Speed of Answer :
The average time to answer a call was 1 minute 8 seconds, indicating some delays in connecting with customers. Reducing this can improve customer satisfaction.

➼ Average Handle Time:
The average time taken to handle a customer interaction was 3 minutes 45 seconds. Optimizing this duration is key to enhancing operational efficiency and potentially improving customer satisfaction through quicker resolutions.

➼ Last Call Received:
The most recent customer interaction was received at 17:36:58 on 31 March 2021. This metric provides real-time awareness of activity, allowing for immediate insights into the operational status of the call center.

## 📈 Detailed Visual Analysis:
1] Decomposition Tree :
   Visualizes call flow from total calls to resolved calls (total → answered → resolved).

2] Calls By Months :
The data indicates that call volume started high in January at 1772 calls, then saw a significant decrease to 1616 calls in February. The volume remained relatively stable, with a slight further dip to 1612 calls in March. This trend suggests a decreasing call volume over the first quarter of the year.
  Adding a drill-down option to the "Calls by Months" chart enables users to click on any month to instantly reveal a day-by-day breakdown of call volumes, providing granular insights into daily fluctuations.

3] Total Calls by Weekday:
The call volume is highest on Monday (770) and Saturday (768), and slightly lower on weekdays like Tuesday (675).
Insights: Staffing on peak days like Monday and Saturday might need adjustment to handle higher traffic.

4] Answered and Abandoned Calls by Topic:
Calls related to Streaming and Payment Issues had the highest abandonment rates, despite being common topics.
Technical Support calls were handled relatively well, indicating better resolution processes in that area.

<br><br>

![Clients Satisfaction](https://github.com/user-attachments/assets/3a0c5a54-a4f6-4f7d-a8da-828797287ad2)

<br><br>

# 🌟 Clients Satisfaction

## 🎯 KPIs

- **Client Satisfaction Rate**: 68.07%
- it means that out of 4,054 customer interactions, approximately two-thirds resulted in a positive experience. While this indicates a majority of satisfied customers, it also highlights that nearly one-third were not fully pleased. This metric is crucial for identifying areas needing improvement to enhance overall customer experience and loyalty.

  
- **Overall Rating**: ⭐⭐⭐⭐☆ (3.4 / 5) – Neutral
-it suggests that while there are positive aspects, there's significant room for improvement. This rating indicates a moderate level of satisfaction that doesn't strongly lean towards either positive or negative, implying an opportunity to convert indifferent customers into advocates.

## 📈 Detailed Visual Analysis:

1] Donut Chart : 
   Quick visual summary of Client Satisfaction Rate in logo.

2] Satisfaction Rating by Agent:
* Martha has the highest rating (3.47), followed by Dan (3.45).
* Joe has the lowest rating (3.33), signaling areas for improvement in his service quality.

3] Satisfaction Rating by calls:
* A majority of calls received 3-star (1218) and 4-star (1180) ratings, indicating most customer experiences range from neutral to moderately satisfied.
* While 843 calls garnered 5-star ratings, reflecting strong satisfaction, a significant number (417 for 1-star, 396 for 2-star) point to considerable customer dissatisfaction.
* This distribution underscores the need to address the causes of lower ratings to convert dissatisfied and neutral customers into highly satisfied ones.

4] Satisfaction Rating by Topics:
* Top-rated: Admin Support received the highest satisfaction rating (3.43).
* Lowest-rated: Contract-Related topics had the lowest satisfaction rating (3.38), indicating a potential area for process or agent training improvement.

![Agents performance](https://github.com/user-attachments/assets/f28b9b05-547c-46f4-9573-7e476b50676c)


# 👨‍💼 Agents Performance 

## 🎯 KPIs

➼ Individual Level

* Agent Name & Rating:
Displays the individual agent's name, Pic alongside their personal satisfaction rating, using a star visual for quick perception of their overall performance quality.

* Total Calls:
Shows the complete number of calls the agent has managed, reflecting their total workload and contribution.

* Avg. Speed of Answer:
Measures how quickly the agent answers incoming calls, highlighting their responsiveness.

* Avg. Handle Time:
Indicates the average duration an agent spends on each call, reflecting their efficiency in resolving customer issues.

* Client Satisfaction Rate:
Represents the percentage of customers who reported satisfaction with this specific agent's service quality.

* Last Call Received:
Pinpoints the exact time the agent received their most recent call, offering real-time insight into their current activity.

➼ Overall Level:

* Most Issues Resolved:
Jim demonstrates exceptional problem-solving, having resolved the most customer issues, indicating high effectiveness.

* Most Calls Missed:
Diane has the highest number of missed calls, suggesting an area for review in her call handling or availability.

* Highest Overall Satisfaction Rating:
Martha achieves the highest customer satisfaction rating, reflecting her outstanding service quality.

* Quickest Answer:
Diane also shows remarkable responsiveness, recording the quickest average speed of answer among agents.

## 📈 Detailed Visual Analysis:

1] Answered Rate :
From the donut chart, users can visualize an agent's individual answered rate, as it dynamically updates to reflect the percentage of calls successfully handled by that specific agent according to applied slicer.

2] Resolved Rate :
From a donut chart, users can visualize an agent's individual resolved rate, as it dynamically updates to reflect the percentage of answered calls successfully brought to a conclusion by that specific agent according to applied slicer.

3] Total Calls by date:
This line chart visually represents the number of calls handled by agents on a daily basis for January, allowing for a clear understanding of daily workload fluctuations. It highlights the peak handling days and quieter periods, providing granular insight into agent activity levels and operational demands throughout the month.




✅ Findings and Recommendations:
1] Top Performers:
Jim is the top performer in terms of volume, resolving the highest number of calls. Martha excels in customer satisfaction, reflecting a customer-focused approach.

2] Improvement Areas:
Diane needs to address her high missed-call rate (132 missed calls), despite her quick response times. Joe should focus on improving resolution rates and customer satisfaction.

3] Balanced Workload:
Call volumes are fairly distributed among agents, but there is scope to adjust workloads for agents with higher abandonment rates to improve efficiency.

4] Response Times:
Improving the overall average speed of answer (67.52 seconds) could enhance customer satisfaction and reduce abandoned calls.


✅ Findings and Recommendations:
1] Call Handling:
With 946 calls abandoned, improving the availability of agents during peak hours can enhance response rates.
2] Customer Satisfaction:
An average rating of 3.40 indicates the need for better training, faster resolutions, and improved processes to enhance customer experience.
3] Resolution Rates:
While 72.92% resolution is good, focusing on unresolved calls can further improve customer trust and retention.
4] Peak Hours and Days:
Reinforce staffing during peak times (11 AM - 3 PM) and busier days (Monday and Saturday) to handle higher call volumes efficiently.
5] Topic-Specific Insights:
Focus on Streaming and Payment-related issues as these areas see high abandonment rates, which can negatively impact customer perception.

## 🧭 Interactivity
- **Filters:** Month Name, Day Name, Topic
- **Bookmark Toggle:** Between “Days” & “Topics” views and to switch views and analyze different agents individually.
- **Navigation Icons:** Home, Call Analysis, Client Satisfaction, Agent Performance.


## 🛠 Tools & Technologies Used

- **Power BI** – for dashboard design and interactivity
- **Excel** – initial data cleaning and preparation
- **DAX** – calculated measures (e.g., resolution rate, avg. time)

## 📈 Skills Demonstrated

- Data Cleaning
- KPI Development
- Dashboard Design
- Insight Communication
- Time Series & Categorical Analysis

## 👨‍💻 Author

**Karthik G K** - Data Analyst 
     📧  gkarthik647@gmail.com
     🔗  <a href="https://www.linkedin.com/in/karthikgk-id333">LinkedIn </a>
