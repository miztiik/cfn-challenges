# Unicorn App Store Order Queue Failtuers

## 🔥 Scenario

Mystique Unicorn App is getting very popular. During peak times the app receives 1.2Million orders per day. All these orders are passed onto the backend systems for downstream processing using AWS SQS FIFO Queues. The application team wants to setup alarms if the queue depth is increasing beyond a certain limit. They like to receive an email when ever the alarm is triggered.

With the current template, they are unable to get it working. The alarm is not being sent, and they are getting notifications at other times. They **key** focus to get the alarm when the queue depth is at the **maximum**(>4500 messages in over 5 minutes).

Can you help them by providing them with a template that will meet their requirements?

_There are atleast 3 fixes to be made. Good Luck_

### Optional

The application team is also interested in setting up another alarm that will let them know, how long it takes for the down stream processors are taking to finish the workload. How much backpressure is getting built because of that. Can you help with that?

<cite>Hint: [Refer][1]</cite>

## 📌 Who is using this

This repository to teaches cloudformation to new developers, Solution Architects & Ops Engineers in AWS. Based on that knowledge these Udemy [course #1][103], [course #2][102] helps you build complete architecture in AWS.

### 💡 Help/Suggestions or 🐛 Bugs

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional documentation or solutions, we greatly value feedback and contributions from our community. [Start here][200]

### 👋 Buy me a coffee

Buy me a [coffee ☕][900].

### 🏷️ Metadata

**Level**: 300

[1]: https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-available-cloudwatch-metrics.html

[100]: https://www.udemy.com/course/aws-cloud-security/?referralCode=B7F1B6C78B45ADAF77A9

[101]: https://www.udemy.com/course/aws-cloud-security-proactive-way/?referralCode=71DC542AD4481309A441

[102]: https://www.udemy.com/course/aws-cloud-development-kit-from-beginner-to-professional/?referralCode=E15D7FB64E417C547579

[103]: https://www.udemy.com/course/aws-cloudformation-basics?referralCode=93AD3B1530BC871093D6

[200]: https://github.com/miztiik/cfn-challenges/issues

[899]: https://www.udemy.com/user/n-kumar/

[900]: https://ko-fi.com/miztiik
