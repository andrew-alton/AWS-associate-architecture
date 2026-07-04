# RDS Read Replicas

## Use Case : Bank

In bank, for different kind of work purpose, there are different people you might
have to approach. For example :

- Cash Collector
- Cheque Counter
- Enquiry Counter

<div align="center">
<img src="images/image1.png"  width="50%">
</div>

## Database Way

Using a single database for all kind of activity will increase the database load
and slow down the operations.

<div align="center">
<img src="images/image2.png"  width="50%">
</div>

## Improved Architecture - Read Replica

Read Replica allows customers to offload read requests or analytics traffic from
the primary instance

<div align="center">
<img src="images/image3.png"  width="50%">
</div>

## RDS Read Replica

RDS Read Replica feature allows customers to implement “Database Read
Replica” functionality for RDS databases.

<div align="center">
<img src="images/image4.png"  width="50%">
</div>

## Pointers to Note - 1

You can create one or more replicas of a given source DB Instance and serve
high-volume application read traffic.

<div align="center">
<img src="images/image5.png"  width="50%">
</div>

## Pointers to Note - 2

With Amazon RDS, you can create a read replica in a different AWS Region
from the source DB instance.

<div align="center">
<img src="images/image6.png"  width="50%">
</div>
