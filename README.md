# UK Train Station Analysis
This analysis explores the operational performance and refund behavior of customers for a United Kingdom train service company. 

### Project Objective
The objective of this analysis is to uncover patterns in journey delays, cancellations, and refund requests, and assess their financial impact. By examining factors such as journey status, ticket type, delay reasons, time patterns, and route performance, I am able to identify inefficiencies, patterns and gaps to provides data-driven insights to support operational improvements, reduce revenue loss and improve the general customer experience.

### Project Background
Train services in the UK operate in a fast-paced environment and competitive market where millions of passengers rely on timely journeys for work, travel, and personal reasons. Train operators often report strong  performances but hidden within it are underlying problems that still affect customer experience and company revenue.

Delays, cancellations, and refund requests directly reduce profitability. Even small disruptions can trigger refund claims, leading to large revenue losses in the long run.

This analysis focuses on understanding how journey disruptions influence refund behavior and financial performance. By examining operational trends and customer reactions, this analysis reveals where and how the company is losing money and what can be improved. This allows the company reduce avoidable losses, improve service reliability, and build passenger trust

### Business Needs
- Pinpoint internal operational factors causing delays and cancellations.
- A better understanding of what triggers refunds and how passenger behavior changes.
- Insight into which routes, ticket types, and delay reasons are causing the revenue losses.
- Develop targeted strategies for preventing delays and cancellations.
- Clear guidance on operational actions that reduce refund claims, especially when delays cross critical thresholds.
- Policies that help retain revenue without harming customer experience.
- A way to prioritize improvements based on financial impact and general performance statistics
- A foundation for predictive analytics to preempt delays and optimize resource allocation, ultimately strengthening profitability and passenger satisfaction

### Stakeholders and their Analytical Needs
Operations Managers:
- Need to know which routes and stations are causing the most delays and cancellations.
- Require insights into what types of issues (technical, staffing, scheduling) are most responsible for underlying problems.
- Must identify operational improvements that can reduce disruptions and protect revenue.
Customer Experience Teams:
- Need to understand what drives refund requests and customer dissatisfaction.
- Need guidance on proactive communication strategies that reduce frustration and refund claims.
Revenue and Finance Teams:
- Need a breakdown of how refunds impact total earnings.
- Need cost-based prioritization of improvements to choose where investments will save the most money.
Technical and Maintenance Teams:
- Need to understand how equipment failures contribute to delays and cancellations.
- Require evidence that supports better maintenance scheduling and resource allocation.
Policy & Ticketing Management:
- Require support to design ticket flexibility policies that retain revenue without harming customer satisfaction
Human Resources and Staff Management:
- Looks at staffing-related delay and cancellation data to plan shifts, training needs, and improve workforce performance.
Business Development and Planning:
- Utilizes trend and route performance analytics to plan service expansions, partnerships, and flexible ticketing strategies

### Key Questions to Answer
- What are the main causes of train delays and cancellations, and how frequently do they occur?
- How do delays and cancellations vary by route, station, time of day, and ticket type?
- At what delay duration do passengers typically begin requesting refunds?
- What is the financial impact of delays and cancellations on overall revenue?
- Which routes and stations contribute most to refund requests and revenue loss?
- How do technical issues and staff performance contribute to service disruptions?
- What patterns exist in passenger refund behavior, and how does service quality affect it?
- How effective are current policies for handling refunds, ticket flexibility, and customer communication?
- How can early intervention and predictive analytics be used to minimize delays and cancellations?
- What operational, staffing, and maintenance improvements are needed to reduce disruptions?

### Tools and Skills Used
- Python (Pandas, Seaborn, Matplotlib, Scipy)
- Power BI (DAX, visuals, KPIs)
- Data Cleaning and Preparation
- Diagnostic Analysis and Exploratory Data Analysis (EDA)
- Excel(Data set reading and comprehension)
  
### Dashboard
<p align="center"><img src="https://github.com/BOAMAH-99/UK-train-station-analysis/blob/9aa6ee37ef2395fc223c03010481101b07f11bb4/Document/Dashboard.jpg" width="800"></p>

### Key Findings:
- Refunds spikes when delays crosses the 20 minutes mark, this suggests there is a customer tolerance threshold of 20 minutes, after which passengers are more likely to request a refund. Interventions aimed at preventing delays from crossing this window could reduce refund volumes substantially.
- Although delayed and cancelled trips represent only a small portion of the total journeys, 7.24% for delays and 6% for cancellations, together they result in a combined financial loss of approximately £172,000 , which accounts for more than 25% of the total revenue. This suggests that these disruptions are happening most frequently on high revenue or high volume routes.
- Despite achieving a strong on time performance of 87%, the company still incurs high losses from delayed trips, totaling £127,000.00. This indicates that hidden inefficiencies exist beneath the headline performance metrics and should be addressed.
- Delayed trips are proving to be three times more costly than cancellations, indicating a large amount of revenue at risk that could still be recovered if performance is improved. While cancellations end the journey, delays lead to dissatisfaction during the trip, often triggering refund requests despite service completion.
- Technical issues and staff performance were the most frequently associated with refund requests steming from reasons for delays and cancellations. These are internal, controllable factors, which highlights the need to prioritize improvements in operations and technical readiness.
- Refund behavior appears to be driven by service quality and personal inconvenience.
- Advance ticket types are consistently associated with higher cancellation rates. This reinforces the importance of reviewing and updating ticket flexibility policies to help reduce unnecessary revenue loss due to possible change of plan leading to cancellations
- Specific routes stand out as hotspots for refund activity. The routes from York to Peterborough, Durham, Doncaster, and Edinburgh, as well as Reading to Swindon, accounted for 1,077 refund requests. York in particular appears to be a key departure station linked to refund heavy journeys, suggesting a need for operational review at the York location.

  ### Strategic Recommendations:
- Offer low cost flexible ticket upgrades that allow customers to reschedule their travel without forfeiting their fare. Our analysis shows that advance ticket holders are more likely to cancel, often due to changing plans. Flexibility can reduce cancellations and retain more revenue
- Send automated travel reminders to customers 24 to 48 hours before their scheduled departure. This can reduce no-shows and increase engagement, giving passengers a chance to adjust plans early without triggering a refund
- Experience has a greater impact on refund behavior than ticket price. Even low-priced tickets are subject to refund requests when service is poor. Focus on delivering a consistent, smooth passenger journey through better communication, reliable performance, and onboard service quality
- Deploy an early-intervention protocol when a trip crosses the 15 minute delay mark. This should include system alerts, fast-response team engagement, and auto-notifications to customers, especially on high-revenue or high-volume routes. Proactive updates at this early threshold can help reduce passenger frustration and preempt refund requests
- Maintain a close watch on station level cancellation triggers. Strengthen crew availability and shift management so cancellations caused by staff shortages are minimized.  If the station cancels a trip, the refund should be automatic or clearly prompted and if it was cancelled by customers, send instant cancellation notifications with a clear refund eligibility message and an option to rebook.
- Run a full operational audit on York routes, especially York to Peterborough, Doncaster, Durham, and Edinburgh. These routes collectively account for over 1,000 refund requests, making York a key area of risk. Addressing scheduling and staffing at this station could significantly reduce refund volume
- Review maintenance intervals and offering staff performance training can reduce the occurrence of avoidable cancellations
- Use predictive analytics to identify trips that are at high risk of being delayed before dispatch. This enables proactive adjustments to crew assignments, departure timing, and route selection, minimizing service disruptions.
- Prioritize investments that prevent delays rather than simply avoiding cancellations. Our data shows that delays, although slightly more frequent than cancellations, result in three times more financial loss. Focusing on delay reduction can save over £127,000 per month
- Introduce weekend booking perks, allowing customers to rebook with no fee to help retain revenue from passengers who would otherwise cancel due to plan changes.

### Expected Impact / Results

Implementing the recommended operational and policy changes is expected to significantly reduce refund-driven revenue loss. By addressing delay triggers at critical stations, improving technical readiness, optimizing staffing, and introducing flexible ticket options, the operator can reclaim a large portion of avoidable losses—especially from delay-related refunds, which are currently three times more costly than cancellations.

With proactive customer communication and early intervention when delays exceed 15–20 minutes, the business can lower refund requests, protect customer satisfaction, and strengthen long-term trust. Overall, these improvements can reduce refund-related revenue loss by an estimated 20–30%, while improving service reliability and operational efficiency across high-risk routes

#### By refining operational performance and implementing smarter, customer focused policies, significant refund losses can be reclaimed. This not only strengthens profitability but also builds long term customer trust through consistently better travel experiences.

#### [Power BI Dashboard (.pbix)](https://github.com/BOAMAH-99/UK-train-station-analysis/blob/9aa6ee37ef2395fc223c03010481101b07f11bb4/Document/Dashboard.pbix)
#### [Dataset: railway.csv](https://github.com/BOAMAH-99/UK-train-station-analysis/blob/9aa6ee37ef2395fc223c03010481101b07f11bb4/data/railway.csv)



