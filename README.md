# Segment customers based on RFM model using K-Means

**1. Business Request:**

Business plan to launch one Free trial subcription program. The target of this program is after using free trial, customers will buy a paid subscription package. 
Business concerns which type of customer that will be potential for the target of the program. 

**2. Main Idea:**

Segment customer based on RFM model. After that, running testing on half of customers of each score, then build the predict model for other customers based on the testing data. 



Using the RFM model to define the target customer segmentation. 

R (Recency): the time from the last action in app until now 

F (Frequency): the number of actions in app in L6M (action: purchase, add to cart)

M (Monetory): the total value of the orders in L6M

With using K-Means, we will score each customers based on each metrics in their RFM performance. A customer who have higher score will be more potential for the program. Also, with scoring each customers, business also can have different approach methods for each customer's score range. 
