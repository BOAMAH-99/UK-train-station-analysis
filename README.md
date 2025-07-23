# UK Train Station Analysis

This analysis explores operational performance and refund behavior in a train service dataset. The objective is to uncover patterns in journey delays, cancellations, and refund requests, and assess their financial impact. By examining factors such as journey status, ticket type, delay reasons, time patterns, and route performance, this study identifies inefficiencies and provides data-driven insights to support operational improvements and reduce revenue loss.


### Key Features
- Interactive Power BI dashboard
- Visual analysis of delay trends, refund patterns, and revenue loss
- Testing to improve accuracy of analysis

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
- Refund requests are significantly more common on trips that were either delayed or cancelled, which aligns with expectations around passenger dissatisfaction following service disruptions.
- Refunds tend to spike when delays crosses the 20 minutes mark, this suggests there is a customer tolerance threshold during moderate delays, after which passengers are more likely to request a refund. Interventions aimed at preventing delays from crossing this window could reduce refund volumes substantially.
- Although delayed and cancelled trips represent only a small portion of the total journeys, 7.24% for delays and 6% for cancellations, together they result in a combined financial loss of approximately £172,000 , which accounts for more than 25% of the total revenue. This suggests that these disruptions are happening most frequently on high revenue or high volume routes.
- Delayed trips are proving to be three times more costly than cancellations, indicating a large amount of revenue at risk that could still be recovered if performance is improved. While cancellations end the journey, delays lead to dissatisfaction during the trip, often triggering refund requests despite service completion.
- A statistically significant relationship was found between the reason for delay and the likelihood of a refund being requested. Delays due to technical issues and staff performance were the most frequently associated with refund requests. These are internal, controllable factors, which highlights the need to prioritize improvements in these areas.
- Refund requests are not always linked to higher priced tickets, which indicates that customers are not strictly price sensitive. Instead, refund behavior appears to be driven more by service quality and personal inconvenience.
- Encourage passengers to book during non-peak hours by offering loyalty points. This could help smooth demand, reduce system strain, and prevent spikes that lead to service delays and refund risk
- The data also revealed significant variations in refund rates across different routes and ticket types. This opens up opportunities for targeted adjustments in refund policies, allowing more precision in how customer service rules are applied based on risk patterns.
- Advance ticket types are consistently associated with higher cancellation rates. This reinforces the importance of reviewing and updating ticket flexibility policies to help reduce unnecessary revenue loss due to possible change of plan leading to cancellations
- Despite achieving a strong on time performance of 87%, the company still incurs high losses from delayed trips, totaling £127,000.00. This indicates that hidden inefficiencies exist beneath the headline performance metrics and should be addressed.
- Controllable operational issues accounted for the most popular reasons for delays and cancellations. This emphasizes the need for additional investment in staff training, equippment improvemt, technical readiness, and scheduling control to reduce preventable service failures.
- Specific routes stand out as hotspots for refund activity. The routes from York to Peterborough, Durham, Doncaster, and Edinburgh, as well as Reading to Swindon, accounted for 1,077 refund requests. York in particular appears to be a key departure station linked to refund heavy journeys, suggesting a need for operational review at the York location.
- Early morning bookings rarely Lead to refunds. Very low refund rates originate from bookings made between 0:00 and 6:00 AM, across all days.
- The late afternoon travel window is operationally fragile, when disruptions occur, they have an outsized impact on refund request rate.


  ### Strategic Recommendations:
  - Offer low cost flexible ticket upgrades that allow customers to reschedule their travel without forfeiting their fare. Our analysis shows that advance ticket holders are more likely to cancel, often due to changing plans. Flexibility can reduce cancellations and retain more revenue
  - Send automated travel reminders to customers 48 to 72 hours before their scheduled departure. This can reduce no-shows and increase engagement, giving passengers a chance to adjust plans early without triggering a refund
  - Enhance communication for bookings made at 17:00–18:00 as these customers have a higher likelihood of canceling or requesting for funds.
  - Experience has a greater impact on refund behavior than ticket price. Even low-priced tickets are subject to refund requests when service is poor. Focus on delivering a consistent, smooth passenger journey through better communication, reliable performance, and onboard service quality
  - Deploy an early-intervention protocol when a trip crosses the 15-minute delay mark. This should include system alerts, fast-response team engagement, and auto-notifications to customers, especially on high-revenue or high-volume routes
  - Set up internal alerts when any trip exceeds a 15-minute delay. Staff should be notified immediately and empowered to communicate with affected passengers. Proactive updates at this early threshold can help reduce passenger frustration and preempt refund requests
  - Maintain a close watch on station-level cancellation triggers. Strengthen crew availability and shift management so cancellations caused by resource shortages are minimized.  If the station cancels a trip, the refund should be automatic or clearly prompted and if it was cancelled by customers, send instant cancellation notifications with a clear refund eligibility message and an option to rebook. Internal cancellations should be minimized by improving platform readiness, equipment availability, and real-time communication between scheduling and station staff
  - Track the source of trip cancellations whether they are initiated by the station or the passenger. Internal cancellations should be minimized by improving platform readiness, equipment availability, and real-time communication between scheduling and station staff
  - Run a full operational audit on York routes, especially York to Peterborough, Doncaster, Durham, and Edinburgh. These routes collectively account for over 1,000 refund requests, making York a key area of risk. Addressing scheduling and staffing at this station could significantly reduce refund volume
  - Conduct in-depth audits on routes that experience recurring technical or staffing issues. Based on the data, technical faults and staff-related problems are among the top reasons customers request refunds. Reviewing maintenance intervals and offering staff performance training can reduce the occurrence of avoidable cancellations
  - Use predictive analytics to identify trips that are at high risk of being delayed before dispatch. This enables proactive adjustments to crew assignments, departure timing, and route selection, minimizing service disruptions.
  - Prioritize investments that prevent delays rather than simply avoiding cancellations. Our data shows that delays, although slightly more frequent than cancellations, result in three times more financial loss. Focusing on delay reduction can save over £127,000 per month
  - Reroute train journeys using enhanced traffic and delay prediction systems. This will help dynamically select routes with the shortest travel times and fewer congestion risks, improving punctuality and reducing delays.
  - Enhance communication for bookings made at 17:00–18:00 each day, as thesee customers are prone to request for refunds
  - Introduce weekend booking perks, allowing customers to rebook with no fee to help retain revenue from passengers who would otherwise cancel due to plan changes.



#### By refining operational performance and implementing smarter, customer focused policies, significant refund losses can be reclaimed. This not only strengthens profitability but also builds long term customer trust through consistently better travel experiences.

