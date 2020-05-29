# CloudFormation Challenges

Learn AWS CloudFormation with these fun challenges to solve. This will help you understand the basics of cloudformation and how to combine multiple AWS services to create an applciation stack

These are multiple puzzles in the directory. There are some defects or missing functionality introduced in each of these templates deliberately. Your task is find them and fix them to achieve the desired functionality. The difficulty level varies from _Simple, Medium and Complex_

After you figured out the solution, dont forget to send us a pull request with your solution.

1. ## 🧰 Prerequisites

    - 🛠 AWS CLI Installed & Configured - [Get help here](https://youtu.be/TPyyfmQte0U)
    - 🛠 AWS CloudFormation Knowledge - [Get help here](https://www.udemy.com/course/draft/3110838/?referralCode=93AD3B1530BC871093D6)

1. ## 🚀 Deploy AWS CloudFormation Tempalte

    Here is a sample CLI command to deploy the template. Make your you have downloaded the template `parameterize_ddb.json` and run this command from the same directory.

    **NOTE**: These templates have been tested in `us-east-1` region. It is highly recommended to try them out them in the same region.

    ```bash
    # Configure AWS CLI
    aws configure

    # Deploy the template
    aws cloudformation create-stack \
        --stack-name "miztiik-automation-clouformation-challenge-puzzles" \
        --template-body file://REPLACE-WITH-TEMPLATE-FILE-NAME \
        --capabilities CAPABILITY_IAM
    ```

1. ## 🔬 Solving the puzzle

    Depending upon the puzzle, you may have to do one or some of these tasks to solve them.

    - Check if, _ALL_ resources that are required are deployed.
    - Check if, _ALL_ attributes for resources have been set correctly.
        - For example, Check if S3 bucket is having `versioning` or `encryption` etc.,
    - Check if the resources are communicating with each other,
        - For example, Is the Webserver accessible from public IP?

    Good Luck

1. ## 🧹 CleanUp

    *You* are responsible for the resources being created by any of the templates in this repository. You are encouraged to destroy all the resources after their purpose has been met. One of the way to clean up the resources is to execute the below command to delete the stack, or _you can delete the stack from console as well_

    ```bash
    aws cloudformation delete-stack \
        --stack-name "miztiik-automation-clouformation-challenge-puzzles"
    ```

    This is not an exhaustive list, please carry out other necessary steps as maybe applicable to your needs.

## Who is using this

A number of organisations are using gamification to enhance their team skills. This Udemy [course][100] uses this repository extensively to teach cloudformation to new beginners in AWS.

### 💡 Help/Suggestions or 🐛 Bugs

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional documentation or solutions, we greatly value feedback and contributions from our community. [Start here][200]

### 👋 Buy me a coffee

Buy me a coffee ☕ through [Ko-Fi](https://ko-fi.com/miztiik).

### 🏷️ Metadata

**Level**: 200

[1]: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-s3-bucket.html#cfn-s3-bucket-accesscontrol

[100]: https://www.udemy.com/course/aws-cloud-development-kit-from-beginner-to-professional/?referralCode=E15D7FB64E417C547579

[200]: https://github.com/miztiik/cfn-challenges/issues
