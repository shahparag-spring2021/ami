# Packer

Create a buildAmi.sh shell script with the below code - 
```
packer build \
    -var 'aws_access_key=' \
    -var 'aws_secret_key=' \
    -var 'aws_region=us-east-1' \
    -var 'subnet_id=' \
    -var 'source_ami=ami-03d315ad33b9d49c4' \
    -var 'prod_account_id=' \
    ami.json
```
Supply the necessary user variables in this shell script
Running the .sh script - ./buildAmi.sh

Checking actions
<!-- A6 demo -->