# Dealing-with-missing-values
Missing values:
- values that are not recorded in a dataset
- represented in the form of Nan or null or None in the dataset.

Why the data is missing?


Missing at Random the data is missing relative to the observed data. The missing data can be predicted based on the complete observed data, e.g. if a child does not attend an educational assessment because the child is (genuinely) ill.
Missing Completely at Random the reasons for its absence are external and not related to the value of the observation. It is typically safe to remove MCAR data, e.g. blood sample might be damaged in the lab
Missing Not at Random there are reasons why the data is missing, but the data cannot be determined by the observed data, because the missing information is unknown, e.g. a person does not attend a drug test because the person took drugs the night before.

References.
1. Data School channel.26 May 2016.How do I handle missing values in pandas?. [https://www.youtube.com/watch?v=fCMrO_VzeL8](https://www.youtube.com/watch?v=fCMrO_VzeL8)
2. Martin Bland’s text book. *An Introduction to Medical Statistics, Fourth Edition. pages 306–307.*[https://www-users.york.ac.uk/~mb55/intro/typemiss4.htm](https://www-users.york.ac.uk/~mb55/intro/typemiss4.htm)
3. Master's in Data Science.[https://www.mastersindatascience.org/learning/how-to-deal-with-missing-data/](https://www.mastersindatascience.org/learning/how-to-deal-with-missing-data/)


