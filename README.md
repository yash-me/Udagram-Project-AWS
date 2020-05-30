# udacity-devops-udagram-project

## Run the following commands to create the full stack:

```
./create.sh networking-stack networking.yaml networking-parameters.json  
./create.sh servers-stack servers.yaml servers-parameters.json  
```

* The bucket is already created, and the IAM role for the EC2 instances allows it to download (using aws cli) the udagram.zip file and unzip it at /var/www/html location 

* The application URL will be an output of the servers-stack
