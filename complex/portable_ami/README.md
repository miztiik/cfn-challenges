# Multi-Region Portability

## 🔥 Scenario

Mystique Unicorn App is using lot of EC2 instances all across the world to support their customers. They recently found out updating the templates with the latest version of AMI ID is proving to be quite cumbersome. Currently the template they are using has the AMI values hardcoded.

The team has the following objectives to reduce their operational overhead:

1. The templates should be portable - One template for ALL regions
1. They do NOT want to use `mappings` as that is also another way of hard-coding
1. They wanted to use the latest version of the base AMI offered by the vendors, instead of maintaining custom images
1. They are currently using two different OS flavors: _Amazon Linux 2_ and _Windows_

One of their Ops Engineers, after watching a [Miztiik demo][1] in youtube came up an idea of replacing the hard-coded values in the templates. If you were the Ops Engineer, how would you proceed?

<sup>Give me a helping hand: [Refer][2]</sup>

## Who is using this

A number of organisations are using gamification to enhance their team skills. This Udemy [course][100] uses this repository extensively to teach cloudformation to new beginners in AWS.

### 💡 Help/Suggestions or 🐛 Bugs

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional documentation or solutions, we greatly value feedback and contributions from our community. [Start here][200]

### 👋 Buy me a coffee

Buy me a coffee ☕ through [Ko-Fi](https://ko-fi.com/miztiik).

### 🏷️ Metadata

**Level**: 300

[1]: https://www.youtube.com/channel/UC_evcfxhjjui5hChhLE08tQ/search?query=ami
[2]: https://aws.amazon.com/blogs/mt/query-for-the-latest-windows-ami-using-systems-manager-parameter-store/

[100]: https://www.udemy.com/course/aws-cloud-development-kit-from-beginner-to-professional/?referralCode=E15D7FB64E417C547579

[200]: https://github.com/miztiik/cfn-challenges/issues
