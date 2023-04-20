Commands used for deploying an S3 template
Command to deploy:
    aws cloudformation deploy --template-file s3-template.yaml --stack-name labymi
Command to describe stack:
    aws cloudformation describe-stack-events --stack name labymi
 Command to Update stack:   
    aws cloudformation update-stack --stack-name my-stack --template-body file://my-updated-template.yaml
Command to delete:
    aws cloudformation delete-stack --stack-name my-stack

![S3 bucket](https://user-images.githubusercontent.com/116459374/233243439-77400950-7f9e-4555-9a0e-03eae0e3eab6.PNG)

![Cloudformation Screenshots](https://user-images.githubusercontent.com/116459374/233243889-69f85012-fc6d-474f-936d-c04673fb5975.PNG)