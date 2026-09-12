# Amazon-Q-Developer-Integration-Project
Setup and integration of Amazon Q Developer for AI-assisted coding, cloud architectural guidance, and secure development workflows.

Amazon Q Developer Integration Project
This project documents the setup and configuration of Amazon Q Developer in Visual Studio Code. This integration adds AI-powered pair programming and cloud architectural guidance to my local development workflow.

Project Overview
The objective was to establish an AI-assisted development environment capable of:

Real-time inline code suggestions.
Context-aware architectural guidance for AWS services.
Automated code reviews and security scanning.
Workflow Setup
1. Installation & Environment Configuration
Integrated the Amazon Q extension via terminal to ensure a repeatable, scripted developer environment.
<img width="1087" height="305" alt="image" src="https://github.com/user-attachments/assets/b9041020-9b19-49e3-95f0-03857dd3ebcc" />


2. Authentication & Security
Configured secure access using AWS Builder ID. This implements an OAuth 2.0 device flow, ensuring zero hardcoded credentials are stored locally, adhering to the Principle of Least Privilege.

3. Proof of Work (Testing)
Validated the integration by generating a functional recursive algorithm and querying AWS best practices for S3 bucket security.
<img width="781" height="925" alt="image" src="https://github.com/user-attachments/assets/c9fa0d56-9980-4848-95f5-367b22d4639e" />

Key Learnings

Context-Aware AI: Leveraged @Pin Context to supply project-specific files, improving AI output accuracy.

Infrastructure Governance: Used Amazon Q as an architectural advisor to validate security configurations (e.g., S3 encryption, logging, and IAM policies).

DevEx Automation: Practiced managing environment variables and PATH configuration to streamline tool integration.

Built as part of a cloud engineering developer experience study.
