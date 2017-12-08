# Roadblocks and Difficulties
One of the more difficult challenges presented by this assignment was finding pertinent data to add to the database itself. When I originally started this project, I intended to see if I could find a correlation between number of cases settled outside of court and the percentage of the population that Catholics made up in the respective state. However, because the populations (and demographics) of the states are not static, and the cases are spread throughout time, it is difficult to make an accurate comparison. Instead, I opted to focus on the breakdown of cases with regard to order and type.

The first, and as it turns out, easiest part of finding this information was to take the data from the internet and make it usable in MySQL. Google Chrome's webscraper extension was easy to use and made this process relatively headache-free. Once the data was on my local device, I ran it through OpenRefine to 'clean it up.'

At this stage, I was able to migrate the data over to MySQL. However, when I initially attempted this, only twenty of my 3000+ rows were being imported. Much to my embarrassment, the issue was with the format that I saved the file as. I was trying to import the data that was saved as a standard CSV file when I needed it as a more specialized CSV UTF-8 format in order to preserve some of the characters in the worksheet. Once I converted the file to this format, the importation process was able to be completed.

I was able to start querying the data once it was in MySQL. After numerous attempts of rearranging the data to find anything substantial, the idea of breaking down the status by type came to me. The assignment moved quickly once I had a direction with which to go. Writing the queries provided their own set of challenges which are easily attributed to beginner mistakes.

If I was to offer any advice to someone attempting a similar project, I would say be familiar with one's own limitations. I originally intended to complete an ambitious database that had outside statistics to further the conclusions that can be reached by reading this database, however, my relative lack of experience made this slightly more than infeasible. Once I was able to set my sights on something more attainable, the work progressed much more quickly.


Describe how your overall process progressed. You can share any particular victories here, if you wish, but you should also share obstacles you ran into. Roadblocks can be general in nature (e.g. difficulty of obtaining data, normalizing it, etc..), or they can also be very specific (difficulties trying to get a certain query to work right, or a certain column not acting as expected). Most importantly, reflect on how you might deal with these problems if you were to attempt it again. What advice would you give to someone else trying this project?

Describe how your overall process progressed. You can share any particular victories here, if you wish, but you should also share obstacles you ran into. Roadblocks can be general in nature (e.g. difficulty of obtaining data, normalizing it, etc..), or they can also be very specific (difficulties trying to get a certain query to work right, or a certain column not acting as expected). Most importantly, reflect on how you might deal with these problems if you were to attempt it again. What advice would you give to someone else trying this project?

Describe how your overall process progressed. You can share any particular victories here, if you wish, but you should also share obstacles you ran into. Roadblocks can be general in nature (e.g. difficulty of obtaining data, normalizing it, etc..), or they can also be very specific (difficulties trying to get a certain query to work right, or a certain column not acting as expected). Most importantly, reflect on how you might deal with these problems if you were to attempt it again. What advice would you give to someone else trying this project?

[Thing you want it to say on the page](http://wheretogo.com)

![Thing you want it to say on the pop-up caption](http://linktoimage.png)

---

* Bullet 1
  * You can nest bullet points
* Bullet 2
- This is just the same

1. This is an ordered list
2. This is the second item
  1. This is a subitem
  128457463. This will still read as sub item 2

This is *italic* this is **bold** this is __underline__

This is a code block
```

```

This is just `inline` block.
