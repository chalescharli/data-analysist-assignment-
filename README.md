# data-analysist-assignment-
We are developing a comprehensive solution to generate, manage, and verify leads. This involves running digital campaigns, collecting lead data, and using a call center to verify these leads. We then send call-verified leads to our advertisers, ensuring high-quality and interested prospects.

Data Explanation
Data Columns
Call ID:
Description: Unique ID for each call
Purpose: Track each call dial 
lead_id:
Description: A unique identifier for each lead in our system.
Purpose: Used to track and manage individual leads.
campaign_id:
Description: The campaign ID associated with the lead.
Purpose: Identifies which campaign the lead originated from.
advertiser_id:
Description: The client ID associated with the advertiser.
Purpose: Allows for tracking multiple products/campaigns for a single advertiser.
hid:
Description: Our system's unique identifier.
Purpose: Used for internal tracking within our system.
Call_status
Description: Status of the lead (Eg. No Answer, Completed)
Purpose: To know if the call is answered or not
Lead Status
Description: The disposition of the lead (e.g., Interested, Not Interested, Not Answered, Busy).
Purpose: Indicates the outcome of the call attempt.
Agent Call Duration:
Description: Duration of the call session with the customer.
Purpose: Measures engagement time with the lead.
Customer Call Duration:
Description: The actual time the agent spent talking to the customer.
Purpose: Provides insights into customer interaction time.
from_calling_number:
Description: The number from which the call was dialed.
Purpose: Tracks the source of the call.
to_calling_number:
Description: The customer’s phone number.
Purpose: Identifies the lead being contacted.
attempt_no:
Description: The call attempt number to the customer.
Purpose: Tracks the number of attempts made to contact the lead.
created_at:
Description: The date and time when the lead was created.
Purpose: Tracks the age of the lead.
updated_at:
Description: The date and time of the last attempt or update.
Purpose: Tracks the most recent activity on the lead.
Agent Name:
Description: The name of the agent who made the call.
Purpose: Identifies which agent handled the lead.
Agent ID:
Description: A unique identifier for the agent.
Purpose: Used to track agent performance and activities.
Call Connected Status:
Description: Status indicating whether the call was successfully connected or not.
Purpose: Helps in measuring connection success rates.
Call Dial Time:
Description: The time when the call was initiated.
Purpose: Tracks the exact timing of the call attempt.
Report Preparation
Using the above data, we aim to prepare the following reports:
Campaign Performance Report:
Metrics:
Total calls (count of call_sid)
Unique leads (count of distinct lead_id)
Calls connected (count of call_status = "Answered")
Unique calls connected (count of distinct lead_id where call_status = "Answered")
Leads converted (count of call_status = "Interested")
Qualified leads (count of leads meeting advertiser criteria)
Leads lost (count of call_status = "Not Interested")
Average agent call duration (average of Agent Call Duration)
Average customer call duration (average of Customer Call Duration)
Purpose: To evaluate the performance of each campaign and agent.
Lead Disposition Report:
Metrics:
Distribution of call statuses (Interested, Not Interested, Not Answered, Busy, etc.)
Purpose: To analyze the outcomes of call attempts and improve call strategies.
Agent Performance Report:
Metrics:
Number of calls made (count of call_sid per agent)
Calls connected (count of call_status = "Answered" per agent)
Leads converted (count of call_status = "Interested" per agent)
Average agent call duration (average of Agent Call Duration per agent)
Average customer call duration (average of Customer Call Duration per agent)
Purpose: To assess the performance of each calling agent.
Additional Reports:
You are encouraged to create any additional reports that you believe would provide valuable insights or improve our call center operations.
Forecasting Objectives
Based on the data, we aim to create the following forecasts:
Call Volume Forecast:
Objective: Predict the total number of calls that will be made in the next 30 days based on historical data.
Lead Conversion Forecast:
Objective: Estimate the number of leads that will be converted into interested prospects over the next 30 days.
Agent Efficiency Forecast:
Objective: Predict agent performance metrics such as calls per hour, success rate, and average handling time.
Resource Allocation Forecast:
Objective: Forecast the number of agents required to handle the expected call volume and maintain desired performance levels.
Additional Forecasts:
You are encouraged to create any additional forecasts that you believe would provide valuable insights or improve our call center operations.
Timeline
Completion Time: 2-3 days
Tools & Technologies
Tools: You may use any tools or technologies you are comfortable with.
Accessibility: The final output should be easily accessible on a computer or through a Chrome browser.

