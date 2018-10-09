## Zumper Infrastructure Engineer Interview

This interview is going to test your knowledge and understanding of Amazon Web
Services, Linux and other basic networking services and policies.

Over the course of three hours, we'll have you work in a nearly-fresh AWS
account, setting up EC2 servers, Route53 DNS records, ELB load balancers and
RDS databases to setup and run a standard Open Source software package.

### Requirements

#### Access and Authentication
- Setup an EC2 instance running Ubuntu Linux.
- Configure SSH public-key access to the server to include your own account
and accounts for the users `dan` and `mike`
- Configure password-less sudo access for your account and the `dan` and `mike`
users
- Disable the default, `ubuntu` account's login capabilities.

#### Web Application
- Install and configure MediaWiki on the EC2 instance.
- Setup a MySQL Aurora RDS database to store MediaWiki's data.
- Configure access to MediaWiki at https://wiki.interview.zumper.com
- Configure access to MediaWiki for your user account as well as `dan` and
`mike`.
