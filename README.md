S3 Security Compliance Automation (Terraform + AWS CLI)
This project demonstrates how to deploy secure AWS S3 buckets using Terraform and verify compliance with key security controls using an automated Bash script.

🔐 Controls Implemented
SC‑28 – Encryption at Rest

S3 bucket configured with AES‑256 server‑side encryption.

CM‑6 – Configuration Management (Versioning)

Versioning enabled to protect against accidental deletion or overwrite.

AC‑3 – Access Control (Public Access Block)

All four public access block settings enforced.

🛠 Tools & Technologies
Terraform (Infrastructure as Code)

AWS CLI

Bash scripting

IAM roles & least privilege

S3 security best practices

📁 What This Project Includes
Terraform code to deploy secure S3 buckets

Automated compliance verification script (verify.sh)

Screenshots of successful deployment and compliance checks

Documentation explaining the architecture and controls

🚀 How to Run
bash
terraform init
terraform apply
./verify.sh

📊 Sample Output
Code
SSEAlgorithm: AES256
Versioning: Enabled
PublicAccessBlock: All true
Bucket is compliant.

WHY THIS MATTERS
Misconfigured S3 buckets are one of the most common causes of cloud data breaches.
This project demonstrates how to enforce encryption, versioning, and public access restrictions using Terraform and verify compliance automatically using AWS CLI.
It reflects real‑world cloud security engineering practices used in GRC, DevSecOps, and cloud audit roles.