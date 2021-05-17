Building a complete Python installation requires the use of various additional third-party libraries, depending on your build platform and configure options. Not all standard library modules are buildable or useable on all platforms. Refer to the Install dependencies section of the Developer Guide for current detailed information on dependencies for various Linux distributions and macOS.

### Features

- asfasdf 
- dsfgdfsg
- dsfgdsfg
- dsfgjsdfg
- sdfgsdfg

### installing terraform

https://www.terraform.io/downloads.html

### How to configure

open and edit the following file

```sh

# vim terraform.tfvars

region = ""
access_key = ""
secret_key = ""
project = "myapp.blog.com"
vpc_cidr = ""

```
### how to use

```sh
$  git clone https://github.com/FujiClado/terraform-vpc.git
$  cd terraform-vpc
$ terraform init
$ terraform plan
$ terraform apply
```
