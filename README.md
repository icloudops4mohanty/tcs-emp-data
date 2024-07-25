# aws-project ( n.vir )👍😎

### Step-1

create vpc

 - name = tcs-vpc
 - ip = 20.20.0.0/16
 - enable DNS hostname

create subnet

 - pub-sn-1
 - az = 1a
 - ip = 20.20.1.0/24

 - pub-sn-2
 - az = 1b
 - ip = 20.20.2.0/24

create internet gateway  and attach to vpc

create security group

 - name =  tcs-sg
 - all traffic --> anywhere

create route table

 - rename main route table as  =  tcs-pub-rt
 - mention subnets and attach internet gateway



# For Ubuntu use:

```sh
sudo su -
apt-get update
apt-get install mysql-client -y
```
	   
For python and related frameworks

```sh
apt-get install python3
apt-get install python3-flask -y
apt-get install python3-pymysql
apt-get install python3-boto3 -y
```

For running application

```sh
python3 EmpApp.py
```
