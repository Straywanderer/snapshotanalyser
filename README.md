# Snapshotanalyser
My EC2 snapshot analyser


## About
This project is  a demo and uses boto3 to manage AWS EC2 instance snapshots.

##Configuring

Shotty uses the configuration file created by the AWS cli. e.g

`aws configure --profile shotty`

## Running

`pipenv run "python shotty/shotty.py"`

*command* is list, start or stop
*project* is optional
