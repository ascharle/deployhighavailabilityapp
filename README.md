
![udacity project](https://github.com/ascharle/deployhighavailabilityapp/assets/17343915/3e6e412a-daaa-442d-bd76-49a570ffa360)

This project deploys web servers for a highly available web app using CloudFormation. It creates and deploys the infrastructure and application for an Instagram-like app from the ground up. Deployment begins with the networking components, followed by servers, security roles and software. The application code is deployed from the S3 bucket using appropriate role.

Description Create a Launch Configuration in order to deploy four servers, two located in each of your private subnets. The launch configuration will be used by an auto-scaling group. You'll need two vCPUs and at least 4GB of RAM. The Operating System to be used is Ubuntu 18. So, choose an Instance size and Machine Image (AMI) that best fits this spec. Be sure to allocate at least 10GB of disk space so that you don't run into issues.

Files included: network.yaml - CloudFormation network infrastructure stack description. network_parameters.json - Parameters file for the network infrastructure stack server.yaml - CloudFormation services infrastructure stack description server_parameters.json - Parameters file for the services infrastructure stack create_network.sh - bash script for managing network infrastructure stack create_servers.sh - bash script for managing services infrastructure stack infrastructure-diagram.png - infrastructure diagram


* /Images-of-result-deploy : Screenshot the result of deploy.

* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* destroy.sh : Cloudformation delete stack script.
* udagram.yml : Udagram Project's CloudFormation script.
* udagram-parameters.json : Udagram Project's CloudFormation script parameters.
