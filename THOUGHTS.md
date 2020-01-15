# This Course

## Trends
 - Cloud managed NoSQL (theirs or vendor)
 - Consolidation of NoSQL providers
 - Big data is here (genomics, others...)
 - Event (streams) vs Batches (or Incremental)
 - Serverless

 ## How to Store
 - Files (regular or HDFS)
    -> Cloud Object Stores (S3...)
 - Relational Tables
 - Customized File systems
    - With structures on top (like tables)

 ## How to Query
 - Files -> write code
    - is becomming use SQL **NEW**
 - Tables -> write SQL and/or use ORM
 - Customized File systems
    - NoSQL or Hadoop/Spark
    - was write code
    - adding use SQL-like syntax

## How to optimize
 - Files -> compress, split
 - Tables -> same and archive
    - add indexes
 - Customized Files systems
    - use file AND table options

## When to Use
 - Files -> massive amounts of data (genomic)
 - Tables -> transactions
 - Customized -> everything else
    - prefer cloud vendor to OSS
        - better integration 
            - vendor 'ORM's'

## Open Source or Not
- True cost of pure open source
- True cost of 'productized' open source
- Reasons to use vendor-integrated NoSQL

## Use Cases
- Mobile on AWS
- Genomics on AWS
- Genomics on GCP