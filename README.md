# 3-stage-webserver-pipeline-repo

CI/CD pipeline for multi-region (us-east-1/N.Virginia and us-west-1/N.California) deployment with AWS CodePipeline

Building three-stage pipeline to deploy web application with CloudFormation template.
- Variant 1: Using AWS CodeCommit and AWS CodePipeline.
- Variant 2: Using GitHub and AWS CodePipeline.

Used cfn-lint tool to test the template on the build stage.

# Diagrams:

Variant 1: Source stage - AWS CodeCommit
![](images/diagram.drawio.png)

Variant 2: Source stage - GitHub
![](images/diagram-1.drawio.png)