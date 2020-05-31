# Serverless Microservice on AWS Fargate Issues

## 🔥 Scenario

Mystique Unicorn App is a containerized microservice front end. Mystique Corp has decided to run this microservice in AWS Fargate to avoid maintaining serverless. This has allowed their developers to iterate faster and release new feature to the web service. The fast moving feature team is busy building new functionality for the webservice, As of now, they have published their container image to docker hub and the image is available under this name `mystique/web-server:latest`.

The platform team has been engaged to create a cloudformation template to create the application stack. As of now, they have got template to accomplish the following,

1. Create a VPC with subnets to host the AWS Fargate Cluster
1. Create Cluster
1. Create Fargate Service along with Container Definition
1. Create Load Balancer to receive incoming traffic
1. Publish the `Web Service Url` in the Cloudformation Outputs section.

When they access the `Web Service Url` from the browser, they are getting `403` errors. The team suspects that somewhere in the template they might have introduced some bugs. Since that team is lacking the necessary skills to troubleshoot this problem, You have been invited by the team to help them.

Oh, by the way, For some reason the container logs are not being sent to CloudWatch Logs. If you can fid that as well, it would be helpful for monitoring the health of the web service.

Can you help?

<sup>Give me a helping hand: Refer [1][1] [2][2] [3][3]</sup>

## 📌 Who is using this

This repository to teaches cloudformation to new developers, Solution Architects & Ops Engineers in AWS. Based on that knowledge these Udemy [course #1][103], [course #2][102] helps you build complete architecture in AWS.

### 💡 Help/Suggestions or 🐛 Bugs

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional documentation or solutions, we greatly value feedback and contributions from our community. [Start here][200]

### 👋 Buy me a coffee

Buy me a [coffee ☕][900].

### 🏷️ Metadata

**Level**: 400

[1]: <https://docs.aws.amazon.com/elasticloadbalancing/latest/network/target-group-health-checks.html>
[2]: <https://aws.amazon.com/premiumsupport/knowledge-center/elb-fix-failing-health-checks-alb/>
[3]: <https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-update-security-groups.html>

[100]: https://www.udemy.com/course/aws-cloud-security/?referralCode=B7F1B6C78B45ADAF77A9

[101]: https://www.udemy.com/course/aws-cloud-security-proactive-way/?referralCode=71DC542AD4481309A441

[102]: https://www.udemy.com/course/aws-cloud-development-kit-from-beginner-to-professional/?referralCode=E15D7FB64E417C547579

[103]: https://www.udemy.com/course/aws-cloudformation-basics?referralCode=93AD3B1530BC871093D6

[200]: https://github.com/miztiik/cfn-challenges/issues

[899]: https://www.udemy.com/user/n-kumar/

[900]: https://ko-fi.com/miztiik
