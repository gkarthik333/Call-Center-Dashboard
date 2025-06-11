# Call-Center-Dashboard 
A call center dashboard is a visual tool that provides a real-time overview of key performance indicators (KPIs) and operational metrics related to a call or contact center. It's designed to help managers and agents monitor performance, identify trends, and make informed decisions to improve efficiency and customer satisfaction.

# 💠 Project Overview
The Call Center Analysis project utilizes Power BI to analyze and evaluate key aspects of call center operations, including total calls, resolution rates, abandoned calls, agent performance, and customer satisfaction.
The analysis highlights patterns in call volume by time and day, identifies top-performing agents, and pinpoints areas needing improvement, such as response times and unresolved issues.
By providing interactive and visually intuitive dashboards, the project equips stakeholders with actionable insights to optimize resource allocation, improve service quality, and enhance customer satisfaction. - This data-driven approach supports better decision-making to address operational challenges effectively.

# 💠 Problem Statement
-How can we reduce the number of abandoned calls and improve the overall call resolution rates?

Which agents are performing well, and who requires additional support or training to enhance their efficiency?

What are the key factors contributing to low customer satisfaction ratings, and how can they be addressed?

Are there specific days or times when call volumes peak?

How can we optimize response times and workload distribution among agents to improve service quality?

What topics or issues generate the highest volume of calls, and how can we proactively address them?

How can insights from this analysis help in resource planning and enhancing the customer experience?

# 💠 Data Source
This dataset is from PwC Switzerland Virtual Internship Program offered by Forage, which containing call records from a customer service center.
Each row represents a call with various attributes such as Call Id, Agent, Date, Time, Topic, whether it was Answered (Yes/No), Resolved, Speed of answer in seconds, and Average Talk Duration.
📂<p align="center" style="font-size: 9pt;"><a href="https://github.com/gkarthik333/Call-Center-Dashboard/blob/main/Call-Center-Dataset.csv">Download</a></p>

# 💠 Tools Used
Microsoft Excel - Data Cleaning
PowerBI - DAX, Creating Visualizations , Creating Dashboard

# 💠 Data Preparation
In the initial data preparation phase, we performed the following tasks:

* Data loading and inspection.

* Handling missing values.

* Data cleaning and formatting

# 💠 Project dashboard includes:-
➵ Page 1: Calls Analysis

➵ Page 2: Agent Analysis

# 💠 Insights & Findings


![Home](https://github.com/user-attachments/assets/7aae481b-41d2-4be1-86b1-16648c2f3076)

This homepage is professionally designed and branded with the PwC logo, is titled "Call Centre Analysis Dashboard," indicating its purpose is to provide insights into call center operations. It highlights three core analytical areas: "Calls Analysis," "Clients Satisfaction," and "Agents Performance." The design suggests a professional and user-friendly interface aimed at managers seeking quick performance overviews.

<br><br>

![Call Analysis](https://github.com/user-attachments/assets/f4145828-0746-458f-9ce0-15a6b5cf4d2b)

# 📞 Call Analysis

KPI's:

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

✅ Detailed Visual Analysis:
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

![Call Analysis](https://github.com/user-attachments/assets/1e48c401-591d-4360-a69f-4df37ebe58db)







✅ Filters and Interactivity:
The dashboard includes several filters for:

- Date:
Users can adjust the time frame to view specific periods.

- Month:
Allows analysis of monthly trends.

Agent and Topic:
Helps to drill down into individual agent performance or specific call topics.


✨ Page 2: Agent Analysis
Screenshot 2024-05-06 151010

➼ Total Agents:
The dashboard analyzes the performance of 8 agents.

➼ Total Calls:
5,000 calls were received, with 4,054 calls (81.08%) answered.

➼ Most Issue Resolved:
Jim resolved the highest number of calls (485 calls) among all agents, showcasing exceptional problem-solving efficiency.

➼ Most Calls Missed:
Diane missed the most calls (132 calls) during this period, indicating areas for improvement in her availability or call-handling capacity.

➼ Highest Customer Satisfaction Rating:
Martha achieved the highest satisfaction rating of 3.47 out of 5, showing her ability to handle calls with high-quality service.

➼ Quickest to Answer:
Diane had the fastest average speed of answer at 66.2 seconds, highlighting her responsiveness.

✅ Detailed Visual Analysis:
1] Answered Calls by Agents:
The highest number of calls answered was by Jim (536 calls), followed by Martha (514 calls).

Stewart answered the least number of calls (477 calls), indicating either fewer assigned calls or potential inefficiency.

2] Resolved Calls by Agents:
Jim leads in resolved calls (485 resolved out of 536 answered), reflecting his efficiency.

Joe has the lowest number of resolved calls (436 resolved out of 484 answered), which might indicate challenges in resolving customer issues.

3] Total Calls by Agent:
Jim handled the most total calls (638 calls), while Stewart handled the least (582 calls).

The relatively balanced distribution suggests a fair allocation of calls among agents.

4] Average Speed of Answer by Agent:
Diane is the quickest to respond (66.2 seconds), while Joe is the slowest (71.5 seconds).

Faster response times generally contribute to better customer satisfaction.

5] Satisfaction Rating by Agent:
Martha has the highest rating (3.47), followed by Dan (3.45).

Joe has the lowest rating (3.33), signaling areas for improvement in his service quality.

6] Agent Statistics Table:
Provides a clear overview of each agent's performance in terms of:

Answered Calls
Abandoned Calls
Resolved Calls
Average Satisfaction
Average Speed of Answer For instance, Martha has a low abandonment rate (124 calls) and high customer satisfaction, making her one of the top-performing agents.
✅ Findings and Recommendations:
1] Top Performers:
Jim is the top performer in terms of volume, resolving the highest number of calls. Martha excels in customer satisfaction, reflecting a customer-focused approach.

2] Improvement Areas:
Diane needs to address her high missed-call rate (132 missed calls), despite her quick response times. Joe should focus on improving resolution rates and customer satisfaction.

3] Balanced Workload:
Call volumes are fairly distributed among agents, but there is scope to adjust workloads for agents with higher abandonment rates to improve efficiency.

4] Response Times:
Improving the overall average speed of answer (67.52 seconds) could enhance customer satisfaction and reduce abandoned calls.

This dashboard provides actionable insights for managers to recognize high-performing agents, address challenges in low-performing areas, and optimize the call center's overall efficiency.

✅ Overall Insights:
➼ Call Metrics:
Out of 5,000 total calls, 81% (4,054 calls) were answered, while 946 calls (19%) were abandoned.
72.92% of answered calls were resolved, indicating room for improvement in issue resolution efficiency.
➼ Call Volume Trends:
Monday and Saturday had the highest call volumes, while weekdays like Tuesday had comparatively lower volumes.
Peak call hours were observed between 10 AM and 2 PM, with a notable drop after 5 PM.
➼ Agent Performance:
Jim resolved the highest number of issues (485) and handled the most calls, while Diane had the most missed calls.
Martha had the highest average satisfaction rating (3.47), while Joe had the lowest (3.33).
Becky had the fastest average speed of answer (65.3 seconds), while Joe had the slowest (71.5 seconds).
➼ Customer Satisfaction:
The average satisfaction rating across the call center was 3.4 out of 5, indicating a need to address service quality and efficiency.






➼ Average Satisfaction Rating:
Rating : 3.40 out of 5, indicating an average level of customer satisfaction. There is room for improvement in terms of providing a better customer experience.




3] Total Calls by Hour:
Calls peak between 11 AM to 3 PM, with 12 PM being the busiest hour (590 calls).
The volume drops sharply after 5 PM.
Insights: Agents should be more available during peak hours for better handling of call volumes.

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



## 🎯 KPIs

- **Total Calls**: 5,000
- **Resolved Calls**: 3,646 (89.94%)
- **Abandoned Calls**: 946 (18.92%)
- **Average Speed of Answer**: 1 minute 8 seconds
- **Average Handle Time**: 3 minutes 45 seconds
- **Last Call Received**: 31 March 2021, 17:36:58

## 📈 Visuals
#### Sankey Chart
   Visualizes call flow from total calls to resolved calls (total → answered → resolved).

#### Line/Area Chart
   Calls by Date : Shows daily call trends

#### Bar Chart
* **Calls by Day Name :**
    Weekly breakdown of answered vs unanswered calls.
* **Calls by Topic :**
    Topic wise breakdown of answered vs unanswered calls.

![Call Analysis](https://github.com/user-attachments/assets/4a674125-5fd5-4acc-8277-2a1269d6a3ca)


# 🌟 Clients Satisfaction

## 🎯 KPIs

- **Client Satisfaction Rate**: 68.07%
- **Overall Rating**: ⭐⭐⭐⭐☆ (3.4 / 5) – Neutral

## 📈 Visuals
#### Donut Chart
* **Client Satisfaction Rate :**
    Quick visual summary of satisfaction %.

#### Card & Star Indicator
* **Overall Rating :**
    Shows average rating with 5-star visual and label.
#### Bar Chart
* **Count of Call IDs by Ratings:**
    * Visualize how many users gave each star rating.
    * Most customers gave 3 or 4 stars.

* **Satisfaction Rating by Topics:**
    * Top-rated: Admin Support (3.43)
    * Lowest-rated: Contract Related (3.38)

 #### Bar Chart
* **Count of Call IDs by Ratings:**
    * Visualize how many users gave each star rating.
    * Most customers gave 3 or 4 stars.

* **Satisfaction Rating by Topics:**
    * Top-rated: Admin Support (3.43)
    * Lowest-rated: Contract Related (3.38)


![Client Satisfaction](https://github.com/user-attachments/assets/516a1de8-b001-46b9-9e52-cbabad51e0f8)

# Agents Performance 

## 🎯 KPIs

- **Agent Name & Rating**: Personal rating with star visual for easy perception.
- **Total Calls**: Total workload handled.
- **Avg. Speed of Answer**: Measures responsiveness.
- **Avg. Handle Time**: Indicates efficiency in resolving calls.
- **Client Satisfaction Rate**: Quality perception.
- **Last Call Received**: Recent activity tracking.


## 📈 Visuals
#### Donut Chart
- **Answered Rate :**
     * Visualizes the percentage of calls answered vs not answered.
     * Highlights agent responsiveness.
-**Resolved Rate :**
     * Shows the split between resolved and unresolved calls. 
     * Measures agent issue resolution effectiveness.


#### Line & Area Chart
– **Total Calls by Date :**
     * Displays daily call volume trends for the selected agent.
     * Helps identify workload peaks and performance patterns..

![Agents Performance](https://github.com/user-attachments/assets/5f49eb82-e555-4d7b-a8b5-6c4fdecae396)

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
