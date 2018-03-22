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
  /?Action=ListDeliveryStreams:
    get:
      summary: ' List Delivery Streams '
      description: lists your delivery streams
      operationId: ListDeliveryStreams
      parameters:
      - in: query
        name: ExclusiveStartDeliveryStreamName
        description: The name of the delivery stream to start the list with
        type: string
      - in: query
        name: Limit
        description: The maximum number of delivery streams to list
        type: string
      responses:
        200:
          description: OK
      tags:
      - delivery streams
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