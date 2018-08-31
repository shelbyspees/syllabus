# SRE Syllabus

## CD/CI
concepts:
- automation/scripting
- build
- deploy

tools:
- git
- jenkins
- travis
- make
- bash
- go ([Learn Go by writing tests](https://dev.to/quii/learn-go-by-writing-tests-structs-methods-interfaces--table-driven-tests-1p01))

## Networking
- ports
- port binding ([12-factor: Port binding](https://12factor.net/port-binding))
- nodes
- ssh
- dns
- http
- proxies
- IPv4
- IPv6
- OSI model
- TCP/IP model
- DDoS
- router
- packet

## Databases
concepts:
- SQL
- joins
- users
- privileges
- clusters
- running jobs
- backups

- mysql
- postgresql

## Linux Systems Administration
- vim
- acl/permissions
- logs: `/var/log`
- processes
- concurrency

Learning resources:
- [chassing/linux-sysadmin-interview-questions](https://github.com/chassing/linux-sysadmin-interview-questions/blob/master/README.md#devop)
- [ ] [Applying the Unix Process Model to Web Apps](https://adam.herokuapp.com/past/2011/5/9/applying_the_unix_process_model_to_web_apps/)

commands:
* tee
* awk
* tr
* cut
* tac
* curl
* wget
* watch
* head
* tail
* fsck

## Encryption and Security
- gpg
- ssh
- sha
- https/ssl
- DoS attack

## Monitoring and Benchmarking
- logs
- metrics
- alerts

tools:
- datadog
- cloudwatch
- pingdom
- app logfiles (`{approot}/shared/log`)
- server logfiles

## Infrastructure as Code
- chef
- ansible
- terraform

## Cloud Infrastructure
- autoscaling
- load balancers
- nodes

## AWS
concepts:
- security groups
- IAM permissions

services:
- ec2
- s3
- redshift
- dynamodb
- sns
- sqs
- emr

