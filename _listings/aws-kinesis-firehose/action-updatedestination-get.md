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
  /?Action=UpdateDestination:
    get:
      summary: ' Update Destination '
      description: updates the specified destination of the specified delivery stream
      operationId: UpdateDestination
      parameters:
      - in: query
        name: CurrentDeliveryStreamVersionId
        description: Obtain this value from the VersionId result of             DeliveryStreamDescription
        type: string
      - in: query
        name: DeliveryStreamName
        description: The name of the delivery stream
        type: string
      - in: query
        name: DestinationId
        description: The ID of the destination
        type: string
      - in: query
        name: ElasticsearchDestinationUpdate
        description: Describes an update for a destination in Amazon ES
        type: string
      - in: query
        name: ExtendedS3DestinationUpdate
        description: Describes an update for a destination in Amazon S3
        type: string
      - in: query
        name: RedshiftDestinationUpdate
        description: Describes an update for a destination in Amazon Redshift
        type: string
      - in: query
        name: S3DestinationUpdate
        description: '[Deprecated] Describes an update for a destination in Amazon
          S3'
        type: string
      responses:
        200:
          description: OK
      tags:
      - destinations
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