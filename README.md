# Dating-History-App-Full-Whammy

# Dating-History-App
# App Name (Lovelines? Ex Track? )
## _High Level Planning Document_


This document describes the main features of the *insert name* application. *Insert name* aims to visualise our dating history, identifying patterns and trends to allow us to make better informed choices for the future. *For the purpose of simplicity, all exes, hook-ups, FWB's etc. will be collectively referred to as "ex" throughout this project. 

###  ✨Required Inputs (Basic) ✨
- Date Range
- Ex Name
- Reason it ended

###  ✨Required Inputs (Full Whammy) ✨
- Gender preference (To filter out friends from love interests)

###  ✨Optional Inputs (Full Whammy) ✨
- Ex Age (Do you always go for older men? Daddy issues?..... What's with the younger women? Are you insecure?)
- Relationship Status (Facebook "in a relationship")
- Financial Status (Are you seen as a gold-digger? Do you attract gold-digger types?)
- Were you friends first/meet on a dating app? (Do you need time to get to know someone or are you a good immediate judge of character?)
- Geographic location (Did you REALLY think the sleazy barman you met on holiday was going to be "the one"?!)
- When you started spending the night (Do you rush into physical intimacy?)
- How often you spend the night (keep it casual or 7 nights per week from the start?)
- Friends in common (Do you keep them segregated in your life? Do you have intimacy issues?)
- Correspondance buzz-words (establish if dating from typical shared language - is it affectionate, sex-related, kisses etc)
- Correspondance times (early morning/late night)
- Selfies together (does phone recognise photos with both faces?) 
- Call log (person you call most often / for the longest duration)

## Data Visulisation Process (Basic)

Manually input data into excel using the following column headings: 

Year    |   Month | Day | Ex    |
--------| --------|-----| ------|
2010    | January |1    | Trevor|
2010    | January |2    | Steve |
2010    | January |3    | Bob   |
etc|

Import data directly into Tableau (or PowerBI?) and produce bar graph with the following constraints:
-*input constraints*
- Graph = Text Table
- Columns = Month (date)
- Rows = Year (date)
- Filters = ex (ex_name)
- Marks = Colour: Max(ex_name), ATTR(ex_name)

Reasons for breakup were added manually as a label 

## Data Visualisation Process (Full Whammy)

Automatically harvest input data into ??? using the following column headings:

Year|Month|Day|Ex|Reason for Breakup|FB Rel Status|Ex Age|Ex Gender|Geo Location|Friends/Tinder|Common Friends|
--------| --------|---| ------|----------| --------|-----| -------- |-----|---|
2010 | January |1  | Trevor| no  |30|Male|Leeds|Tinder|no| 
2010 | January |2  | Steve | yes |
2010 | January |3  | Bob   | yes |
etc|

- ✨Magic ✨

## Potential Data Sources

- Manual input - Choose a database to manually input data range / name / reason for breakup
- Iphone Location (android?)
- Facebook
- Instagram
- Twitter
- Tinder (can you access this data?)
- Messages
- Whatsapp 
