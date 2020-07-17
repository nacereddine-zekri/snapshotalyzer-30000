# snapshotalyzer-30000
Demo project to manage AWS EC2 instances snapshots

## ABOUT
This project is a demao, and uses boto3 to manage AWS EC2 instances snapshots;

## Configuring

shotty usses the configuration file created by AWS cli. e.g.

'aws confgure --profile shotty'

## Running

`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`
*command* is instances, volumes, or snapshots
*subcommand* -depends on command
*project* is optional
