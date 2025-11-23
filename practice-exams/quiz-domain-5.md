# 📝 Domain 5: Security and Governance Quiz (14% Weight)

Focus: Task 5.1 (Security), 5.2 (Compliance)

---

**Q1. (D5.1) According to the AWS Shared Responsibility Model, which security task is the customer ALWAYS responsible for when using Amazon Bedrock to access a Foundation Model?**
A. Securing the Bedrock infrastructure and network.
B. Training and patching the underlying FM.
C. Securing customer data stored in Amazon S3 used for RAG/Fine-Tuning.
D. Protecting the global physical infrastructure hosting the service.

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. Securing customer data stored in Amazon S3 used for RAG/Fine-Tuning.
**Explanation:** Securing data *in* the cloud (including data stored in S3, IAM policies, and VPC access) is the customer's responsibility. AWS manages security *of* the cloud (infrastructure).
</details>

---

**Q2. (D5.1) An attacker attempts to retrieve confidential information from the model's memory by submitting a maliciously crafted prompt that overrides the system instructions. This attack is known as:**
A. Data Poisoning
B. Model Inversion
C. Prompt Injection
D. Denial of Service (DoS)

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. Prompt Injection
**Explanation:** Prompt Injection is the specific GenAI security risk where an attacker uses a carefully crafted input to manipulate the model into ignoring its pre-set safety guidelines or leaking information.
</details>

---

**Q3. (D5.2) Which AWS service continuously monitors and records the configuration of your AWS resources (like S3 buckets or VPCs) to help you ensure they adhere to compliance rules and policies?**
A. AWS Audit Manager
B. AWS Config
C. AWS CloudTrail
D. Amazon Macie

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** B. AWS Config
**Explanation:** AWS Config is the service used for continuous configuration monitoring and compliance checking against defined rules. AWS Audit Manager automates evidence collection for formal audits.
</details>

---

**Q4. (D5.2) To comply with regulations requiring a detailed, immutable log of all user actions and API calls made within an AWS account, which service should be used?**
A. Amazon GuardDuty
B. AWS Identity and Access Management (IAM)
C. AWS CloudTrail
D. AWS KMS

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. AWS CloudTrail
**Explanation:** CloudTrail provides the log of all API calls and user activity, serving as the primary audit and governance trail.
</details>
