# Configuration For AWS

## AMI Configuration
These scripts are run as bootstrap script to customize the environment for use by the data science containers. 

* `bootstrap_awslinux_ami`: customize AWS Linux AMI
* `bootstrap_deeplearning_ami`: customize AWS Deep Learning AMI

## FoxyProxy Config File 
Required to support dynamic port forwarding to AWS.  This allows browser accessing containers through the ec2 instance public internet interface.  Currently working with Chrome Browser.

Use of FoxyProxy is modelled after [AWS's use of FoxyProxy to support access to EMR clusters](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-connect-master-node-proxy.html).
