# glue-athena-s3

Based on [this](https://aws.amazon.com/blogs/big-data/build-a-data-lake-foundation-with-aws-glue-and-amazon-s3/) post and the sample [here](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-glue-crawler.html)

## deploy

aws cloudformation create-stack --stack-name g \
--template-body file://gas.yml \
--capabilities CAPABILITY_IAM

## Notes

To build a glue role instead of using AWSGlueServiceRoleDefault - see [here](https://docs.aws.amazon.com/glue/latest/dg/getting-started-access.html)