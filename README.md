# AWS-Project-2

Re- Architect Services for AWS Cloud

AWS Services used:
1. Beanstalk :- VM for tomcat (app server), nginx lb replacement, Automation for VM Scaling
2. S3 :- Storage
3. RDS :- Database
4. Elastcache :- Using in place of Memcache
5. ActiveMQ :- Using in place of RabbitMQ
6. Route 53 :- DNS
7. CloudFront :- Content Delivery Network


STEPS TAKEN:-
- -> Log to aws account
- -> Create key-pair for beanstalk instance login
- -> Create security group for Elasticache, RDS, ActiveMQ
- -> Create:
   - RDS
   - Amazon Elastic Cache
   - Amazon Active MQ
- -> Create Elastic Beanstalk Environment
- -> Update SG of the backend to allow traffic from Bean SG
- -> Update SG of the backend to allow internal traffic
- -> Launch EC2 instance for DB initialization
- -> Login to the instance and initialize RDS DB
- -> Change healthcheck on beanstalk to /login
- -> Add 443 https Listener to ELB
- -> Build Artifact with Backend Information
- -> Deploy Artifact to Beanstalk
- -> Create CDN with sl cert
- -> Update Entry in GoDaddy DNS Zones
- -> Test the URL




















