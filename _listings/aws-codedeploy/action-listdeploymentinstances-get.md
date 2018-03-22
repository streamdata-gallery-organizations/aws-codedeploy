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
  /?Action=ListDeploymentInstances:
    get:
      summary: ' List Deployment Instances '
      description: |-
        Lists the instance for a deployment associated with the applicable IAM user or AWS
                    account
      operationId: listDeploymentInstances
      parameters:
      - in: query
        name: deploymentId
        description: The unique ID of a deployment
        type: string
      - in: query
        name: instanceStatusFilter
        description: 'A subset of instances to list by status:'
        type: string
      - in: query
        name: nextToken
        description: An identifier returned from the previous list deployment instances
          call
        type: string
      responses:
        200:
          description: OK
      tags:
      - deployment instances
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