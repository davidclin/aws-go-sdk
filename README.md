# aws-go-sdk
AWS SDK for Go Cheatsheet

## Create Virtualenv
<pre>
$ virtualenv go
$ source go/bin/activate 
</pre>

## Installing Go
<pre>
1) Download Go Tarball
   $ wget https://dl.google.com/go/go1.12.4.linux-amd64.tar.gz

2) Untar
   $ sudo tar -C /usr/local -xzf go1.12.4.linux-amd64.tar.gz

3) Set PATH
   $ vim /etc/profile
     export PATH=$PATH:/usr/local/go/bin    <--- Add below the pathmunge() function

4) Logout and log back into instance to verify PATH was added
   $ echo $PATH
</pre>

## Installing AWS SDK for Go
<pre>
1) $ cd go

2) $ go get -u github.com/aws/aws-sdk-go/...     (Wait a minute or so)
</pre>

## Install AWS SDK for Go Depencency
<pre>
1) Create directory named 'jessevdk' in /home/ec2-user/go/src/github.com/

2) $ git clone https://github.com/jessevdk/go-flags.git
</pre>

## RESOURCES
Download Go		: https://golang.org/dl/ <p>
Install  Go		: https://golang.org/doc/install  <p>
Install AWS SDK for Go	: https://docs.aws.amazon.com/sdk-for-go/v1/developer-guide/setting-up.html  <p>

