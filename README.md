# Kusto_Detective_Agency
![Kusto Detective Agency Logo](https://images.credly.com/images/43b452c6-89f2-4649-bb84-19f3166a833e/image.png "Kusto Detective Agency Log")

My solutions for the Kusto Detective Agency cases as I try to solve them while learning how to use Azure Data Explorer.


## On-Boarding - Welcome
This provided a simple yet effective introduction to KQL, nothing much to say about it.


## Case 1 - Missing Book
![Case 1 Picture](/img/case1.png "Case 1 Picture")

Finding the book proved an interesting challenge. I quickly realised it had to do with comparing the total weight of the books on the shelf, i.e. the weight the shelf should have, and the weight of the shelf according to the data. After that it was a case of simply finding the correct commands to figure out which one had the highest difference.


## Case 2 - Election Fraud
![Case 2 Picture](/img/case2.png "Case 2 Picture")

This felt like a massive step up from the previous case, and required me to explore the dataset in-depth to figure out how to normalise the votes. After understanding how to use bin() and series_decompose_anomalies(), as well as other intermediary functions I managed to solve the case. 


## Case 3 - Bank Robebry
With all the testing and failing I did for case 2 I managed to smash this one out pretty quickly.

// TODO: Rewrite all of these, should explain a bit more the method I used, not these unhelpful sentences
