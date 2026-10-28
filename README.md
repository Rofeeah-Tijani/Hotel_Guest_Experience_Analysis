# Hotel_Guest_Experience_Analysis

Hotel Guest Experience Analysis

An interactive Excel dashboard that analyses guest feedback and booking records from a hotel, covering 1,948 customers across one year. It answers four practical questions: who stays, why they come, how they found the hotel, and how satisfied they are.

Dataset

The raw file is not included in this repository because it contains guest-level personal fields (full names and dates of birth). Only the analysis and summary findings are shared here.

Each row is one guest. The columns fall into five groups:

Group	Columns
Booking	ID, Checkin Date, Checkin Month, Checkin Day, Checkin Year, Checkout Date, Stay period
Guest profile	Full Name, Gender, Date of Birth
Visit context	Purpose of the visit, How did you discover us?
Survey scores	Overall experience, Likelihood to recommend, Staff attitude, Check-in process, Room service, Room cleanliness, Food quality, Variety of food, Broadband & TV, Gym
Calculated	Rating, Avg Staff, Avg Room, Avg Food, Avg Facility, Recommendation
What I did
Cleaned and prepared the data. Checked for duplicates and blanks, split check-in dates into month, day and year, and calculated stay length from check-in and check-out dates.
Built category averages. Grouped the individual survey scores into Avg Staff, Avg Room, Avg Food and Avg Facility so related services can be compared side by side.
Segmented guests. Used the recommendation score to classify each guest as an Advocate, Supporter, Cautious or Skeptic, and converted the overall experience score into a rating band (Poor to Excellent).
Built pivot tables and charts for each question below.
Added slicers for Gender and Day of the week, so every chart on the dashboard can be filtered to a specific group of guests or to specific check-in days.
Key findings

Total guests: 1,948

Recommendation segments

Segment	Share
Advocates	47.5%
Supporters	26.8%
Cautious	14.1%
Skeptics	11.6%

Nearly three in four guests (74.3%) are Advocates or Supporters.

Purpose of visit

Purpose	Share
Business	43%
Vacation	36%
Function	15%
Other	7%

How guests discovered the hotel

Source	Share
Organization	39.9%
Hotel booking	15.7%
Word of mouth	14.2%
Search engine	12.3%
Internet	8.1%
Television	6.0%
Newspaper	3.9%

Organizations are the largest source of guests by a wide margin, which fits with business being the most common reason for visiting.

Overall customer rating

Rating	Guests	Share
Excellent	640	32.9%
Very good	499	25.6%
Good	369	18.9%
Average	273	14.0%
Poor	167	8.6%

58.5% of guests rated their stay Very good or Excellent.

Monthly check-in trend

Check-ins stayed fairly even through the year, ranging from 139 (July) to 193 (June). June was the busiest month, followed by August (182) and September (180).

Guest age profile

Guests were grouped by birth year, from 1951 to 2006, and the groups are spread fairly evenly (41 to 46 guests per group). The hotel is not dependent on a single age bracket.

Dashboard filters
Gender: compare satisfaction, purpose of visit and discovery source between male and female guests.
Day of the week: see how check-in volume and ratings change depending on the day guests arrive.
Tools

Microsoft Excel (data cleaning, calculated columns, PivotTables, PivotCharts, slicers)

Author

Rofee'ah Tijani GitHub: Rofeeah-Tijani
