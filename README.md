# setnget-config

## ssh to the EC2 instance

`ssh -i <path to .pem file> ec2-user@<ec2-machine-name>`

## Download and install Java

`wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie" https://download.oracle.com/otn-pub/java/jdk/14.0.2+12/205943a0976c4ed48cb16f1043c5c647/jdk-14.0.2_linux-x64_bin.rpm`

then run

`yum install jdk-14.0.2_linux-x64_bin.rpm`
