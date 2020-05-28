# Caredash_takehome

This repository is relating to an assignment. 

## I. What is this assigment final goal? 
  - Given the database, my goal is to determine when is the best day to send the campaign emails to increase email engagement. 
  
  
## II. Answering the questions that are given: 
1.	What is the date range of sends? of opens?
  - The emails are sent from March 17th to March 23rd (The span of the send_email is a full week; from Monday to Sunday)
  - The emails are opened on March 17th to March 25th

2.	How many sends, opens, clicks, unsubs are there in that time range?
  - Number of Sends:  296186
  - Number of Opens Emails:  74922
  - Number of Clicks:  5139
  - Number of Unsubscribes:  115

3.	What metrics do you want to derive from this data set to measure the success of the email campaign?
In Email Marketing Metrics, according to HubSpot and Impact, there are 9 well known metrics: 
1. Click-through Rate: the ratio of people who received and clicked on one or more links contained in emails over the total emails sent
2. Click-to-open Rate: the ratio of people who clicked on one more links in the emails over the email opened

3. Conversion Rate: The ratio of people who received and clicked a link from the email and completed a desired goal, such as filling out a survey or purchasing products, over the total emails sent
4. Bounce Rate: The percentage of total sent emails that are not succesfully delivered to the recipient's mail box
5. Complaint Rate: The percentage of email recipients who hit spam or junk buttons 
6. Email Sharing/ Forwarding Rate: The percentage of email recipients who shared the emails content to others or who clicked on "forward this to a friend". 
7. Overal ROI: profitable ratio given a campaign, or we can say as return of an investment 
8. Open Rate: The ratio of people who opened the given emails over the total emails sent
9. Unsubscribe Rate: The ratio of people who unsubscribed from your email list after opening the email over the total emails sent
=> With the given database, the metrics I used to evaluate the success of the campaign are Click-through  Rate, Open Rate and Unsubscribe Rate  

3.a.	Which one do you think is the most important and why?
-  I personally think the most important metrics are the click-through rate. Depending on your campaign goal, you want your emails to look interesting or attractive to the recipients so that they want to know more what you are doing by clicking on given links, and, eventually, do a desired action.


4.	What are the trends of these metrics broken down by send_time? open_time? Can you break down by anything else?
  The trends are made in the conclusion part
  
5.	What are your recommendations in terms of what time we should send our emails? 
 From the conclusion, the sent email should be given in the following priority: 
    1. Monday
    2. Thursday and Friday
    3. Tuesday 
    4. Saturday 
    5. Wednesday and Sunday
- Hour frame to send the emails: Because the emails are more likely to be opened within the first hour and there is more email engagement after 6:00 pm, the optimal time to send the email is around 6:00 pm. 
    - In the 6:00pm - 9:00 pm hour frame, there is more email engagement because emails are most likely not to be unsubcribed, highest number of clicks, and number of opened emails
6.	Do you have any recommendations for future analysis?

  - The open rate of around 25% is pretty impressive for an email marketing campaign. The low in both click-through-rate and click-to-open rate are more worrisome.
      -  What I am seeing here is, the customers are interested in the content of the emails because of the headlines. But lose interest after seeing the content/design of the emails. Depending on the purpose of the marketing campaign, the contents/designs have to both meet the expectations of the headline and trigger user's curiousity
      -  The suggestion for this is to conduct an A/B testing or UX research - understanding who our clients are and what can the campaign benefit them.

  - Other variables that I think would help trememdously in determining when to send the emails are recipients' age, gender, deliverability of the emails, conversion factor (what is the desired action that the campaign wants the recipients to do)

  - Of course, the more data sets the better. We have more information to be more certain that our conclusions are reliable.

 ## III. Conclusions 
  - Recipients are most likely to read the email on Thursday and Saturday
  - They are less likely to open emails on Wednesday and Sunday
  - On average, it takes around 14.50 hours for recipients to open their emails
  - Highest open rates are from emails sent on Monday and Friday
  - Lowest open rates are from emails sent on Wednesday and Sunday
  - Highest click-through rate is on Monday. The rate is closely similar for the remaining days of the week.
  - The click-to-open rate is in the range of 6%-8% everyday. The distribution of the rate against time is relatively flat. This information has no value contribution in determining what is the best day to send emails
  - Emails sent on Thursday are less likely to be unsubscribed
  - Recipients more likely to unsubscribe emails on Wednesday, Saturday and Sunday
  - 27% of all emails are opened within the first 3 hours after receiving (around 10% in the first hour of receiving).
  - Only 1% of all emails are opened after 13 hours receiving
  - The hour frame that has the highest engagement is around 6pm - 12:00 am
