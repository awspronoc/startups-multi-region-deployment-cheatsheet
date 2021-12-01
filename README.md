# Startups Multi Region Deployment Cheatsheet & Reources


## AWS Global Infrastructure

[AWS Global infrastructure map](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/?p=ngi&loc=2)

## Multi Region Deployment examples

* [Serverless multi-Region deployment](https://aws.amazon.com/solutions/implementations/multi-region-application-architecture/)
* [Multi-region programmatic deployment](https://aws.amazon.com/solutions/implementations/multi-region-infrastructure-deployment/?did=sl_card&trk=sl_card)
* [Asynchronous Object Replication Solution](https://aws.amazon.com/solutions/implementations/multi-region-asynchronous-object-replication-solution/?did=sl_card&trk=sl_card)


## How to choose the right tool for the right job (AWS Databases)

* [Re:Invent 2018: The Right Tool for the Right Job by Shawn Bice](https://www.youtube.com/watch?v=-pb-DkD6cWg)

## Infrastructure-as-Code resources

* [AWS Cloud Development Kit API Reference](https://docs.aws.amazon.com/cdk/api/latest/docs/aws-construct-library.html)
* [AWS CloudFormation](https://aws.amazon.com/cloudformation/faqs)
* [Create CFn templates using Former 2](https://aws.amazon.com/blogs/opensource/accelerate-infrastructure-as-code-development-with-open-source-former2/)


## Managed database services replication options

* [Amazon Aurora Global Database](https://aws.amazon.com/rds/aurora/global-database/)
* [Amazon DynamoDB Global Tables](https://aws.amazon.com/dynamodb/global-tables/)

## Whitepaper

* [Disaster Recovery White Paper](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-options-in-the-cloud.html)


## re:Invent 2021 multi-Region announcements

* [EFS Replication](https://aws.amazon.com/efs/features/)
* [AWS Backup support for S3](https://aws.amazon.com/blogs/aws/preview-aws-backup-adds-support-for-amazon-s3/)

## Best practices

* Triage and replicate
* Immutable architecture
* Rely on infrastructure as code
* Use serverless wherever you can
* Use Route53 for automatic failover
* Rely on managed services for faster failover & replication

## Call to action

* Create a snapshot of your current infrastructure
* Figure out what are critical workloads
* Create a failover play-book
* Get in touch with an SA if you need help!