# Static web hosting

The project contains CloudFormation scripts for static web hosting using CloudFront with a custom domain. The nested stacks also creates a CodePipeline to upload static content from `/src` to CloudFront and refresh teh cache. 