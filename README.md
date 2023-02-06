# Kusto_Detective_Agency
![Kusto Detective Agency Logo](/img/kusto.png "Kusto Detective Agency Log")
My solutions for the Kusto Detective Agency cases as I try to solve them while learning how to use Azure Data Explorer.


## On-Boarding: Welcome
This provided a simple yet effective introduction to KQL, nothing much to say about it.

## Case 1: Missing Book
![Case 1 Picture](/img/case1.png "Case 1 Picture")
Finding the book proved an interesting challenge. I quickly realised it had to do with comparing the total weight of the books on the shelf, i.e. the weight the shelf should have, and the weight of the shelf according to the data. After that it was a case of simply finding the correct commands to figure out which one had the highest difference.



## Case 2: Election Fraud
![Case 2 Picture](/img/case2.png "Case 2 Picture")
This felt like a massive step up from the previous case, and required me to explore the dataset in-depth to figure out how to normalise the votes. After understanding how to use bin() and series_decompose_anomalies(), as well as other intermediary functions I managed to solve the case. 


