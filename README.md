# UK Train Station Analysis

This analysis explores operational performance and refund behavior in a train service dataset. The objective is to uncover patterns in journey delays, cancellations, and refund requests, and assess their financial impact. By examining factors such as journey status, ticket type, delay reasons, time patterns, and route performance, this study identifies inefficiencies and provides data-driven insights to support operational improvements and reduce revenue loss.


### Key Features
- Power BI (Interactive dashboard)
- Jupyter Notebook (Visual analysis of delay trends, refund patterns, and revenue loss)

### Dashboard
[View the interactive Power BI dashboard](https://app.powerbi.com/reportEmbed?reportId=ed853100-e602-41c8-a42c-58a1b429a2ab&autoAuth=true&ctid=bd697c1b-c481-479c-841e-c618542675c3) 

_or view below:_

<iframe title="UK TRAINS ANALYSIS DASHBOARD" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=ed853100-e602-41c8-a42c-58a1b429a2ab&autoAuth=true&ctid=bd697c1b-c481-479c-841e-c618542675c3" frameborder="0" allowFullScreen="true"></iframe>

### Tools and Skills Used
- Python (Pandas, Seaborn, Matplotlib, Scipy)
- Power BI (DAX, visuals, KPIs)
- Data Cleaning & Exploratory Data Analysis (EDA)
- Excel(Data set reading and comprehension)

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


#### By refining operational performance and implementing smarter, customer focused policies, significant refund losses can be reclaimed. This not only strengthens profitability but also builds long term customer trust through consistently better travel experiences.

