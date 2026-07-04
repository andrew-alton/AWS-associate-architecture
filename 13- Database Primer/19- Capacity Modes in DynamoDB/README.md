# Capacity Modes in DynamoDB

"Adjust Throughput Automatically"

## Understanding the Challenge

We can specify throughput capacity in terms of read capacity units (RCUs) and write capacity
units

If your application exceeds your provisioned throughput capacity on a table or index, it is
subject to request throttling.

<div align="center">
<img src="images/image1.png"  width="75%">
</div>

## Types of Capacity Modes

There are two primary capacity modes available in DynamoDB.

<div align="center">
<img src="images/image2.png"  width="75%">
</div>

## Provisioned Mode

If you choose provisioned mode, you specify the number of reads and writes per second that you
require for your application.
You can use auto scaling to adjust your table’s provisioned capacity automatically in response to
traffic changes.

<div align="center">
<img src="images/image3.png"  width="75%">
</div>

## Recommended Traffic Patterns for Provisioned Mode

Provisioned mode is a good option if any of the following are true:

● You have predictable application traffic.

● You run applications whose traffic is consistent or ramps gradually.

● You can forecast capacity requirements to control costs.

## On-Demand Mode

Amazon DynamoDB on-demand is capable of serving thousands of requests per second
without capacity planning.

DynamoDB on-demand offers pay-per-request pricing for read and write requests so that you
pay only for what you use.

<div align="center">
<img src="images/image4.png"  width="75%">
</div>
