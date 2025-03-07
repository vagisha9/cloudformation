# CD12352 - Infrastructure as Code Project Solution
# [Vagisha Barwal]

## Spin up instructions
./create.sh networkinfra network.yml network-parameters.json
./create.sh udagraminfra udagram.yml udagram-parameters.json

## Tear down instructions
./delete.sh networkinfra
./delete.sh udagraminfra

## Other considerations
Load Balancer URL: http://udagra-webap-aagztmc4hhwu-874612842.us-east-1.elb.amazonaws.com/

S3 static content URL: http://udacityinfra-bucket-1012.s3-website-us-east-1.amazonaws.com