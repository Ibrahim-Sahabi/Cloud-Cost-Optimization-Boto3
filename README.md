# Cloud-Cost-Optimization-Boto3

### Why Lambda?

Lambda functions are serverless, it doesn't mean there aren't any servers. It just means that you don't have the manage the underlying servers. All you have to do is write code to perform your desired actions. For this function, you have to add a trigger i.e., for the function to be triggered when an EC2 instance is deleted. This action leads to the running of the function, which will check if any stale snapshots created from the deleted instance exist and delete.
Lambda functions are serverless, it doesn't mean there aren't any servers. It just means that you don't have to manage the underlying servers. All you have to do is write code to perform your desired actions. For this function, you have to add a trigger i.e., for the function to be triggered when an EC2 instance is deleted. This action leads to the running of the function, which will check if any stale snapshots created from the deleted instance exist and delete.

A Lambda function is developed utilizing AWS Boto3, which is an AWS SDK, to automate the identification and deletion of stale snapshots, thus optimizing cloud expenses. Through proactive management of snapshots, the Lambda function contributes to cost optimization strategies within AWS environments.





A Lambda function is developed utilizing AWS Boto3 services to automate the identification and deletion of stale snapshots, thus optimizing cloud expenses. This function efficiently manages AWS resources by identifying snapshots that are no longer needed and removing them, thereby reducing unnecessary storage costs. Through proactive management of snapshots, the Lambda function contributes to cost optimization strategies within AWS environments.

