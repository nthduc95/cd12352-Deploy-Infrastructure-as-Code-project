# CD12352 - Infrastructure as Code Project Solution
Endpoint URL: 
http://udagr-webap-mdddq961w959-530597814.us-east-1.elb.amazonaws.com/

## Spin up instructions
Create script:
./create.sh udagram-web-app-stack udagram.yml udagram-parameters.json
./create.sh udagram-network-stack network.yml network-parameters.json

## Tear down instructions
Delete script:
./delete.sh udagram-web-app-stack udagram.yml udagram-parameters.json
./delete.sh udagram-network-stack network.yml network-parameters.json
