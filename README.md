# BBC-News-Youtube-Data
Data collected by Youtube API and Python used for analysis. These steps followed : 
1. Data Cleaning : Null and NaN values and irrelevant columns detected and deprecated.
2. Formatting datatypes : Video duration column datatype converted from timedelta to minute.
3. Enriching data; for further analysis new calculated columns added, especially duration and tags count categories created.From publishedAt, publishedDay and publishedYear extracted.
4. Simple statistics covered ; max, min, avg and correlation between columns.


FINDINGS:
In an interesting way, the analysis showed that the number of comments is higher than the number of likes which is the opposite way in general. 
Also over the years, Wednesday has the highest number of video published.
Between 2013 and 2022, there are many days with more videos shared than normal, at the beginning of these events 2019-12-13 (election in the UK) attracts attention. 
