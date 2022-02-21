The data used in this analysis is an Online Shoppers Purchasing Intention data set provided on the UC Irvine’s Machine Learning Repository (Source: Kaggle). The data set was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.The primary purpose of the data set is to predict the purchasing intentions of a visitor to this particular store’s website.
12,330 sessions in the dataset, 84.5% (10,422) were negative class samples that did not end with shopping, and the rest (1908) were positive class samples ending with shopping.

Attribute Information :
The dataset consists of 10 numerical and 8 categorical attributes. 

"Revenue" - class label of purchase
"Administrative", "Administrative Duration", "Informational" - Page Type
"Informational Duration", "Product Related" and "Product Related Duration" -the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another. 

"Bounce Rate” - metric measured by "Google Analytics”. A web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session.
"Exit Rate” - metric measured by "Google Analytics”. A specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session.
"Page Value” - metric measured by "Google Analytics”. The average value for a web page that a user visited before completing an e-commerce transaction. 

"Special Day" - indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 

The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.
