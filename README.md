**STYAVA-AI900-Fundamentals-Project-Kit**

**The AI-900 Deconstructed: Core Concepts, Battle Plan, and Code Challenges**

This repository provides the structured notes, essential cheat sheets, and security blueprint from the STYAVA 2-Day Azure AI Fundamentals Masterclass. We are turning conceptual knowledge into deployable skills.

**🧭 I. The AI Services Map (System Thinking)**
The AI-900 is about knowing the right tool for the job. Our Masterclass defined the five pillars of Azure AI.

![5 Pillars of Azure AI] {ai900 diagram.png}

Key Service Distinctions (The Expert View)
Azure Machine Learning:

Core Function: Platform for building, training, and deploying custom models (Regression, Classification)

The STYAVA Takeaway: Choose AML when you need custom prediction, model versioning, or complex Python workflows (Notebooks).

Custom Vision Service:

Core Function: Training a model on your own images to detect specific, custom objects (e.g., dog breed, custom meter type).

The Problem Solver: You must use this when Computer Vision's pre-trained generic model fails.

Forms Recognizer (Document Intelligence):

Core Function: Automates data extraction from structured documents (receipts, invoices, passports).

The STYAVA Takeaway: This is an Applied AI Service—it solves one specific problem very well, minimizing development effort.

🧠 II. Exam Cheat Sheet: ML & Responsible AI
ML Model Types (The Quiz Review)
Regression: Predicts a numeric value (e.g., stock price, credit amount).

Classification: Predicts a category (e.g., Yes/No, Positive/Negative, Approve/Reject).

Clustering: Finds groups in unlabeled data based on similarities (e.g., grouping online shoppers).

The 6 Responsible AI Principles (Non-Negotiable)
Fairness: Mitigation of bias in models (e.g., loan approvals).

Transparency: Giving clear explanations of how the AI system works.

Reliability & Safety: Ensuring the AI solution is robust, tested, and avoids causing harm (e.g., driverless taxis).

Accountability: Following a governance framework and meeting ethical standards.

Inclusiveness: Empowering everyone, regardless of ability, gender, or ethnicity.

Privacy & Security: Protecting user data and ensuring the security of the system.

🛠️ III. The Project Kit Challenge (Bridging the Code Gap)
Since the session did not include live IaC code, this challenge forces you to build the solution discussed by the expert.

1. Starter Assets (In the /starters/ folder):
config_checklist.md: Checklist of AVD configuration parameters discussed in the Masterclass.

vnet_starter.bicep: A minimal Bicep template to deploy a basic VNet and a single subnet—the necessary foundation for the challenge.

2. The Security IaC Challenge (Project 3: Enterprise Integration):
Your Task: Complete the following using Bicep (Infrastructure as Code):

Take the vnet_starter.bicep file.

Add an Azure OpenAI Service Private Endpoint resource.

Verify that your configuration ensures traffic to the AI service never touches the public internet, achieving the Privacy & Security principle.

🔗 IV. Resources & Community (The Retention Funnel)
Mandatory Study Resources
Official Learning Path: Azure AI Fundamentals

Resource Link: https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-fundamentals/

Testing Tool (Free Practice): Take the free Microsoft practice assessment to gauge your readiness.

Resource Link: https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-900/practice-assessment/

Bicep for IaC Quickstart: Essential documentation for the Private Endpoint challenge.

Resource Link: https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview

AI Content Safety (Responsible AI in Practice): How to implement guardrails against harmful content in GenAI apps.

Resource Link: https://learn.microsoft.com/en-us/azure/ai-services/content-safety/overview

🚨 Q&A, CODE HELP, and MENTORSHIP
Do not debug alone. Mentorship and the final solution review happen only here:

JOIN THE STYAVA DISCORD NOW: https://discord.gg/NSMpUgxEpF
  (Post your questions and your completed Bicep file in the dedicated channel.)
