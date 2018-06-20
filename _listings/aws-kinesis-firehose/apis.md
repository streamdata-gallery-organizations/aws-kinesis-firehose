---
name: AWS Kinesis Firehose
x-slug: aws-kinesis-firehose
description: Amazon Kinesis Firehose is the easiest way to loadstreaming datainto
  AWS. It can capture, transform,and load streaming data intoAmazon Kinesis Analytics,Amazon
  S3,Amazon Redshift, andAmazon Elasticsearch Service, enabling near real-time analytics
  with existing business intelligence tools and dashboards you&rsquo;re already using
  today. It is a fully managed service that automatically scales to match the throughput
  of your data and requires no ongoing administration. It can also batch, compress,
  and encrypt the data before loading it, minimizing the amount of storage used at
  the destination and increasing security.You can easily create a Firehose delivery
  stream from theAWS Management Console, configure it with a few clicks, and start
  sending data to the stream from hundreds of thousands of data sources to be loaded
  continuously to AWS &ndash; all in just a few minutes.With Amazon Kinesis Firehose,
  you only pay for the amount of data you transmit through the service. There is no
  minimum fee or setup cost.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Kinesis Firehose
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Kinesis Firehose API Create Delivery Stream
  x-api-slug: aws-kinesis-firehose-api
  description: creates a delivery stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
  humanURL: https://aws.amazon.com/kinesis/firehose/
  baseURL: ://///?Action=CreateDeliveryStream
  tags: Delivery Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/actioncreatedeliverystream-get-openapi.md
- name: AWS Kinesis Firehose API Delete Delivery Stream
  x-api-slug: aws-kinesis-firehose-api
  description: deletes a delivery stream and its data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
  humanURL: https://aws.amazon.com/kinesis/firehose/
  baseURL: ://///?Action=DeleteDeliveryStream
  tags: Delivery Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/actiondeletedeliverystream-get-openapi.md
- name: AWS Kinesis Firehose API Describe Delivery Stream
  x-api-slug: aws-kinesis-firehose-api
  description: describes the specified delivery stream and gets the status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
  humanURL: https://aws.amazon.com/kinesis/firehose/
  baseURL: ://///?Action=DescribeDeliveryStream
  tags: Delivery Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/actiondescribedeliverystream-get-openapi.md
- name: AWS Kinesis Firehose API List Delivery Streams
  x-api-slug: aws-kinesis-firehose-api
  description: lists your delivery streams.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
  humanURL: https://aws.amazon.com/kinesis/firehose/
  baseURL: ://///?Action=ListDeliveryStreams
  tags: Delivery Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/actionlistdeliverystreams-get-openapi.md
- name: AWS Kinesis Firehose API Put Record
  x-api-slug: aws-kinesis-firehose-api
  description: writes a single data record into an Amazon Kinesis Firehose delivery
    stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
  humanURL: https://aws.amazon.com/kinesis/firehose/
  baseURL: ://///?Action=PutRecord
  tags: Records
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/actionputrecord-get-openapi.md
- name: AWS Kinesis Firehose API Put Record Batch
  x-api-slug: aws-kinesis-firehose-api
  description: |-
    writes multiple data records into a delivery stream in a single call, which can
             achieve higher throughput per producer than when writing single records.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
  humanURL: https://aws.amazon.com/kinesis/firehose/
  baseURL: ://///?Action=PutRecordBatch
  tags: Records
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/actionputrecordbatch-get-openapi.md
- name: AWS Kinesis Firehose API Update Destination
  x-api-slug: aws-kinesis-firehose-api
  description: updates the specified destination of the specified delivery stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
  humanURL: https://aws.amazon.com/kinesis/firehose/
  baseURL: ://///?Action=UpdateDestination
  tags: Destinations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/actionupdatedestination-get-openapi.md
- name: AWS Kinesis Firehose API
  x-api-slug: aws-kinesis-firehose-api
  description: Amazon Kinesis Firehose is the easiest way to loadstreaming datainto
    AWS. It can capture, transform,and load streaming data intoAmazon Kinesis Analytics,Amazon
    S3,Amazon Redshift, andAmazon Elasticsearch Service, enabling near real-time analytics
    with existing business intelligence tools and dashboards you&rsquo;re already
    using today. It is a fully managed service that automatically scales to match
    the throughput of your data and requires no ongoing administration. It can also
    batch, compress, and encrypt the data before loading it, minimizing the amount
    of storage used at the destination and increasing security.You can easily create
    a Firehose delivery stream from theAWS Management Console, configure it with a
    few clicks, and start sending data to the stream from hundreds of thousands of
    data sources to be loaded continuously to AWS &ndash; all in just a few minutes.With
    Amazon Kinesis Firehose, you only pay for the amount of data you transmit through
    the service. There is no minimum fee or setup cost.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisFirehose.png
  humanURL: https://aws.amazon.com/kinesis/firehose/
  baseURL: :///
  tags: AWS Kinesis Firehose
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-firehose/master/_listings/aws-kinesis-firehose/openapi.md
x-common:
- type: x-console
  url: https://console.aws.amazon.com/firehose/
- type: x-documentation
  url: http://docs.aws.amazon.com/firehose/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/kinesis/firehose/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/kinesis/firehose/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/kinesis/firehose/pricing/
- type: x-website
  url: https://aws.amazon.com/kinesis/firehose/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---