# Tri-Cloud Essentials Practice

A hands-on learning repository documenting my Tri-Cloud Essentials
training, with notes and practical exercises across Microsoft Azure,
Amazon Web Services (AWS), and Google Cloud Platform (GCP).

## Learning Objectives

-   Understand core cloud concepts, services, identity, access
    management, storage, and monitoring.
-   Practice cloud security principles, including least privilege and
    role-based access control.
-   Explore cloud services used in data engineering and Databricks
    integrations.
-   Keep learning materials and practical work organized by cloud
    provider and study day.

## Repository Structure

```text
Tri_Cloud_Essentials_Practice/
├── README.md
└── src/
    └── Azure/
        ├── azure_lab/
        │   └── lab_1/
        │       ├── add_identity_to_vm.png
        │       ├── assign_role_at_container.png
        │       ├── create_container.png
        │       ├── create_managed_identity.png
        │       ├── create_resource_group.png
        │       ├── create_storage_account.png
        │       ├── create_vm.png
        │       ├── identity_details.png
        │       └── validate_access.png
        ├── day_1_azure_fundamentals/
        │   └── day_1_azure_fundamentals.pdf
        ├── day_2_azure_fundamentals/
        │   └── day_2_azure_fundamentals.pdf
        └── day_3_azure_fundamentals/
            └── day_3_azure_fundamentals.pdf
```

The tree reflects the current learning organization; additional files
will be added as the exercises progress.

## Current Progress --- 23 October 2026

### Azure I --- Cloud Fundamentals, Storage, and Identity

**Day 1: Cloud Fundamentals and Storage** - Reviewed cloud concepts,
subscriptions, and resource groups. - Explored Azure compute and storage
services. - Studied Azure Data Lake Storage Gen2 (ADLS Gen2),
containers, and hierarchical namespace. - Day 1 notes are maintained in
the PDF under `src/Azure/day_1_azure_fundamentals/`.

**Day 2: Identity and Access Management** - Studying Microsoft Entra ID
fundamentals. - Learning how to create and use managed identities. -
Understanding Azure role-based access control (Azure RBAC), roles, and
scope. - Practising the principal--role--resource assignment model. -
Reviewing the principle of least privilege and the
`Storage Blob Data Contributor` role pattern for blob data access.

**Day 3: Azure Security and Data Integration** - Learning Azure Key Vault fundamentals, including secrets and keys. - Understanding the differences between Azure RBAC and access policies in Key Vault. - Studying Azure Data Factory pipelines, linked services, and activities. - Exploring Azure Data Factory triggers and their use in pipeline scheduling. - Learning Azure Monitor fundamentals, including metrics, logs, and alerts.

### Lab 1: Managed Identity and RBAC

The practical lab covers:

1. Create a resource group and storage account.
2. Create a container in the storage account.
3. Create a managed identity and a virtual machine.
4. Assign the managed identity to the VM.
5. Grant an appropriate role at the container scope.
6. Validated the access by uploading files.

Screenshots documenting the lab steps are available in `src/Azure/azure_lab/lab_1/`.


## Planned Learning Areas

-   **Microsoft Azure:** Identity and access management, Key Vault,
    Azure Data Factory, Azure Monitor, Databricks connectivity, and
    Azure DevOps CI/CD.
-   **Amazon Web Services (AWS):** IAM, S3, Secrets Manager, KMS, Step
    Functions, Glue, CloudWatch, and Databricks connectivity.
-   **Google Cloud Platform (GCP):** Projects, Cloud Storage, IAM and
    service accounts, Secret Manager, Cloud Monitoring, and Databricks
    overview.

These are planned study areas; progress will be updated as each topic is
covered.

## Tools and Technologies

-   Microsoft Azure
-   Amazon Web Services (AWS)
-   Google Cloud Platform (GCP)
-   Git and GitHub
-   Databricks (cloud integration topics)

## Purpose

This repository serves as a structured record of my cloud learning
journey, including study notes, practical exercises, and examples. The
content will evolve as I complete each topic.

## Author

[shivam-a-diggibyte](https://github.com/shivam-a-diggibyte)
