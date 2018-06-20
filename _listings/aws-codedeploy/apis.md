---
name: AWS CodeDeploy
x-slug: aws-codedeploy
description: AWS CodeDeploy is a service that automates code deployments to any instance,
  including Amazon EC2 instances and instances running on-premises. AWS CodeDeploy
  makes it easier for you to rapidly release new features, helps you avoid downtime
  during application deployment, and handles the complexity of updating your applications.
  You can use AWS CodeDeploy to automate software deployments, eliminating the need
  for error-prone manual operations, and the service scales with your infrastructure
  so you can easily deploy to one instance or thousands.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS CodeDeploy
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CodeDeploy API Add Tags To On Premises Instances
  x-api-slug: aws-codedeploy-api
  description: Adds tags to on-premises instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=AddTagsToOnPremisesInstances
  tags: Premises Instances Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionaddtagstoonpremisesinstances-get-openapi.md
- name: AWS CodeDeploy API Batch Get Application Revisions
  x-api-slug: aws-codedeploy-api
  description: Gets information about one or more application revisions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetApplicationRevisions
  tags: Application Revisions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionbatchgetapplicationrevisions-get-openapi.md
- name: AWS CodeDeploy API Batch Get Applications
  x-api-slug: aws-codedeploy-api
  description: Gets information about one or more applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetApplications
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionbatchgetapplications-get-openapi.md
- name: AWS CodeDeploy API Batch Get Deployment Groups
  x-api-slug: aws-codedeploy-api
  description: Gets information about one or more deployment groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetDeploymentGroups
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionbatchgetdeploymentgroups-get-openapi.md
- name: AWS CodeDeploy API Batch Get Deployment Instances
  x-api-slug: aws-codedeploy-api
  description: |-
    Gets information about one or more instance that are part of a deployment
                group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetDeploymentInstances
  tags: Deployment Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionbatchgetdeploymentinstances-get-openapi.md
- name: AWS CodeDeploy API Batch Get Deployments
  x-api-slug: aws-codedeploy-api
  description: Gets information about one or more deployments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetDeployments
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionbatchgetdeployments-get-openapi.md
- name: AWS CodeDeploy API Batch Get On Premises Instances
  x-api-slug: aws-codedeploy-api
  description: Gets information about one or more on-premises instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetOnPremisesInstances
  tags: On Premises Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionbatchgetonpremisesinstances-get-openapi.md
- name: AWS CodeDeploy API Create Application
  x-api-slug: aws-codedeploy-api
  description: Creates an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=CreateApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actioncreateapplication-get-openapi.md
- name: AWS CodeDeploy API Create Deployment
  x-api-slug: aws-codedeploy-api
  description: Deploys an application revision through the specified deployment group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=CreateDeployment
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actioncreatedeployment-get-openapi.md
- name: AWS CodeDeploy API Create Deployment Config
  x-api-slug: aws-codedeploy-api
  description: Creates a deployment configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=CreateDeploymentConfig
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actioncreatedeploymentconfig-get-openapi.md
- name: AWS CodeDeploy API Create Deployment Group
  x-api-slug: aws-codedeploy-api
  description: |-
    Creates a deployment group to which application revisions will be
                deployed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=CreateDeploymentGroup
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actioncreatedeploymentgroup-get-openapi.md
- name: AWS CodeDeploy API Delete Application
  x-api-slug: aws-codedeploy-api
  description: Deletes an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=DeleteApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiondeleteapplication-get-openapi.md
- name: AWS CodeDeploy API Delete Deployment Config
  x-api-slug: aws-codedeploy-api
  description: Deletes a deployment configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=DeleteDeploymentConfig
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiondeletedeploymentconfig-get-openapi.md
- name: AWS CodeDeploy API Delete Deployment Group
  x-api-slug: aws-codedeploy-api
  description: Deletes a deployment group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=DeleteDeploymentGroup
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiondeletedeploymentgroup-get-openapi.md
- name: AWS CodeDeploy API Deregister On Premises Instance
  x-api-slug: aws-codedeploy-api
  description: Deregisters an on-premises instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=DeregisterOnPremisesInstance
  tags: On Premises Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionderegisteronpremisesinstance-get-openapi.md
- name: AWS CodeDeploy API Get Application
  x-api-slug: aws-codedeploy-api
  description: Gets information about an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiongetapplication-get-openapi.md
- name: AWS CodeDeploy API Get Application Revision
  x-api-slug: aws-codedeploy-api
  description: Gets information about an application revision.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetApplicationRevision
  tags: Application Revisions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiongetapplicationrevision-get-openapi.md
- name: AWS CodeDeploy API Get Deployment
  x-api-slug: aws-codedeploy-api
  description: Gets information about a deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetDeployment
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiongetdeployment-get-openapi.md
- name: AWS CodeDeploy API Get Deployment Config
  x-api-slug: aws-codedeploy-api
  description: Gets information about a deployment configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetDeploymentConfig
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiongetdeploymentconfig-get-openapi.md
- name: AWS CodeDeploy API Get Deployment Group
  x-api-slug: aws-codedeploy-api
  description: Gets information about a deployment group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetDeploymentGroup
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiongetdeploymentgroup-get-openapi.md
- name: AWS CodeDeploy API Get Deployment Instance
  x-api-slug: aws-codedeploy-api
  description: Gets information about an instance as part of a deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetDeploymentInstance
  tags: Deployment Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiongetdeploymentinstance-get-openapi.md
- name: AWS CodeDeploy API Get On Premises Instance
  x-api-slug: aws-codedeploy-api
  description: Gets information about an on-premises instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetOnPremisesInstance
  tags: On Premises Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actiongetonpremisesinstance-get-openapi.md
- name: AWS CodeDeploy API List Application Revisions
  x-api-slug: aws-codedeploy-api
  description: Lists information about revisions for an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListApplicationRevisions
  tags: Application Revisions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionlistapplicationrevisions-get-openapi.md
- name: AWS CodeDeploy API List Applications
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the applications registered with the applicable IAM user or AWS
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListApplications
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionlistapplications-get-openapi.md
- name: AWS CodeDeploy API List Deployment Configs
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the deployment configurations with the applicable IAM user or AWS
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListDeploymentConfigs
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionlistdeploymentconfigs-get-openapi.md
- name: AWS CodeDeploy API List Deployment Groups
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the deployment groups for an application registered with the applicable IAM
                user or AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListDeploymentGroups
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionlistdeploymentgroups-get-openapi.md
- name: AWS CodeDeploy API List Deployment Instances
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the instance for a deployment associated with the applicable IAM user or AWS
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListDeploymentInstances
  tags: Deployment Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionlistdeploymentinstances-get-openapi.md
- name: AWS CodeDeploy API List Deployments
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the deployments in a deployment group for an application registered with the
                applicable IAM user or AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListDeployments
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionlistdeployments-get-openapi.md
- name: AWS CodeDeploy API List On Premises Instances
  x-api-slug: aws-codedeploy-api
  description: Gets a list of names for one or more on-premises instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListOnPremisesInstances
  tags: On Premises Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionlistonpremisesinstances-get-openapi.md
- name: AWS CodeDeploy API Register Application Revision
  x-api-slug: aws-codedeploy-api
  description: Registers with AWS CodeDeploy a revision for the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=RegisterApplicationRevision
  tags: Application Revisions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionregisterapplicationrevision-get-openapi.md
- name: AWS CodeDeploy API Register On Premises Instance
  x-api-slug: aws-codedeploy-api
  description: Registers an on-premises instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=RegisterOnPremisesInstance
  tags: On Premises Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionregisteronpremisesinstance-get-openapi.md
- name: AWS CodeDeploy API Remove Tags From On Premises Instances
  x-api-slug: aws-codedeploy-api
  description: Removes one or more tags from one or more on-premises instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=RemoveTagsFromOnPremisesInstances
  tags: On Premises Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionremovetagsfromonpremisesinstances-get-openapi.md
- name: AWS CodeDeploy API Stop Deployment
  x-api-slug: aws-codedeploy-api
  description: Attempts to stop an ongoing deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=StopDeployment
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionstopdeployment-get-openapi.md
- name: AWS CodeDeploy API Update Application
  x-api-slug: aws-codedeploy-api
  description: Changes the name of an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=UpdateApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionupdateapplication-get-openapi.md
- name: AWS CodeDeploy API Update Deployment Group
  x-api-slug: aws-codedeploy-api
  description: Changes information about a deployment group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=UpdateDeploymentGroup
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/actionupdatedeploymentgroup-get-openapi.md
- name: AWS CodeDeploy API
  x-api-slug: aws-codedeploy-api
  description: AWS CodeDeploy is a service that automates code deployments to any
    instance, including Amazon EC2 instances and instances running on-premises. AWS
    CodeDeploy makes it easier for you to rapidly release new features, helps you
    avoid downtime during application deployment, and handles the complexity of updating
    your applications. You can use AWS CodeDeploy to automate software deployments,
    eliminating the need for error-prone manual operations, and the service scales
    with your infrastructure so you can easily deploy to one instance or thousands.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: :///
  tags: AWS CodeDeploy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codedeploy/master/_listings/aws-codedeploy/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/codedeploy
- type: x-documentation
  url: http://docs.aws.amazon.com/codedeploy/latest/APIReference
- type: x-faq
  url: https://aws.amazon.com/codedeploy/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=179
- type: x-getting-started
  url: https://aws.amazon.com/codedeploy/getting-started/
- type: x-integrations
  url: https://aws.amazon.com/codedeploy/product-integrations/
- type: x-partners
  url: https://aws.amazon.com/solutions/partners/dev-ops/
- type: x-pricing
  url: https://aws.amazon.com/codedeploy/pricing/
- type: x-tutorials
  url: https://aws.amazon.com/codedeploy/developer-resources/#tutorials
- type: x-website
  url: https://aws.amazon.com/codedeploy/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---