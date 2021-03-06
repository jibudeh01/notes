# Third Pillar - Reliability

- Ability of a system to recover from infrastructure or service disruptions, dynamically acquire computing resources to meet demand, and mitigate disruptions such as misconfigurations or transient network issues
- Design principles
    - **Test recovery procedures** - Use automation to simulate different failures or to recreate scenarios that led to failures before
    - **Automatically recover from failure** - Anticipate and remediate failures before they occur
    - **Scale horizontally to increase aggregate system availability** - Distribute requests accross multiple, smaller resources to ensure that they don't share a common point of failure
    - **Stop guessing capacity** - Maintain the optimal level to satisft demand without over under provisioning - Use auto scaling
    - **Manage change in automation** - Use automation to make changes to infrastructure
- AWS Services
    - Foundations
        - IAM
        - Amazon VPC
        - Service Limits
        - AWS Trusted Advisor
    - Change Management
        - AWS Auto Scaling
        - Amazon CloudWatch
        - AWS CloudTrail
        - AWS Config
    - Failure Management
        - Backups
        - AWS CLoudFormation
        - Amazon S3
        - Amazon S3 Glacier
        - Amazon Route 53