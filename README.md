# AWS-ElasticSearch
Documentation guidance on AWS ES
Elasticsearch is an open-source database tool that can be easily deployed and operated. It is used for the analytic purpose and searching your logs and data in general. Basically, it is a NoSQL database to store the unstructured data in document format. Besides from that, if we talk about AWS Elasticsearch, it is like the Amazon which is easier as a service to create it in the clouds. You can use it for various purposes not only for online poor checking your logs or data, but you can also connect it to your cloud watch and use it for modeling after creating the AWS Elasticsearch.

There may be several ways to add data or connect it with your logs after creating the AWS Elasticsearch. We can use it by API and send the bulk data or files. We can also connect with it using any of our code to do this automatically. You can use third-party plugins with AWS Elasticsearch, e.g., Amazon s3 River plugin. AWS Elasticsearch makes things simpler to its users as they do not need to manually create an Elasticsearch cluster. It allows the user to visualize, analyze, and search the data in real-time.

Concept of AWS Elasticsearch
There are following concepts of AWS Elasticsearch -

Amazon Elasticsearch domain and Elasticsearch cluster are identical to each other. Domains are the clusters with instance type, instance count, settings, and storage resources that you specify.
It allows us to create one or more Elasticsearch indices within the same domain.
A blue/green deployment process is used by Amazon Elasticsearch while updating the domain. It refers to the practice of running two production environments that are one live and one idle.
AWS automatically updates the service software after a certain timeframe if you do not take any action on the required updates.

Advantages:

1) Easily usable
In Amazon Elasticsearch, all the services are fully managed, and this makes it easy to use. We can save time for backup, failure recovery, software patching, and monitoring. The users of AWS Elasticsearch can post the production-ready Elasticsearch cluster using AWS Elasticsearch within a few seconds. They do not need to worry about the installation and maintenance of Elasticsearch software.

2) Highly secure
AWS Elasticsearch is highly secure. It is easy to set up secure access to Amazon Elasticsearch Service from the VPC. It is done for the perfect maintenance of VPC. AWS IAM and Amazon Cognito policies help to manage authentication and access control. Users can achieve network isolation with Amazon VPC for their data in Elasticsearch service.

3) Cost-effective
One of the biggest advantage of Amazon Elasticsearch service is that you need to pay only for those resources you consume. It gives a choice to its users that they can select on-demand pricing with no upfront costs. As we already said, that Amazon Elasticsearch service is a fully managed service; it reduces the cost of operations by eliminating the Elasticsearch experts team to manage and monitor the clusters.

4) Easily scalable and available
AWS Elasticsearch is a highly scalable tool. It enables the users to store up to 3 PB data in a single cluster. Besides from that, it also allows the users to run the large log analytics workloads through the user interface such as Kibana. The cluster can be easily up and down through a single API call or by a few clicks in the AWS console.

Multi-AZ deployments allow replicating data between three availability zones in the same region. Using this, Elasticsearch is designed to be highly available.

5) Tightly integrated with AWS Services
AWS Elasticsearch has built-in integrations with AWS services. This includes AWS IOT, CloudWatch Logs, and Kinesis Firehose for seamless data ingestion.

6) Support Open Source APIs
AWS Elasticsearch does not require any new software or programming skills and provides direct access to open-source API. Logstash, an open-source data ingestion, is supported by the AWS Elasticsearch services. Along with Logstash, it also supports Kibana which is a data visualization tool. The combination of all three tools is known as ELK Stack.

Limitations of AWS Elasticsearch
Along with several advantages, there are few limitations of AWS Elasticsearch, which are as follows -

It allows the users to launch their domain within a VPC or use a public endpoint. Although both actions are not allowed to be performed together in it.
