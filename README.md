# Sparkify Data Warehouse

<p align = 'center'><img src = 'https://www.levi9.com/wp-content/uploads/2021/09/Levi9-AWS-Redshift-Program-V2.png'/></p>

## Project objectives

- Moving Database to the cloud for scalability and performance.
- Learning Amazon Redshift architecture.
- Learning how to load data into and from an S3 bucket.

## To run project scripts

1. Run the following command in your terminal: <br> <pre><code>pip install -r requirements.txt</code></pre>
2. Run create_tables.py to connect to the Redshift cluster and create Database tables if they don't exist, and if they exist they will be dropped and re-created. <br> WARNING: will drop tables if they exist when intiated.
3. Run etl.py to load the data to the created Database.
