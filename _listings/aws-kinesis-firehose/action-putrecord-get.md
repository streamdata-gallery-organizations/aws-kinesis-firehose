---
swagger: "2.0"
info:
  title: AWS Kinesis Firehose API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PutRecord:
    get:
      summary: ' Put Record '
      description: writes a single data record into an Amazon Kinesis Firehose delivery
        stream
      operationId: PutRecord
      parameters:
      - in: query
        name: DeliveryStreamName
        description: The name of the delivery stream
        type: string
      - in: query
        name: Record
        description: The record
        type: string
      responses:
        200:
          description: OK
      tags:
      - records
definitions: []
x-collection-name: AWS Kinesis Firehose
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---