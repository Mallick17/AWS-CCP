# AWS-Services
## AWS Acceptable Use Policy
- _**Security, Compliance, Data Protection, and Intellectual Property**_
- The AWS Acceptable Use Policy (AUP) outlines the key areas that users must comply with when using AWS services. These areas include security, where AWS stipulates that users cannot carry out any actions that can compromise the security of AWS services or other users. Compliance refers to adhering to all applicable laws and regulations while using AWS services. Data protection means ensuring the privacy and security of personal data stored or processed on AWS. Intellectual property involves respecting the rights of others and not using AWS services to infringe upon these rights, such as copyrights, trademarks, or patents. In essence, the AUP guides AWS users on how to use the services responsibly and legally.

---

## "6 R's" Migration Strategy for Migrating Applications to AWS Cloud
> **Refactor, Rehost, Repurchase, Retain, Retire, and Rebuild**
- The "6 R's" migration strategy in AWS refers to six approaches for migrating applications to the cloud: Rehost (lift and shift), Replatform (lift, tinker, and shift), Repurchase (drop and shop), Refactor (re-architect), Retire, and Retain. Each R represents a different method tailored to specific application needs and goals during migration.
  - **_Rehost_**: Also known as "lift and shift," this approach involves moving applications to the cloud without making any significant changes to their architecture. It's often the quickest and simplest method, suitable for applications that don't require significant modifications and need to be migrated rapidly. Rehosting reduces the time and effort required for migration, making it a preferred choice for many organizations.
  - **_Replatform:_** Also known as "lift, tinker, and shift," this approach involves making some adjustments to the application architecture to optimize it for the cloud environment. While not as extensive as refactoring, replatforming may involve updating the operating system, middleware, or database to versions compatible with the cloud. It allows for better performance, scalability, and cost optimization compared to rehosting, without requiring a complete overhaul of the application.
  - **_Repurchase:_** Also known as "drop and shop," this approach involves replacing an existing application with a similar one available as a service. For example, instead of hosting an email server on-premises, an organization might choose to use a cloud-based email service like Amazon WorkMail. Repurchasing can provide benefits such as reduced maintenance overhead, increased scalability, and access to advanced features offered by cloud services.
  - **_Refactor:_** Also known as "re-architect," this approach involves redesigning and restructuring the application to take full advantage of cloud-native features and capabilities. It often leads to improved performance, scalability, and cost efficiency compared to traditional on-premises deployments. Refactoring may involve breaking monolithic applications into microservices, adopting serverless architectures, or using managed services provided by the cloud provider.
  - **_Retire:_** This involves decommissioning applications or services that are no longer needed or relevant. It helps streamline the migration process by reducing complexity and eliminating unnecessary resources and costs. Retiring legacy applications frees up resources that can be allocated to more critical workloads or initiatives.
  - **_Retain:_** This approach involves keeping certain applications or components on-premises due to regulatory requirements, performance considerations, or other constraints. It allows organizations to maintain hybrid environments and gradually migrate workloads to the cloud at their own pace, ensuring minimal disruption to operations.
> These six approaches offer a comprehensive strategy for migrating applications to the AWS Cloud, enabling organizations to optimize performance, scalability, and cost efficiency while minimizing disruption and risk.

---

## AWS Compute Optimizer
- AWS Compute Optimizer analyzes the utilization of your AWS compute resources. Based on its findings, it generates recommendations for your resources to reduce cost and improve performance.
- AWS Compute Optimizer uses machine learning to analyze historical utilization metrics and configuration data for your AWS resources, offering recommendations on how to optimize compute resources across Amazon EC2 instances, Amazon EBS volumes, and AWS Lambda functions. For EC2 instances, it provides recommendations on changing instance types or sizes to match your workload requirements more closely, potentially leading to cost savings and performance improvements. This tool is particularly useful for identifying rightsizing opportunities by suggesting configurations that could deliver the same or better performance at a lower cost.

## Amazon Elastic Transcoder
- Amazon Elastic Transcoder is a scalable media transcoding service in AWS that converts audio and video files into formats suitable for various devices. It supports a wide range of input and output formats, codecs, and resolutions, making it versatile for different media processing needs. With its pay-as-you-go pricing model, users can efficiently manage transcoding costs based on usage. Elastic Transcoder integrates seamlessly with other AWS services, offering flexibility and scalability to handle transcoding tasks from small to large scale applications, including streaming services, media distribution, and content management systems.
- By using Amazon Elastic Transcoder, the company can automate the media conversion process, ensuring that files stored in Amazon S3 are converted into compatible formats for mobile playback. The service integrates seamlessly with Amazon S3 for input and output storage, and it provides numerous presets to handle various formats and devices.

## Amazon Redshift Spectrum
- Amazon Redshift Spectrum is a feature in Amazon Redshift that allows users to run queries against exabytes of data in Amazon S3. It's more about data warehousing and analytics.

## Amazon Chime
- Amazon Chime is a communication service that transforms online meetings with a secure, easy-to-use application that you can trust.

---

# Billing and Cost Management
### Cost Anamoly Detection
- AWS Cost Anomaly Detection service is designed to monitor for unusual spending patterns within an AWS account. It uses machine learning to detect anomalies in your AWS spending, and alerts you when unexpected changes in cost and usage occur, which could indicate fraudulent activity or mismanagement. This service is ideal for those looking to keep track of their AWS billing and be alerted to potential issues promptly.

### AWS Cost & Usage Reports (CUR)
- AWS Cost & Usage Reports (CUR) is the most comprehensive tool for examining your AWS costs in detail. These reports deliver the most granular level of data about your AWS costs, and they enable you to drill down into your data to gain insights about your AWS usage and spending. The reports contain line item details of your costs, resource usage, and Reserved Instance usage across all AWS services. You can customize the CUR to aggregate data by the hour or day, by product or product resource, or by tags that you define yourself. AWS CUR provides the most extensive data to understand, analyze, and optimize your AWS costs.

### AWS Budgets
- AWS Budgets allows you to set custom cost and usage budgets to manage your AWS costs. When your costs or usage exceed your budget amount, AWS sends you alerts.

### AWS Cost Explorer
- AWS Cost Explorer allows you to visualize, understand, and manage your AWS costs and usage over time. It offers a set of reports with different views of your cost data, like monthly spend by AWS service or daily spend.
- AWS Cost Explorer is an analytical tool that enables you to visualize, understand, and manage your AWS costs and usage over time. With Cost Explorer, you can identify trends, pinpoint cost drivers, and detect anomalies. Specifically, it provides detailed reports and insights into your spending patterns, including recommendations for how you might reduce costs by rightsizing your services. For Amazon EC2 instances, Cost Explorer can help identify instances that are underutilized or oversized, offering suggestions on how to adjust the size or type of these instances to better align with actual usage, thereby optimizing costs.

## AWS Billing Conductor
- AWS Billing Conductor (ABC) is a billing and cost allocation service designed for AWS resellers, managed service providers (MSPs), or large organizations with multiple internal departments or business units that need to manage and customize billing and chargeback.
- AWS Billing Conductor allows customers to customize their AWS billing and create personalized billing experiences. This service can help in managing and understanding your AWS bill.
- AWS Billing Conductor allows you to:
  - Create custom billing rates and discounts for different groups of accounts (called account groups).
  - Define pricing rules (e.g., markups or markdowns).
  - Generate custom views of billing information for internal teams or customers without affecting the actual AWS charges.
- You get the real AWS bill with discounted rates, but you need to:
  - Apply custom pricing (e.g., 5% markup for Client A, 10% for Client B).
  - Show custom billing summaries to each client.
  - Keep internal AWS pricing private.

---

# AWS Cloud Adoption Framework (CAF)
### People Perspective
- Cloud fluency emphasizes the importance of education and knowledge across the organization about cloud technologies and AWS services. Ensuring that staff are cloud-fluent means they understand not only the technical aspects but also the operational, financial, and business implications of using AWS services. This comprehensive understanding enables the organization to maximize the benefits of cloud adoption, fostering innovation, accelerating time to market, and optimizing costs. Cloud fluency supports a culture of continuous learning, empowering teams to make informed decisions, innovate with new services, and adapt processes to use cloud advantages fully. By focusing on cloud fluency, organizations can ensure their workforce is equipped with the necessary skills and knowledge to navigate the complexities of cloud adoption and harness the full potential of AWS Cloud technologies.

### Governance Perspective
- The AWS Cloud Adoption Framework (CAF) is a comprehensive guide designed to assist organizations in adopting AWS cloud services effectively. It provides a structured approach covering business, people, and technology aspects to facilitate successful cloud migration and integration. CAF helps organizations align their cloud strategy with business objectives, establish a governance model, define roles and responsibilities, and implement best practices for security, compliance, and cost management. It supports organizations in navigating the complexities of cloud adoption while ensuring scalability, agility, and innovation.
- Benefits management within CAF focuses on identifying, quantifying, and realizing the expected outcomes from cloud adoption initiatives. This involves defining clear metrics, establishing monitoring mechanisms, and optimizing cloud usage to maximize cost savings, operational efficiency, scalability, and innovation within the organization's digital transformation journey.

---

## AWS IAM Identity Center (AWS Single Sign-On)
- AWS IAM Identity Center (AWS SSO) simplifies the management of access to multiple AWS accounts and business applications by allowing users to sign in with a single set of credentials. This service enables administrators to easily manage user access at scale and improve security by eliminating the need for multiple passwords. It also supports automatic user provisioning, which further simplifies the process and ensures users have access only to the resources they need for their job functions.

## AWS DataSync
- AWS DataSync is an online data movement and discovery service that simplifies and accelerates data migrations to AWS as well as moving data to and from on-premises storage, edge locations, other cloud providers, and AWS Storage services.
- AWS DataSync includes automatic data validation as a feature. After DataSync transfers the data to the destination, it automatically validates the data by comparing the metadata from the source and destination locations, ensuring that data was transferred accurately and completely. This helps users to have confidence that the transferred data is consistent with the source data.

## AWS Trusted Advisor
- AWS Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices. It gives recommendations to help you improve your AWS environment in areas such as cost optimization, performance, security, fault tolerance, and service limits.

---

# AWS Technical Support
### Business Support Plan
- The Business Support plan is specifically designed for users who need rapid and comprehensive support. This plan ensures access to AWS technical support within one hour. It includes 24/7 phone, email, and chat support for critical issues, meaning businesses can receive timely assistance when they need it most. Additionally, this plan provides support for third-party applications, offers best practice recommendations, and proactively monitors AWS infrastructure. By opting for the Business Support plan, businesses can achieve a balance between cost and level of service, ensuring that their operational needs are met without the higher cost of the Enterprise plan.

### Basic Support Plan
- The Basic Support plan provides very limited support options, such as 24/7 customer service, access to documentation, whitepapers, and support forums. It does not include access to technical support engineers. Therefore, it is not suitable for businesses that require urgent technical assistance.

### Developer Support Plan
- The Developer Support plan is slightly more advanced than the Basic plan, offering business day access to support for technical issues but only guarantees a response time of 12-24 hours based on severity. This plan is geared toward non-mission critical workloads and lacks immediacy and comprehensiveness.

### Enterprise Support Plan
- The Enterprise Support plan provides the highest level of support, including access to a Technical Account Manager, concierge support, and faster response times across all issues. While it does provide technical support within an hour, the cost associated with this plan is significantly higher and may not be justified for many businesses, making it less cost-effective compared to the Business plan.

---

# VPC
### Transit Gateways
- AWS Transit Gateway is a network transit hub that connects Amazon VPCs and on-premises networks through a central hub. This simplifies network architectures, reducing the complexity and management overhead associated with connecting multiple VPCs and networks. By providing a scalable and high-performance solution, AWS Transit Gateway enables efficient routing and connectivity, supporting thousands of VPCs and VPN connections. It integrates seamlessly with AWS services, enhances security, and supports features like multicast and inter-region peering, making it a versatile choice for large-scale, dynamic cloud environments.

### AWS VPN
- AWS VPN enables encrypted connections from on-premises networks or mobile devices to AWS. Although it provides secure connectivity.

### AWS PrivateLink
- AWS PrivateLink enables private connectivity between VPCs, AWS services, and on-premises applications without using public IPs. However, it is more suited for service-to-service communication within the same or interlinked VPCs.

---

## AWS Outposts
- AWS Outposts is a fully managed service that extends AWS infrastructure, services, APIs, and tools to virtually any on-premises facility, including data centers and co-location environments, creating a truly consistent hybrid experience. This solution is ideal for applications that require low latency access to on-premises systems, local data processing, or local data storage. By bringing native AWS services to on-premises locations, Outposts enables customers to operate in a hybrid environment seamlessly, using the same AWS management console, APIs, and control services they're familiar with in the cloud. This ensures a unified way to manage both cloud and on-premises resources, simplifying operations and reducing the time to market for applications that need to span both environments.

## AWS Direct Connect
- AWS Direct Connect provides a dedicated network connection from on-premises to AWS, enhancing bandwidth throughput and providing a more consistent network experience than internet-based connections, it is primarily intended for linking your existing networks with AWS. Although it facilitates the connection to AWS, it does not extend AWS services, APIs, or tools into on-premises environments.

## Amazon CodeGuru
- Amazon CodeGuru is a developer tool that provides intelligent recommendations to improve code quality and identify the most expensive lines of code in your applications. CodeGuru can help optimize the performance and cost of software applications by improving code efficiency.

## Amazon SageMaker
- Amazon SageMaker is a comprehensive machine learning service that enables developers and data scientists to build, train, and deploy machine learning models quickly. SageMaker can optimize the cost and efficiency of machine learning workflows.

## Amazon Pinpoint
- Amazon Pinpoint is a flexible and scalable outbound and inbound marketing communication service. It allows you to engage with your customers by sending them email, SMS, voice, and push notifications. Amazon Pinpoint is primarily used for understanding user behavior, defining which users to target, determining which messages to send, scheduling the best time to deliver the messages, and then analyzing the results of your campaigns.

## Cloud Design Principle of Loose Coupling (AWS Well-Architected Framework)
- _Components interacting through middleware interfaces encapsulate functionality, enabling the components to evolve independently without causing disruptions in the overall system. This approach adheres to the principle of loose coupling, which minimizes dependencies between components. Middleware provides a standard method for communication, enhancing system flexibility, scalability, and maintainability. By decoupling components, changes, updates, or replacements of individual parts can be done seamlessly, leading to a more resilient architecture. This design is particularly beneficial in cloud environments where scalability and rapid iteration are critical._


## Security Best Practices
- Use AWS Organizations Service Control Policies (SCPs) to enforce mandatory access key rotation every 90 days.
  - Service Control Policy (SCPs) is a feature of AWS Organizations that allows administrators to define specific permissions for accounts under their management. SCPs enable central governance and restriction of services and actions across multiple AWS accounts. They act as a guardrail, ensuring accounts operate within defined parameters and can be used to enforce compliance, security practices, and cost controls by either whitelisting or blacklisting specific AWS service actions.
  - An SCP that mandates the rotation of IAM user access keys every 90 days can be applied across all accounts in the organization, ensuring compliance. With this policy in place, IAM users will be unable to perform AWS actions with keys older than 90 days, prompting them to rotate their keys. This method offers a proactive and enforced approach to maintain security best practices.

## Amazon QuickSight
- Amazon QuickSight is a fast, cloud-powered business intelligence service that makes it easy to deliver insights to everyone in your organization. With QuickSight, you can create and publish interactive dashboards that include ML Insights. Dashboards can then be accessed from any device, and embedded into your applications, portals, and websites. Hence, for developing a business intelligence solution with a focus on dashboard reporting, Amazon QuickSight is the most suitable AWS service.

## Amazon Redshift
- Amazon Redshift is a fully managed, petabyte-scale data warehouse service in the cloud. It's crucial for analyzing large datasets and optimizing queries. But it doesn't provide a dashboard or reporting features like QuickSight.

## Amazon Athena
- Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. It doesn't provide dashboard capabilities. For visualizations and dashboarding, data from Athena would typically be imported into a tool like QuickSight.

## AWS Glue
- AWS Glue is a fully managed extract, transform, and load (ETL) service that makes it easy for users to prepare and load their data for analytics. Glue can help organize, cleanse, validate and format data. It doesn't provide the end-user dashboarding and visualization capabilities that QuickSight does.

---

# AWS Security Hub
### AWS Systems Manager(SSM)
- AWS Systems Manage gives you visibility and control of your infrastructure on AWS. This service allows you to group your resources according to applications, view operational data for monitoring and troubleshooting, and take action on your groups of resources. AWS Systems Manager simplifies resource and application management, shortens the time to detect and resolve operational problems, and makes it easy to operate and manage your infrastructure securely at scale. It provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks across your AWS resources.
- AWS Systems Manager allows you to view and control your AWS resources. It helps to identify and resolve operational issues quickly across multiple AWS resources, thereby simplifying operational tasks and reducing the time it takes to resolve them. With AWS Systems Manager, you can group resources, like Amazon EC2 instances or Amazon S3 buckets, by application, view operational data for monitoring and troubleshooting, and take action on your groups of resources. AWS Systems Manager helps you to maintain security and compliance by scanning your instances against your patch, configuration, and custom policies.

### Amazon Inspector
- Amazon Inspector is a security assessment service that helps improve the security and compliance of applications deployed on AWS. It does so by assessing applications for vulnerabilities or deviations from best practices.
- Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. It automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. After performing an assessment, Amazon Inspector produces a detailed list of security findings prioritized by level of severity. It can continuously monitor the company's EC2 instances, and it will be a perfect fit for the needs. The Inspector agent that runs on the EC2 instances collects behavior-based data, which can help identify when and where you might have software vulnerabilities or unintended network exposures.

### AWS Shield
- AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. AWS Shield provides robust security measures.

### AWS Config
- AWS Config provides a detailed view of the resources associated with your AWS account, including how they are configured, how they are related to one another, and how the configurations and their relationships have changed over time.
- AWS Config enables you to assess, audit, and evaluate the configurations of your AWS resources. It can be used to monitor and record compliance.

---

## AWS CloudTrail
- AWS CloudTrail enables governance, compliance, operational auditing, and risk auditing of your AWS account. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command line tools, and other AWS services.
