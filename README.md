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
        --template-body file://parameterize_ddb.json \
        --capabilities CAPABILITY_IAM
    ```

1. ## 🔬 Solving the puzzle

    Depending upon the puzzle, you may have to do one or some of these tasks to solve them.

    - Check if, _ALL_ resources that are required are deployed.
    - Check if, _ALL_ attributes for resources have been set correctly.
        - For examples, Check if S3 bucket is having `versioning` or `encryption` etc.,
    - Check if the resources are communicating with each other,
        - For example, Is the Webserver accessible from public IP?

    Good Luck

1. ## 🧹 CleanUp

    If you want to destroy all the resources created by the stack, Execute the below command to delete the stack, or _you can delete the stack from console as well_

    ```bash
    aws cloudformation delete-stack \
        --stack-name "miztiik-automation-clouformation-challenge-puzzles"
    ```

    This is not an exhaustive list, please carry out other necessary steps as maybe applicable to your needs.

## 👋 Buy me a coffee

[Buy me](https://paypal.me/valaxy) a coffee ☕, _or_ You can reach out to get more details through [here](https://youtube.com/c/valaxytechnologies/about).

### 💡 Help/Suggestions or 🐛 Bugs

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional documentation or solutions, we greatly value feedback and contributions from our community.

- [Github Issues](https://github.com/miztiik/cfn-challenges/issues)
