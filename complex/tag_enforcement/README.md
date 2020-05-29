# EC2 Instance Tag Compliance Enforcement

## 🔥 Scenario

The recently formed Mystique Unicorn App Security Board had become very active. The latest intiatives from them is to ensure all volumes are tagged. This would allow them to run automatic scans - To find `unused-volumes`, `unencrypted-volumes` etc. These automatic scans are approved by the board to power-off any instance with an _untagged_ volume. The security automation is configured to be event driven: On every EC2 Instance creation event, the tagging for the new instance volumes are checked.

To comply with this mandate, The application teams have been asked to ensure all their instances and the volumes attached to those instances are tagged appropriately. This includes tagging the EC2 root volumes as well during the boot sequence. The application team is not well versed with infrastructure especially with AWS CloudFormation. They are currently having this template as their base, This template accomplishes the following.

- Using parameters, get the SSH KeyName from the user
- Get the Instance Size
- Get the Availability Zone from the user. The template **assumes** there is a default VPC in the region. If not the user is expected to create one and then run the template.

Can you help them?. This template when completed, should tag the EC2 root volumes. For testing use any _tag-key_ and _tag-value_.

<sup>Give me a helping hand: [Refer][1]</sup>

## Who is using this

A number of organisations are using gamification to enhance their team skills. This Udemy [course][100] uses this repository extensively to teach cloudformation to new beginners in AWS.

### 💡 Help/Suggestions or 🐛 Bugs

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional documentation or solutions, we greatly value feedback and contributions from our community. [Start here][200]

### 👋 Buy me a coffee

Buy me a coffee ☕ through [Ko-Fi](https://ko-fi.com/miztiik).

### 🏷️ Metadata

**Level**: 300

[1]: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html

[100]: https://www.udemy.com/course/aws-cloud-development-kit-from-beginner-to-professional/?referralCode=E15D7FB64E417C547579

[200]: https://github.com/miztiik/cfn-challenges/issues
