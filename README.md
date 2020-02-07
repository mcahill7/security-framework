# security-framework
Framework to deploy custom config rules as individual cloudformation stacks

## Pipeline
To create the pipeline run the following:
```
aws cloudformation create-stack --stack-name security-pipeline --template-body file://pipeline/pipeline.yaml --capabilities CAPABILITY_NAMED_IAM
```