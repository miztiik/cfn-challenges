# Serverless Microservice on AWS Fargate Issues

## 🔥 Scenario

Mystique Unicorn App is a containerized microservice front end. Myztique Corp has decided to run this microservice in AWS Fargate to avoid maintaining serverless. This has allowed their developers to iterate faster and release new feature to the web service. The fast moving feature team is bysy building new functionality for the webservice, As of now, they have published their container image to docker hub and the image is available under this name `mystique/web-server:latest`.

The platform team has been engaged to create a cloudformation template to create the application stack. As of now, they have got template to accomplish the following,

1. Create a VPC with subnets to host the AWS Fargate Cluster
1. Create Cluster
1. Create Faragate Service along with Container Definition
1. Create Load Balancer to receive incoming traffic
1. Publish the `Web Service Url` in the Clouformation Outputs section.

When they access the `Web Service Url` from the browser, they are getting `403` errors. The team suspects that somewhere in the template they might have introduced some bugs. Since that team is lacking the necessary skills to troubleshoot this problem, You have been invited by the team to help them.

Oh, by the way, For some reason the container logs are not being sent to CloudWatch Logs. If you can fid that as well, it would be helpful for monitoring the health of the web service.

Can you help?

<sup>Give me a helping hand: Refer[1][1] [2][2] [3][3]</sup>

## 👋 Buy me a coffee

Buy me a coffee ☕ through [Ko-Fi](https://ko-fi.com/miztiik).

### 🏷️ Metadata

**Level**: 300

[1]: https://docs.aws.amazon.com/elasticloadbalancing/latest/network/target-group-health-checks.html
[2]: https://aws.amazon.com/premiumsupport/knowledge-center/elb-fix-failing-health-checks-alb/
[3]: https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-update-security-groups.html
