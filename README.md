# Module-16-Amazon_Vine_Analysis

## Overview

We are reviewing the Amazon vine program to determine favorable bias views from our members. We will be performing the ETL process with pyspark. Extracting the data for cleaning transforming and connecting to a AWS RDS instance. Afterward we will load the data into Pgadmin for storage. For our Analysis we will be focusing on US review for video games.

## Resources
* AWS Reviewed Dataset: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt
* Video Game review dataset:https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz
* Google Collab
* AWS
* PGadmin & Postgresql

## Results

### 5 Star Reviews

#### Vine Reviews
<img width="865" alt="Screen Shot 2021-10-10 at 9 41 23 AM" src="https://user-images.githubusercontent.com/83923903/136705376-1dba3be1-ba5e-4a0f-ab13-0ea0e0ed594b.png">

#### Non Vine Reviews
<img width="884" alt="Screen Shot 2021-10-10 at 9 41 31 AM" src="https://user-images.githubusercontent.com/83923903/136705390-c03aac9c-5914-4284-a4ce-ecfa1e465dd4.png">


### Total Reviews

#### Vine Reviews

<img width="1345" alt="Screen Shot 2021-10-10 at 9 38 20 AM" src="https://user-images.githubusercontent.com/83923903/136705279-9749643e-5f46-4962-9426-2185abe231dd.png">

#### Non Vine Reviews

<img width="1104" alt="Screen Shot 2021-10-10 at 9 38 38 AM" src="https://user-images.githubusercontent.com/83923903/136705299-a1e35b6f-e75b-4088-85f7-d2cdab35a958.png">


### Percentage Breakdown

#### Vine Reviews
<img width="663" alt="Screen Shot 2021-10-10 at 9 43 32 AM" src="https://user-images.githubusercontent.com/83923903/136705434-63081615-1657-4810-b2f1-4a3d82551861.png">

#### None Vine Review
<img width="641" alt="Screen Shot 2021-10-10 at 9 43 43 AM" src="https://user-images.githubusercontent.com/83923903/136705438-44de1117-194c-4d43-bc50-625a5f300c53.png">


## Summary

Based on our Analysis, only 39% of non-vine reviews rated a 5 star review, where as over 51% of the reviews from Amazon Vine program rated a 5 star review. We can describe that users in the Vine program has a positive bias when reviewing. To build further deeper analysis, I think we should analyze the mean, median and mode, for the distribution star ratings of Vine reviews vs non vine reviews. 
