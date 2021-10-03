Insiderthreat provides a compiled list CSV list of users, dates, pc,content, to ,and from email headers address, size, attachment, content, state/province,country, and Timezone.


Objectives:

1. First objective is to provide a correlation between the emails that contained attachment vs no attachments, along with removing unecessary columns such as pc, usernames, and the size. 
2. Next, creating a plot and whisker chart showing the outliers to the attachments, and scattered plot for the same attachment metrics. 
3. My next objective is find duplicates of the same email headers with attachments that correlate to country, and produce a geopandas map of those targets that may be insider threats. i suspect there will be multiple emails with attachments containing indicators of compromise (IOCs), but the same email addresses will come from different countries, and even different timelines. If this were to be true i suspect it will be based on masking location if the attachments/content is suspicious - thus indicating signs of insider threats. 


Limitations:
4. My problems as of now is finding a script to form map of the world in the country, or state province  to create visual. I am currently struggling with importing geopandas. Then my next goal/struggle is take the the malicious content and filter it with pandas and see if there is a similarity of From, and To emails.
