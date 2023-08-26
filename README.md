# RevenueDashboard
ATLIQ Grands Revenue Dashboard
# ATLIQ Grands Revenue Dashboard
### INTRODUCTION:

I recently completed this project utilizing PowerBI, which was modeled after the tutorials provided by Codebasics in their PowerBI YouTube playlist .This project allowed me to gain a deeper understanding of PowerBI and its capabilities.

[Codebasics youtube playlist](https://www.youtube.com/watch?v=tT4V7zguCnc)

[Live Dashboard Link]([https://app.powerbi.com/view?r=eyJrIjoiMmJmMzRjYjgtOTZhNy00ZGVkLTg2YjEtZTY0MDcxMDM3ZGRiIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&pageName=ReportSection40e6fb4b5493ba29ec91](https://app.powerbi.com/view?r=eyJrIjoiYTk5MzcxMTAtMjExZC00ZWVlLTg1NzUtMjE3Mzg4YjgxOGU0IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9))

### PROBLEM STATEMENT
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. 

Data Analysts are needed to provide insights from the historical data.


### SOFTWARE AND TOOLS REQUIRED:

1. [Github Account](https://github.com)
2. [PowerBI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
3. [NovyPro Account](https://www.novypro.com/)  --for publishing PowerBI dashboard online

### DATA MODEL:
<div align="center" >
<img height:"100" width:"100" src="https://github.com/bavithaboina/RevenueDashboard/blob/main/img/Reveue_dashboard_data_model.jpg">
</div>

### Steps followed in this project:
1. Excel files were imported into PowerBI to lay the foundation for analysis.
2. Extensive exploration was conducted, including the creation of new columns such as 'day type' to differentiate between weekends and weekdays.
3. Essential measures were derived using DAX, encompassing: Revenue,RevPar (Revenue Per Availbale room ),DSRN (Daily Sellable Room Nights),DURN (Daily Utilised Room Nights) ... etc 
4. A comprehensive dashboard was designed, showcasing KPIs and vital trends. 
5. The final dashboard was published online using NovyPro for accessibility.

## Key Insights

### Key Measures Created:
1. **Revenue**    : The total revenue realised from each booking.
     *  If the booking status is 'CHECKED OUT' then the revenue realised will be equal to revenue generated from that booking
     *  If the booking status is 'CANCELLED' then the revenue realised = 40% of revenue generated (as 60% refund therfore remaining 40% is the revenue generated)
     *  If the booking status is 'NO SHOW' then the revenue realised will be equal to revenue generated from that booking ( no refund) (no show means the user has booked but did not utilise the booked room )
2. **RevPar** (Revenue Per Available room) : The revenue that is being generated by each room that is available to be sold.
       RevPAR = Total Revenue / Total Available Rooms to sell
3. **ADR** (Average Daily Rate) : the revenue being by each of the sold rooms
       ADR =  Total revenue from the rooms sold/number of rooms sold
4. **Occupancy %** : % of rooms used out of the total rooms available
       Occupancy % = (total number of rooms used / total number of rooms available )*100
   
   NOTE : if occupancy is 100% then RevPar = ADR
   
5. **SRN** (Sellable Room Nights) : Number of rooms that are in a condition to be sold .
6. **URN** (Utilised Room Nights): Number of rooms in which customers eneded up staying
7. **BRN** (Booked Room Nights) : Number of rooms booked .this includes all utilised rooms ,cancellations and no show
   
    NOTE : if you calculate SRN,URN,BRN on daily basis they become DSRN,DURN,DBRN
   
8. **Realization** : Number of rooms that were actually utlised out of the total booked rooms
       Realization = URN/BRN
9. **Cancellation %** : % of bookings cancelled out of the total bookings
10. **No show %** : % of bookings whose status is no show out of the total bookings 
For week on week change used  = ((current week value  - last week value) /last week value) * 100
For calculating any percentage change
    Percentage Change = ((New Value - Old Value) / Old Value) * 100

## FINAL RESULT

### DASHBOARD 
<div align="center">
<img src="https://github.com/bavithaboina/RevenueDashboard/blob/main/img/Dashboard.jpg"  />
</div>

### IMPORTANT INSIGHTS 
## 1. PRICING STRATEGY :
   <div align="center" >
    <img height:"50" width:"50" src="https://github.com/bavithaboina/RevenueDashboard/blob/main/img/trend_by_key_metrics.jpg">
    </div>
   You can observe that RevPar is changing in accordance with occupancy%  and ADR is almost constant.
   Therefore it means the pricing strategy used is flat pricing .So there is a room to incorporate any other pricing strategy like weekday/weekend Pricing or Dynamic Pricing.
   
   * **Weekday/Weekend Pricing** : Set the price based on the day whether it is weekday or weekend.Generally on weekends the price is ususally high.So you can set accordingly.
   
       NOTE : In hotels
               * weekend - Friday,Saturday
               * weekday - other days
   * **Dynamic Pricing** : Change the price dynamically based on occupancy,competition rates or any other factors that frequently change and effect the hotels revenue
## 2. DIFFERENTIAL PRICING (between the channels) :
   <div align="center" >
    <img height:"50" width:"50" src="https://github.com/bavithaboina/RevenueDashboard/blob/main/img/booking_platform.jpg">
    </div>
   You can observe that the revenue realized from your channel is almost same as the revenue generated from other channels. Most owners,hotels,business sell the cheapest on their own channel so that they can increase the bookings from their own channel .Because if the booking is from some other channel then the hotel has to pay some comission to that channel. So if the booking is from your channel you can save the money that is going as commision to someone else.So hotels incorporate differential pricing based on the channel.They try to give discount coupons or complemetaries or any other promotional offer to encourage customers to book from the hotel's channel.So this can be incorporated in Atliq Grand.
   
## 3. Highest Performing and Least performing:
  <div>
    <img  height:"50" src="https://github.com/bavithaboina/RevenueDashboard/blob/main/img/highest_performinh.jpg">
    <img height:"50" src="https://github.com/bavithaboina/RevenueDashboard/blob/main/img/least_performing.jpg">
</div>
    
    <div >
    <img height:"50" width:"30" src="https://github.com/bavithaboina/RevenueDashboard/blob/main/img/least_performing.jpg">
    </div>
   Checkout whats going wrong with the least performing hotels ,check the average ratings given to the least performing hotels.Read the reviews.Find out if the service is bad or the ambience is bad or any other reason that is leading to less revenue from the hotel .Talk to the management of these least performing and try to take strategic decisions
   Checkout whats going right with the highest performing hotels.Try to incorporate those features in other hotels so that they can also perform as good as the highest perfroming hotels.
                   




