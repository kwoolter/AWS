# AWS
Stuff for setting up VMs on AWS


# Logging onto server
Had to fire up Git Bash and run 
chmod 400 kwoolter.pem
to set permissions of the file

'ssh -i "kwoolter.pem" ec2-user@ec2-3-14-65-164.us-east-2.compute.amazonaws.com'

OR use putty...

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html?icmpid=docs_ec2_console

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-ug.pdf#putty

# Installing stuff

`sudo yum install python3`

`python3 -m pip install --user virtualenv`
`virtualenv myvenv`
`source myvenv\bin\activate`
`pip install numpy` etc


`sudo yum install git`



