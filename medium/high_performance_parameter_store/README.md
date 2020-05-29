# High Performance Parameter Store

## 🔥 Scenario

As part of the Mystique Unicorn App Standards Specification, All hard coded values from the application configuration is being moved
to AWS SSM Parameter Store. Some characteristics that makes this migration complex is listed below,

- It is to be noted that the application has more `20000` parameters and the maximum could be around `50000` parameters
- The size of the parameters range from `6KB` to `8KB`

The application team has began the migration and the given template snippet is being used to create the parameters. The template is created when a _dummy value_ on creation. When the team is trying to store the _actual parameter_(refer sample file contents) they are getting errors.

Can you help them by providing them with a template that will meet their requirements?

<cite>Hint: Use the GUI and [Refer][1]</cite>

## 📌 Who is using this

This repository to teaches cloudformation to new developers, Solution Architects & Ops Engineers in AWS. Based on that knowledge these Udemy [course #1][103], [course #2][102] helps you build complete architecture in AWS.

### 💡 Help/Suggestions or 🐛 Bugs

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional documentation or solutions, we greatly value feedback and contributions from our community. [Start here][200]

### 👋 Buy me a coffee

Buy me a [coffee ☕][900].

### 🏷️ Metadata

**Level**: 300

[1]: https://docs.aws.amazon.com/systems-manager/latest/userguide/parameter-store-advanced-parameters.html

[100]: https://www.udemy.com/course/aws-cloud-security/?referralCode=B7F1B6C78B45ADAF77A9

[101]: https://www.udemy.com/course/aws-cloud-security-proactive-way/?referralCode=71DC542AD4481309A441

[102]: https://www.udemy.com/course/aws-cloud-development-kit-from-beginner-to-professional/?referralCode=E15D7FB64E417C547579

[103]: https://www.udemy.com/course/aws-cloudformation-basics?referralCode=93AD3B1530BC871093D6

[200]: https://github.com/miztiik/cfn-challenges/issues

[899]: https://www.udemy.com/user/n-kumar/

[900]: https://ko-fi.com/miztiik
