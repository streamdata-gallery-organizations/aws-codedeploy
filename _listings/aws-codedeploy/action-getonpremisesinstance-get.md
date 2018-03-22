---
swagger: "2.0"
info:
  title: AWS CodeDeploy API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetOnPremisesInstance:
    get:
      summary: ' Get On Premises Instance '
      description: Gets information about an on-premises instance
      operationId: getOnPremisesInstance
      parameters:
      - in: query
        name: instanceName
        description: The name of the on-premises instance about which to get information
        type: string
      responses:
        200:
          description: OK
      tags:
      - on premises instances
definitions: []
x-collection-name: AWS CodeDeploy
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