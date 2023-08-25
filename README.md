# RevenueDashboard
ATLIQ Grands Revenue Dashboard
# ATLIQ Grands Revenue Dashboard
### INTRODUCTION:

I recently completed this project utilizing PowerBI, which was modeled after the tutorials provided by Codebasics in their PowerBI YouTube playlist .This project allowed me to gain a deeper understanding of PowerBI and its capabilities.

[Codebasics youtube playlist](https://www.youtube.com/watch?v=tT4V7zguCnc)

[Live Dashboard Link]([https://app.powerbi.com/view?r=eyJrIjoiMmJmMzRjYjgtOTZhNy00ZGVkLTg2YjEtZTY0MDcxMDM3ZGRiIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&pageName=ReportSection40e6fb4b5493ba29ec91](https://app.powerbi.com/view?r=eyJrIjoiYTk5MzcxMTAtMjExZC00ZWVlLTg1NzUtMjE3Mzg4YjgxOGU0IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9))

### PROBLEM STATEMENT
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. 

Data Analysts are needed to provide insights from the historical data


### SOFTWARE AND TOOLS REQUIRED:

1. [Github Account](https://github.com)
2. [PowerBI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
3. [NovyPro Account](https://www.novypro.com/)  --for publishing PowerBI dashboard online

### DATA MODEL:
<div align="center" >
<img height:"100" width:"100" src="https://github.com/bavithaboina/SalesInsightsDashboard/blob/main/images/Sales_Insights_DataModel.png">
</div>

### Steps followed in this project:
1. Loaded excel files into PowerBI
2. Analysed data ,created necessary columns like day type to know whether the day is weeekend or weekday
3. Created necessary key measures like Revenue,RevPar (Revenue Per Availbale room ),DSRN (Daily Sellable Room Nights),DURN (Daily Utilised Room Nights) ... etc using DAX
4. Created Dashboard with necessaey KPI's and necessary trends 
5. Published the dashboard online

### Key Measures Created:
1. Revenue : The total revenue realised from each booking.
     *  If the booking status is 'CHECKED OUT' then the revenue realised will be equal to revenue generated from that booking
     *  If the booking status is 'CANCELLED' then the revenue realised = 40% of revenue generated (as 60% refund therfore remaining 40% is the revenue generated)
     *  If the booking status is 'NO SHOWS' then the revenue realised will be equal to revenue generated from that booking ( no refund)
2. RevPar  : Revenue Per Available room.The revenue that is being generated by each room that is available to be sold.
       RevPAR = Total Revenue / Total Available Rooms
       $$ RevPAR = \frac {Total Revenue  }{ Total Available Rooms} $$




  
## FINAL RESULT

### INITIAL DASHBOARD
<div align="center">
<img height:"75" width:"75" src="https://github.com/bavithaboina/SalesInsightsDashboard/blob/main/images/inital_sales_inisghts_dahsboard.png">
</div>

### FINAL DASHBOARD 
<div align="center">
<img src="https://github.com/bavithaboina/SalesInsightsDashboard/blob/main/images/Microsoft-Power-BI-Google-Chrome.gif"  />
</div>




