# AWS-cloud-platform
DAY-1

Introduction to AWS
Cloud Computing is the delivery of IT services such as servers, storage, databases, networking, and software over the internet instead of running them on your own physical computers or data center. Organizations can access resources on demand and scale them as needed.

Simple Example

Instead of buying and maintaining a physical server for an application, you can rent computing resources from a cloud provider like Microsoft Azure, AWS, or Google Cloud Platform (GCP) and pay only for what you use.

Public Cloud

A Public Cloud is owned and managed by a third-party provider. Multiple customers share the same infrastructure securely over the internet. Examples include Azure, AWS, and GCP.

Advantages

✅ Low cost (Pay-as-you-go)
✅ Easy to scale up or down
✅ No hardware maintenance
✅ Quick deployment of applications

Examples of cloud providers
Microsoft Azure
Amazon Web Services (AWS)
Google Cloud Platform (GCP)
Private Cloud

A Private Cloud is dedicated to a single organization. The infrastructure is not shared with other companies and can be hosted in the organization's data center or by a dedicated provider.

Advantages

✅ More security and privacy
✅ Greater control over infrastructure
✅ Better for compliance and sensitive data
✅ Dedicated resources

Examples
Internal company data centers
VMware-based private cloud environments

**Why public cloud is popular**

Public cloud is popular because it is cost-effective, scalable, easy to use, and does not require organizations to purchase and maintain their own infrastructure. Cloud providers such as Azure, AWS, and GCP manage the infrastructure, allowing companies to focus on their applications and business needs

**Why AWS is more popular**

AWS is popular mainly because it was the first major public cloud provider and got a big head start over Azure and GCP. Many companies started their cloud journey with AWS and continue to use it today

AWS offers one of the largest sets of cloud services covering compute, storage, databases, networking, AI/ML, security, and more

AWS has largest market share

**DAY-2**

What is AWS IAM?

AWS IAM (Identity and Access Management) is a fundamental AWS service that allows you to securely manage access to your AWS resources. In simple terms, it handles Authentication (verifying who someone is) and Authorization (determining what they are allowed to do).

Key Components of IAM:

IAM Users: These are individual identities created for people or applications that need to interact with your AWS account. Each user gets its own set of credentials (password, access keys).

IAM Groups: A group is a collection of IAM users. Instead of assigning permissions to each user one by one, you can assign permissions to a group, and all users in that group inherit those permissions. This simplifies management for users with similar roles.

IAM Policies: Policies are JSON documents that define permissions—they specify what actions are allowed or denied on which AWS resources. You attach policies to users, groups, or roles to grant them specific access.

IAM Roles: A role is similar to a user, but it is not associated with a specific person. Instead, it is meant to be assumed by trusted entities, like AWS services (e.g., an EC2 instance) or users from another account, to securely perform actions on your behalf.

Why is IAM Important?

IAM provides centralized, fine-grained control over your AWS environment. By using IAM, you can implement the principle of least privilege—giving users and services only the permissions they need to do their job and nothing more. This significantly reduces the risk of unauthorized access and helps maintain a secure cloud environment.
sgggf
