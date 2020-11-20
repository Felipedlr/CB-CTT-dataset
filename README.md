# CB-CTT dataset

In this repository, we include the data employed to analyze the empirical hardness of Curriculum-Based Course Timetabling (CB-CTT) Instances represented using the XHSTT format (https://www.utwente.nl/en/eemcs/dmmp/hstt/). We solved 6,000 instances using the KHE Timetabling Engine (http://jeffreykingston.id.au/khe/) and classify them according to the penalty value (i.e., cost) of their solutions. Based on this data, we followed the feature selection methodology described in the article "Measuring the complexity of university timetabling instances" (https://link.springer.com/article/10.1007/s10951-020-00641-y) to identify the main factors that make CB-CTT instances hard to solve.

The file "Data.csv" is organized as follows. The first column describes the hardness of the instances, classified as Very Easy, Easy, Medium, Hard, and Very Hard. The second column records the penalty value of the solutions obtained by the KHE Timetabling Engine. The rest of the columns correspond to the features calculated to describe the instances after removing uni-valued features (i.e., features with the same value in all instances).
 
