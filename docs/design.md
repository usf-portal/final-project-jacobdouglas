# Design and Choices



The most important table that I created during the project would be the Master Table. This was essentially a copy of every entry in the database. Instead of creating separate tables for locations, orders, etc..., I decided to pull information from the Master list via views. I would then use those views to influence my table design.

The views that I created were simple, yet gave up a substantial bit of information. The views were variations of a rudimentary view I made to give the total number of accusations for the Priest option under type. Once I created this, I realized the versatility that this view had.

By stringing together multiple variations of the original view with a UNION command, I was able to create a larger, more comprehensive view that gave information on the other types. In the views I made, I used the last row to have the total number of successes or failures in order to give a comparison.

I decided to label any status where the individual is accused, convicted, sued, or charged as a 'success.' This was not because I rejoice in clergymen getting arrested, but rather, because this was what I was looking for. And if the status of the individual was settled, reinstated, acquitted, or had their charges dropped, I failed to find what I was looking for, and as such, labeled those options as 'failures.' Initially, I had two separate views that counted the successes and failures and put them into two tables. However, I found that employing the CASE WHEN query created a table that was significantly cleaner and easier to read, with the added bonus of only using one table.

I then modified the view to breakdown the successes/failures by Diocese or Order. This allows analysis on how frequently members of certain orders are let off the hook when compared to other denominations.

The two views are labled "TotalSuccessandFail" and "OrderBreakdown."
