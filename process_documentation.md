# Process Documentation Log
#### This file will be a log of my process and thoughts as I complete the Coursera captstone project.
---
#### Section Links:
[Preperation Phase](process_documentation.md#preperation-phase)

[Process Phase](process_documentation.md#process-phase)

 ---
### Preparation Phase

#### # Storage 
  *-Let's store the data locally in preparation for sorting and cleaning before uploading to BigQuery.*

  1. Data downloaded from [https://divvy-tripdata.s3.amazonaws.com/index.html](https://divvy-tripdata.s3.amazonaws.com/index.html).
  2. Data chosen: *202310-divvy-tripdata.zip*.
  3. *202310-divvy-tripdata.csv* saved locally to project folder *capstone_project_20231110*.

#### # Organization 
  *-We need to identify how the data is organized so we can better understand its credibility.*

  1. Who collected and provided the data?

     *-[Motivate LLC](https://en.wikipedia.org/wiki/Motivate_(company))*
  2. Is it a credible source?

     *-Yes, Motivate LLC is a bike share service provider with a known history.*
  3. Can the data be publically scrutinized for errors?
   
     *-Yes, it is a publically available data set that anyone can use or critique.*
  4. Is the data recent enough to be useful?

     *-Yes, the data was collected during 2023.*
  5. What license is being used to access and use this data?

     *-The data is being accessed under the [https://divvybikes.com/data-license-agreement](https://divvybikes.com/data-license-agreement) license.*
  6. Privacy, security and accessibility, in brief.

     *-There is no unique identifiable user data in the data set, the local data set is not secured beyond a windows login, the cleaned data set wll be publically available for review.*
  7. Has the data integrity been preserved during transfer?

     *-By comparing hash values for the files we can confirm the data has not been corrupted during transfer.*
   
  
   8. Are there issues with the data?
      >[!WARNING]
      >*-Yes, there are many rows with missing data that will need to removed or reconcilled based on contextual data points to fill in the blanks.*
      
 ---
### Process Phase
