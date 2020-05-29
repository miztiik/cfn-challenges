# High Performance Parameter Store

## 🔥 Scenario

As part of the Mystique Unicorn App Standards Specification, All hard coded values from the application configuration is being moved
to AWS SSM Parameter Store. Some characteristics that makes this migration complex is listed below,

- It is to be noted that the application has more `20000` parameters and the maximum could be around `50000` parameters
- The size of the parameters range from `6KB` to `8KB`

The application team has began the migration and the given template snippet is being used to create the parameters. The template is created when a _dummy value_ on creation. When the team is trying to store the _actual parameter_(refer sample file contents) they are getting errors.

Can you help them by providing them with a template that will meet their requirements?

<cite>Hint: Use the GUI and [Refer][1]</cite>

## Who is using this

A number of organisations are using gamification to enhance their team skills. This Udemy [course][100] uses this repository extensively to teach cloudformation to new beginners in AWS.

### 💡 Help/Suggestions or 🐛 Bugs

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional documentation or solutions, we greatly value feedback and contributions from our community. [Start here][200]

### 👋 Buy me a coffee

Buy me a coffee ☕ through [Ko-Fi](https://ko-fi.com/miztiik).

### 🏷️ Metadata

**Level**: 300

[1]: https://docs.aws.amazon.com/systems-manager/latest/userguide/parameter-store-advanced-parameters.html

[100]: https://www.udemy.com/course/aws-cloud-development-kit-from-beginner-to-professional/?referralCode=E15D7FB64E417C547579&couponCode=AWS_4U_MAY

[200]: https://github.com/miztiik/cfn-challenges/issues
