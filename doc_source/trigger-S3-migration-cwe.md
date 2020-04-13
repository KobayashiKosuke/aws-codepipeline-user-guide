# Update Polling Pipelines to the Recommended Change Detection Method<a name="trigger-S3-migration-cwe"></a>

If you have a pipeline that uses polling to react to source changes, you can update it to use the recommended detection method \(webhooks for pipelines with a GitHub source and Amazon CloudWatch Events for pipelines with a CodeCommit or Amazon S3 source\)\.


| How to Migrate Pipelines to the Recommended Change Detection Method | Source | Recommended Detection Method | Console | CLI | AWS CloudFormation | 
| --- | --- | --- | --- | --- | --- | 
| Amazon S3 | Amazon CloudWatch Events \(recommended\) and an AWS CloudTrail trail\.  | See [Update Pipelines for Push Events \(CodeCommit or Amazon S3 Source\) \(Console\)](update-change-detection.md#update-change-detection-console-codecommit-S3)\. | See [Update Pipelines for Push Events \(Amazon S3 Source\) \(CLI\)](update-change-detection.md#update-change-detection-cli-S3)\. | See [Update Pipelines for Push Events \(Amazon S3 Source\) \(AWS CloudFormation Template\)](update-change-detection.md#update-change-detection-cfn-s3)\. | 
| AWS CodeCommit | Amazon CloudWatch Events \(recommended\)\. | See [Update Pipelines for Push Events \(CodeCommit or Amazon S3 Source\) \(Console\)](update-change-detection.md#update-change-detection-console-codecommit-S3)\. | See [Update Pipelines for Push Events \(CodeCommit Source\) \(CLI\)](update-change-detection.md#update-change-detection-cli-codecommit)\. | See [Update Pipelines for Push Events \(CodeCommit Source\) \(AWS CloudFormation Template\)](update-change-detection.md#update-change-detection-cfn-codecommit)\. | 
| GitHub | Webhooks \(recommended\)\.[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/codepipeline/latest/userguide/trigger-S3-migration-cwe.html) | See [Update Pipelines for Push Events \(GitHub Source\) \(Console\)](update-change-detection.md#update-change-detection-console-github)\. | See [Update Pipelines for Push Events \(GitHub Source\) \(CLI\)](update-change-detection.md#update-change-detection-cli-github)\. | See [Update Pipelines for Push Events \(GitHub Source\) \(AWS CloudFormation Template\)](update-change-detection.md#update-change-detection-cfn-github)\. | 